# EBANX (ebanx)

EBANX is a Brazil-founded payments processor specializing in pay-in, payout, and cross-border payments for Latin America and other emerging markets. The EBANX API ecosystem covers pay-in (Direct API, Payment Page, Payment Link, Drop-in), payouts (local and cross-border), foreign exchange, card tokenization, and signed payment notifications across 19+ countries. EBANX is best known for connecting global merchants to local payment methods like Pix, Pix Automatico, Boleto, OXXO, SPEI, PSE, Efecty, PagoEfectivo, Nequi, Mercado Pago, NuPay, and PicPay.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ebanx/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Payments, Pay-in, Payouts, Foreign Exchange, Tokenization, LATAM, Emerging Markets, Pix, Boleto, OXXO, SPEI, PSE, Cross-Border, Webhooks

## APIs

### EBANX Pay-in Direct API

Direct integration that gives merchants full control of the checkout experience across cards (with 3DS and installments), Pix, Boleto, OXXO, SPEI, PSE, Efecty, PagoEfectivo, and many local e-wallets.

- **Human URL:** https://docs.ebanx.com/api/
- **Base URL:** https://api.ebanxpay.com
- **OpenAPI:** [openapi/ebanx-pay-in-direct-api-openapi.yml](openapi/ebanx-pay-in-direct-api-openapi.yml)
- **Capability:** [capabilities/pay-in-direct.yaml](capabilities/pay-in-direct.yaml)

### EBANX Payment Page API

Hosted EBANX checkout where the merchant posts payment parameters and EBANX handles UI, validation, and processing, then returns the customer via a redirect URL.

- **Human URL:** https://docs.ebanx.com/docs/pay-in/solution/integration-methods/payment-page
- **Base URL:** https://api.ebanxpay.com
- **OpenAPI:** [openapi/ebanx-payment-page-api-openapi.yml](openapi/ebanx-payment-page-api-openapi.yml)
- **Capability:** [capabilities/payment-page.yaml](capabilities/payment-page.yaml)

### EBANX Tokenization API

Tokenize cards on EBANX so PAN never touches merchant servers, and refresh CVVs on stored tokens before reusing them for high-risk charges.

- **Human URL:** https://docs.ebanx.com/api/
- **OpenAPI:** [openapi/ebanx-tokenization-api-openapi.yml](openapi/ebanx-tokenization-api-openapi.yml)
- **Capability:** [capabilities/card-tokenization.yaml](capabilities/card-tokenization.yaml)

### EBANX FX API

Quote FX rates between merchant pricing currency (USD/EUR) and EBANX market currencies, and mint a short-lived FX token to lock a rate for a future Direct Payment.

- **Human URL:** https://docs.ebanx.com/api/
- **OpenAPI:** [openapi/ebanx-fx-api-openapi.yml](openapi/ebanx-fx-api-openapi.yml)
- **Capability:** [capabilities/foreign-exchange.yaml](capabilities/foreign-exchange.yaml)

### EBANX Payout API

Disburse from a merchant funded balance to bank accounts and e-wallets across EBANX markets. Supports local (merchant pre-funds in local currency) and cross-border (merchant funds in USD, EBANX converts) flows.

- **Human URL:** https://docs.ebanx.com/docs/payout/payouts-overview
- **Base URL:** https://api.ebanxpay.com
- **OpenAPI:** [openapi/ebanx-payout-api-openapi.yml](openapi/ebanx-payout-api-openapi.yml)
- **Capability:** [capabilities/payouts.yaml](capabilities/payouts.yaml)

### EBANX Payment Notifications

Signed HTTP POST callbacks delivered to a merchant-configured Notification URL for payment, refund, chargeback, and Pix MED return-request events.

- **Human URL:** https://docs.ebanx.com/docs/payments/guides/features/payment-notifications/
- **AsyncAPI:** [asyncapi/ebanx-notifications-asyncapi.yml](asyncapi/ebanx-notifications-asyncapi.yml)
- **Capability:** [capabilities/payment-notifications.yaml](capabilities/payment-notifications.yaml)

## Artifacts

| Artifact | Path |
|---|---|
| Plans & Pricing | [plans/ebanx-plans-pricing.yml](plans/ebanx-plans-pricing.yml) |
| Rate Limits | [rate-limits/ebanx-rate-limits.yml](rate-limits/ebanx-rate-limits.yml) |
| FinOps Alignment | [finops/ebanx-finops.yml](finops/ebanx-finops.yml) |
| Vocabulary | [vocabulary/ebanx-vocabulary.yml](vocabulary/ebanx-vocabulary.yml) |
| JSON-LD Context | [json-ld/ebanx-context.jsonld](json-ld/ebanx-context.jsonld) |
| Spectral Ruleset | [rules/ebanx-rules.yml](rules/ebanx-rules.yml) |

## Geographic Coverage

Brazil, Mexico, Colombia, Chile, Argentina, Peru, Ecuador, Bolivia, Paraguay, Uruguay, Guatemala, Costa Rica, Panama, Dominican Republic, India, the Philippines, Kenya, Nigeria, South Africa, Egypt.

## Authentication

EBANX APIs authenticate with an **integration key** that is distinct for sandbox and production. The integration key is historically passed as `integration_key` in the JSON request body and is also accepted via the `x-ebanx-integration-key` header. EBANX additionally supports **JWS Authentication** for enhanced request integrity.

## Environments

| Environment | Base URL |
|---|---|
| Production | https://api.ebanxpay.com |
| Sandbox | https://sandbox.ebanxpay.com |

## Maintainers

- Kin Lane — info@apievangelist.com — https://apievangelist.com
- EBANX Sales Engineering — sales.engineering@ebanx.com — https://www.ebanx.com
