---
name: Accept a hosted-iframe ecommerce payment
description: Take a card or bank payment through the Versapay-hosted iframe so sensitive payment data never transits the merchant app (reduced PCI scope).
api: openapi/versapay-ecommerce-api.json
operations: [createSession, getToken, createSale, createPayment]
---

# Accept a hosted-iframe ecommerce payment

Use the Versapay Ecommerce API (base `https://secure.versapay.com/api/v2`) with the
client-side JavaScript SDK. Authenticate server-to-server with HTTPS Basic
(API Token & Key). Test everything against UAT (`https://uat.versapay.com`) first.

## Steps
1. **Create a session** — server-side, call `createSession` (`POST /sessions`).
   Persist the returned session `id`.
2. **Render the iframe** — client-side, initialize the Versapay payment SDK with the
   session `id`. The customer enters a payment method inside the Versapay-hosted iframe.
3. **Tokenize** — the SDK returns a payment-method token to your client code; send it
   back to your server. (Programmatically, `getToken` — `POST /sessions/{id}/tokens`.)
4. **Create the sale** — server-side, call `createSale` (`POST /sessions/{id}/sales`)
   with the session `id` and token.
5. **Take payment** — call `createPayment` (`POST /sessions/{id}/sales/{saleid}/payments`).

## Rules
- Never handle raw PAN/bank data server-side — the iframe keeps it out of your PCI scope.
- Test cards, ACH numbers, and CVV/AVS test values are in `sandbox/versapay-sandbox.yml`
  (e.g. Visa `4895281000000006`; `4264280001234500` always declines).
- Errors are custom JSON `{ "success": false, ... }` — see `errors/versapay-problem-types.yml`.
