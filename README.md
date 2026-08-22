# EBANX (ebanx)

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

EBANX is a Brazil-founded payments processor specializing in pay-in, payout, and cross-border payments for Latin America and other emerging markets. The EBANX API ecosystem covers Pay-in (Direct API, Payment Page, Payment Link, Drop-in), Payouts (local and cross-border), Foreign Exchange, Card Tokenization, and signed Payment Notifications across 19+ countries including Brazil, Mexico, Colombia, Chile, Argentina, Peru, Ecuador, Bolivia, Uruguay, Paraguay, Costa Rica, Guatemala, Panama, Dominican Republic, India, the Philippines, Kenya, Nigeria, South Africa, and Egypt. EBANX is best known for connecting global merchants to local payment methods like Pix, Pix Automatico, Boleto, OXXO, SPEI, PSE, Efecty, PagoEfectivo, Nequi, Mercado Pago, NuPay, PicPay, and dozens of others, plus an expanding recurring-payments product on top of alternative payment methods.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ebanx/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ebanx/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming

## Tags

- Payments
- Pay-in
- Payouts
- Foreign Exchange
- Tokenization
- LATAM
- Emerging Markets
- Pix
- Boleto
- OXXO
- SPEI
- PSE
- Cross-Border
- Webhooks

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### EBANX Pay-in Direct API

Direct integration that gives merchants full control of the checkout experience. Accept cards (with optional 3DS and installments), Pix, Boleto, OXXO, SPEI, PSE, Efecty, PagoEfectivo, and many local e-wallets across EBANX markets. Includes capture, query, cancel, refund, refundOrCancel, installment-plan lookup, BIN lookup, available-banks lookup, available e-wallets lookup, and customer bank-info resend.

- **Human URL:** [https://docs.ebanx.com/api/](https://docs.ebanx.com/api/)
- **Base URL:** `https://api.ebanxpay.com`

#### Tags

- Payments
- Pay-in
- Direct API
- Pix
- Boleto
- OXXO
- SPEI
- PSE
- Cards

#### Properties

- [API Reference](https://docs.ebanx.com/api/)
- [Documentation](https://docs.ebanx.com/docs/pay-in/solution/integration-methods/direct-api)
- [Documentation](https://docs.ebanx.com/docs/pay-in/solution/pay-in-guide)
- [OpenAPI](openapi/ebanx-pay-in-direct-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ebanx-pay-in-direct-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-pay-in-direct-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/ebanx-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ebanx-refund-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/ebanx-payment-structure.json)
- [Example](examples/ebanx-create-direct-payment-pix-example.json)
- [Example](examples/ebanx-create-direct-payment-card-example.json)

### EBANX Payment Page API

Hosted EBANX checkout. The merchant submits payment parameters and EBANX renders the full payment UI, validates the customer input, processes the payment, and returns the customer to the merchant via a redirect URL. Ideal for merchants who want to outsource PCI scope and per-market UI work.

- **Human URL:** [https://docs.ebanx.com/docs/pay-in/solution/integration-methods/payment-page](https://docs.ebanx.com/docs/pay-in/solution/integration-methods/payment-page)
- **Base URL:** `https://api.ebanxpay.com`

#### Tags

- Payments
- Pay-in
- Hosted Checkout

#### Properties

- [Documentation](https://docs.ebanx.com/docs/pay-in/solution/integration-methods/payment-page)
- [OpenAPI](openapi/ebanx-payment-page-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ebanx-payment-page-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-payment-page-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EBANX Tokenization API

Tokenize cards on EBANX so PAN never touches merchant servers, and refresh CVVs on stored tokens before high-risk reuse. Reusable tokens power one-click checkout, subscriptions, and stored-card flows.

- **Human URL:** [https://docs.ebanx.com/api/](https://docs.ebanx.com/api/)
- **Base URL:** `https://api.ebanxpay.com`

#### Tags

- Payments
- Tokenization
- Cards
- PCI

#### Properties

- [API Reference](https://docs.ebanx.com/api/)
- [OpenAPI](openapi/ebanx-tokenization-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ebanx-tokenization-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-tokenization-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/ebanx-card-token-schema.json) — [JSON Schema](https://json-schema.org/specification)

### EBANX FX API

Quote current FX rates between a merchant pricing currency (typically USD or EUR) and EBANX market currencies, and mint a short-lived FX token to lock a rate so a quoted price is honored when the underlying Direct Payment is captured.

- **Human URL:** [https://docs.ebanx.com/api/](https://docs.ebanx.com/api/)
- **Base URL:** `https://api.ebanxpay.com`

#### Tags

- Foreign Exchange
- FX
- Cross-Border

#### Properties

- [API Reference](https://docs.ebanx.com/api/)
- [OpenAPI](openapi/ebanx-fx-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ebanx-fx-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-fx-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EBANX Payout API

Send money from a merchant funded balance to a payee bank account or e-wallet in any EBANX market. Supports local payouts (merchant funds in local currency) and cross-border payouts (merchant deposits USD and EBANX converts to the payee currency). Includes create, commit, cancel, retrieve, search, simulate, attach invoice, balance, bank list, bank detail, payee creation, and bank-account verification.

- **Human URL:** [https://docs.ebanx.com/docs/payout/payouts-overview](https://docs.ebanx.com/docs/payout/payouts-overview)
- **Base URL:** `https://api.ebanxpay.com`

#### Tags

- Payouts
- Disbursements
- Cross-Border
- LATAM

#### Properties

- [Documentation](https://docs.ebanx.com/docs/payout/payouts-overview)
- [API Reference](https://docs.ebanx.com/api/)
- [OpenAPI](openapi/ebanx-payout-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ebanx-payout-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-payout-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/ebanx-payout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/ebanx-payout-structure.json)
- [Example](examples/ebanx-create-payout-example.json)

### EBANX Payment Notifications

Signed HTTP POST callbacks delivered to a merchant-configured Notification URL whenever a payment, refund, chargeback, or Pix MED return request changes state. Each callback carries the EBANX hash so the merchant can re-query the Direct API for authoritative payment state.

- **Human URL:** [https://docs.ebanx.com/docs/payments/guides/features/payment-notifications/](https://docs.ebanx.com/docs/payments/guides/features/payment-notifications/)

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.ebanx.com/docs/payments/guides/features/payment-notifications/)
- [AsyncAPI](asyncapi/ebanx-notifications-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Example](examples/ebanx-payment-notification-example.json)
- [Postman Collection](collections/ebanx-fx-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-fx-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ebanx-pay-in-direct-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-pay-in-direct-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ebanx-payment-page-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-payment-page-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ebanx-payout-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-payout-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ebanx-tokenization-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ebanx-tokenization-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
**Email:** sales.engineering@ebanx.com
**URL:** https://www.ebanx.com
