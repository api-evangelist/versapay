# Versapay

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Versapay is a Toronto, Canada based B2B payments company focused on accounts receivable (AR) automation and integrated payment acceptance for suppliers and their buyers. Its "Collaborative AR" platform combines electronic invoicing, customer collaboration, cash application, and embedded payment processing so businesses can invoice, get paid, and reconcile inside one workflow, with ERP-adjacent integrations for order-to-cash. Versapay serves the North American mid-market and enterprise segment and, unlike consumer money-movement players in Canada's Interac-dominated market, sits in the API-native B2B acquiring and AR/AP money-movement layer. Its API posture is genuinely public and honest: developers.versapay.com hosts a Redocly-rendered reference for a broad REST platform API (onboarding, wallets, orders, order transactions, gift cards, card-present EMV, settlement reporting, autopay, customers, invoices, divisions, notifications, and webhooks) plus a separate hosted-iframe Ecommerce API for PCI-reduced payment sessions. Authentication is HTTPS Basic access authentication using an API Token and Key issued from the account console, with a UAT sandbox alongside production and a documented webhook event model.

**Areas:** Payments · Canada · Accounts Receivable · AR Automation · Order-to-Cash · Payment Acceptance · Payment Processing · B2B Payments · Invoicing · E-Commerce · Card Present · Webhook

## Versapay on APIs.io

Everything profiled for Versapay is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/versapay/](https://apis.io/providers/versapay/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [Versapay Agreements API](https://apis.io/apis/versapay/versapay-agreements-api/) — The Agreements API from Versapay — 7 operation(s) for agreements.
- [Versapay Authentication API](https://apis.io/apis/versapay/versapay-authentication-api/) — Visit your account settings in `UAT` (https://uat.versapay.com/account) or `Production` (https://secure.versapay.com/account) to setup API credentials…
- [Versapay Autopay API](https://apis.io/apis/versapay/versapay-autopay-api/) — Autopays are a digital analog to paper pre-authorized debit agreements that businesses could use, for instance, for monthly billing.
- [Versapay Card Present EMV API](https://apis.io/apis/versapay/versapay-card-present-emv-api/) — Card Present EMV payment transactions require a Versapay certified point-of-sale terminal. Contact support@versapay.com for support & setup for POS/CP EMV…
- [Versapay Collaboration API](https://apis.io/apis/versapay/versapay-collaboration-api/) — As a supplier your customers collaborate with you through comments about invoices and/or payments.
- [Versapay Customers API](https://apis.io/apis/versapay/versapay-customers-api/) — As a supplier your customers are the entities that are invoiced. ## Webhooks When using Webhooks, your application will be notified when key events are…
- [Versapay Developers API](https://apis.io/apis/versapay/versapay-developers-api/) — Operations available to developers
- [Versapay Divisions API](https://apis.io/apis/versapay/versapay-divisions-api/) — As a supplier divisions are used to group your invoices.
- [Versapay File Imports API](https://apis.io/apis/versapay/versapay-file-imports-api/) — As a supplier you can upload customer, invoice, and payment data in CSV file formats.
- [Versapay Fund Sources API](https://apis.io/apis/versapay/versapay-fund-sources-api/) — The Fund Sources API from Versapay — 2 operation(s) for fund sources.
- [Versapay Gift Cards API](https://apis.io/apis/versapay/versapay-gift-cards-api/) — Provisioned gift cards can be activated/enabled (or deactivated/disabled) as well as have their balances loaded/re-loaded with an amount. Contact…
- [Versapay Internal API](https://apis.io/apis/versapay/versapay-internal-api/) — Operations intended only to the iframe front end
- [Versapay Invoices API](https://apis.io/apis/versapay/versapay-invoices-api/) — As a supplier invoices are your receivables. ## Webhooks When using Webhooks, your application will be notified when key events are triggered for an invoice.
- [Versapay Invoicing Payments API](https://apis.io/apis/versapay/versapay-invoicing-payments-api/) — As a supplier a payments are made by customers for invoices issued to them. ## Webhooks When using Webhooks, your application will be notified when key…
- [Versapay Notifications API](https://apis.io/apis/versapay/versapay-notifications-api/) — As a supplier you can notify customers about their invoices.
- [Versapay Onboarding API](https://apis.io/apis/versapay/versapay-onboarding-api/) — Onboarding supports the automated process of applying for merchant services. Contact support@versapay.com for support & setup of supplier onboarding partner…
- [Versapay Order Transactions API](https://apis.io/apis/versapay/versapay-order-transactions-api/) — Order-based card/ACH and card present EMV payment transactions include verify, authorize, capture, sale, void, return refund, and return credit transaction…
- [Versapay Orders API](https://apis.io/apis/versapay/versapay-orders-api/) — The Order entity represents the sales document in the ERP system. The fields in the ERP system should be aligned as closely as possible with the fields in…
- [Versapay Reference Data API](https://apis.io/apis/versapay/versapay-reference-data-api/) — For convenience purposes only, Versapay can supply third party reference data to its partners and users. This data can be used to implement client-side…
- [Versapay Settlement Reporting API](https://apis.io/apis/versapay/versapay-settlement-reporting-api/) — Settlement Reporting includes retrieval of monthly statements, daily deposit amounts (including fee information), transaction exceptions (ACH reject/return…
- [Versapay Transactions API](https://apis.io/apis/versapay/versapay-transactions-api/) — The Transactions API from Versapay — 4 operation(s) for transactions.
- [Versapay Wallets API](https://apis.io/apis/versapay/versapay-wallets-api/) — The Wallet entity holds vaulted & secured payment methods owned by a customer (buyer/payor) that can be used to make payments via Collaborative AR (online…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Versapay Webhooks](https://apis.io/asyncapis/versapay/versapay-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [versapay](https://apis.io/servers/versapay/versapay/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Versapay Agentic Access](https://apis.io/agentic-access/versapay/versapay-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Versapay API Reference](https://apis.io/collections/versapay/open-versapay-api-reference/)
- [Versapay Ecommerce API](https://apis.io/collections/versapay/open-versapay-ecommerce-api/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Versapay Api Reference Overlay](https://apis.io/overlays/versapay/versapay-api-reference-overlay/)
- [Versapay Ecommerce Api Overlay](https://apis.io/overlays/versapay/versapay-ecommerce-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Versapay Authentication](https://apis.io/security/versapay/versapay-authentication/)
- [Versapay Domain Security](https://apis.io/security/versapay/versapay-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Versapay Scopes](https://apis.io/scopes/versapay/versapay-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://versapay.com)
- [Documentation](https://developers.versapay.com/)
- [API reference](https://developers.versapay.com/)
- [Sign up](https://secure.versapay.com/account)
- [Blog](https://versapay.com/blog)
- [Security](https://versapay.com/security)
- [Compliance](https://versapay.com/security)
- [Terms of service](https://versapay.com/terms)
- [Privacy policy](https://versapay.com/legal/privacy-policy)
- [Status](https://status.versapay.com)

## API Evangelist rating

**Kin Score 53.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 54.4 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 49.4 |
| Access clarity | 42.1 |

**Agent readiness 44.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 42.9** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/versapay/](https://apis.io/providers/versapay/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Versapay: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/versapay/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
