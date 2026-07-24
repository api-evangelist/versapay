---
name: Import an invoice and record a payment
description: Push an invoice into Versapay Collaborative AR, then create and reconcile a payment against it.
api: openapi/versapay-api-reference.json
operations:
  - "POST /api/imports/invoice"
  - "POST /api/imports/payment"
  - "GET /api/exports/open_invoices"
  - "GET /api/exports/payment/{reference_or_token}"
---

# Import an invoice and record a payment

Use the platform REST API (base `https://secure.versapay.com`). Authenticate with
HTTPS Basic (API Token & Key). Confirm the customer exists first
(`POST /api/imports/customer`).

## Steps
1. **Create/update the invoice** — `POST /api/imports/invoice` with the customer
   identifier and line items.
2. **Confirm it is open** — `GET /api/exports/open_invoices?watermark=<hwm>&limit=100`
   to page incrementally (limit 1-2500, default 100).
3. **Record the payment** — `POST /api/imports/payment` to apply/allocate a payment.
4. **Verify** — `GET /api/exports/payment/{reference_or_token}` to read the settled payment,
   or `GET /api/exports/payment_amounts` for allocations.

## Rules
- Pagination is watermark + limit, not page numbers — persist the high-water mark and
  poll for records newer than it (`conventions/versapay-conventions.yml`).
- Prefer webhooks (Customer/Invoice/Payment) over polling where possible; the consumer
  must return 200 and be idempotent (`asyncapi/versapay-webhooks.yml`).
- `HTTP 412 Precondition Failed` signals a validation constraint — inspect the message
  and satisfy it before retrying (`errors/versapay-problem-types.yml`).
