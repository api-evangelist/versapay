# Versapay (versapay)

Versapay is a Toronto, Canada based B2B payments company focused on accounts receivable (AR) automation and integrated payment acceptance. Its "Collaborative AR" platform combines electronic invoicing, customer collaboration, cash application, and embedded payment processing so businesses can invoice, get paid, and reconcile inside one order-to-cash workflow. Versapay ships a genuinely public developer surface: a broad REST platform API and a hosted-iframe Ecommerce API, both documented at developers.versapay.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/versapay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/versapay/refs/heads/main/apis.yml)

## Tags

- Payments
- Canada
- Accounts Receivable
- AR Automation
- Order to Cash
- Payment Acceptance
- Payment Processing
- B2B Payments
- Invoicing
- Ecommerce
- Card Present
- Webhooks

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Versapay API Reference

The core Versapay platform REST API (v1.3.35, OpenAPI 3.0.0, 86 documented paths) covering the Collaborative AR and payment-acceptance surface: onboarding applications, wallets, orders and order transactions, gift cards, card-present EMV, reference data, settlement reporting, autopay, customers, invoices and invoicing payments, divisions, notifications, collaboration, file imports, and webhooks. Authenticated with HTTPS Basic access authentication (API Token and Key) against a UAT sandbox and production.

- **Human URL:** [https://developers.versapay.com/](https://developers.versapay.com/)
- **Base URL:** `https://secure.versapay.com`

#### Properties

- [OpenAPI](openapi/versapay-api-reference.json)
- [Documentation](https://developers.versapay.com/)
- [API Reference](https://developers.versapay.com/)

### Versapay Ecommerce API

The Versapay Ecommerce server-side API (v2.0.0, OpenAPI 3.0.0, 11 documented paths) that configures payment sessions, manages customer wallets (credit cards and bank accounts), creates and captures order sales and payments, checks gift-card balances, and validates Apple Pay merchants. It pairs with a client-side JavaScript SDK and a Versapay-hosted iframe so sensitive payment data never transits the merchant application, reducing PCI scope. Served from `https://{subdomain}.versapay.com/api/v2`.

- **Human URL:** [https://developers.versapay.com/ecommerce/](https://developers.versapay.com/ecommerce/)
- **Base URL:** `https://secure.versapay.com/api/v2`

#### Properties

- [OpenAPI](openapi/versapay-ecommerce-api.json)
- [Documentation](https://developers.versapay.com/ecommerce/)
- [API Reference](https://developers.versapay.com/ecommerce/)

## Common Properties

- [Website](https://versapay.com)
- [Developer Portal](https://developers.versapay.com/)
- [Documentation](https://developers.versapay.com/)
- [API Reference](https://developers.versapay.com/)
- [Status Page](https://status.versapay.com)
- [Blog](https://versapay.com/blog)
- [Sign Up / Login](https://secure.versapay.com/account)
- [Terms of Service](https://versapay.com/terms)
- [Privacy Policy](https://versapay.com/legal/privacy-policy)
- [Security](https://versapay.com/security)
- [LinkedIn](https://www.linkedin.com/company/versapay)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
