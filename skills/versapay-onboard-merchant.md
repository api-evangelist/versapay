---
name: Onboard a merchant for payment acceptance
description: Fetch rates/terms, submit a merchant application, record completed steps, and poll application status.
api: openapi/versapay-api-reference.json
operations: [getTerms, addApplication, addApplicationSteps, getApplicationStatus, getApplicationToken]
---

# Onboard a merchant for payment acceptance

Use the Onboarding surface of the platform REST API (base `https://secure.versapay.com`),
authenticated with HTTPS Basic (API Token & Key). Run in UAT first.

## Steps
1. **Retrieve terms** — `getTerms` (`GET /api/onboarding/v1/terms`) for the rates and
   terms for merchant services.
2. **Create the application** — `addApplication` (`POST /api/onboarding/v1/applications`).
   Persist the returned application id/token.
3. **Record completed steps** — `addApplicationSteps`
   (`POST /api/onboarding/v1/application_steps`) as the merchant progresses.
4. **Poll status** — `getApplicationStatus` (`GET /api/onboarding/v1/applications/{id}`);
   recover a lost token with `getApplicationToken`
   (`GET /api/onboarding/v1/applications/search/{id}`).

## Rules
- `401` means bad/missing API Token & Key; `404` means the application id is not visible
  to your account (`errors/versapay-problem-types.yml`).
- Once approved, the merchant can transact via Order Transactions and Wallets.
