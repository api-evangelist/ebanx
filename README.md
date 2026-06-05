# EBANX (ebanx)

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
