# EBANX

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

**Areas:** Payments · Pay-In · Payouts · Foreign Exchange · Tokenization · Latin America · Emerging Markets · Pix · Boleto · OXXO · SPEI · PSE

## EBANX on APIs.io

Everything profiled for EBANX is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ebanx/](https://apis.io/providers/ebanx/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [EBANX Tokenization API](https://apis.io/apis/ebanx/ebanx-tokenization-api/) — Tokenize cards on EBANX so PAN never touches merchant servers, and refresh CVVs on stored tokens before high-risk reuse. Reusable tokens power one-click…
- [EBANX FX API](https://apis.io/apis/ebanx/ebanx-fx-api/) — Quote current FX rates between a merchant pricing currency (typically USD or EUR) and EBANX market currencies, and mint a short-lived FX token to lock a…
- [EBANX Payment Notifications](https://apis.io/apis/ebanx/ebanx-notifications/) — Signed HTTP POST callbacks delivered to a merchant-configured Notification URL whenever a payment, refund, chargeback, or Pix MED return request changes…
- [EBANX PaymentPage API](https://apis.io/apis/ebanx/ebanx-paymentpage-api/) — The PaymentPage API from EBANX — 1 operation(s) for paymentpage.
- [EBANX Payments API](https://apis.io/apis/ebanx/ebanx-payments-api/) — The Payments API from EBANX — 12 operation(s) for payments.
- [EBANX Payouts API](https://apis.io/apis/ebanx/ebanx-payouts-api/) — The Payouts API from EBANX — 12 operation(s) for payouts.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [EBANX Payment Notifications](https://apis.io/asyncapis/ebanx/ebanx-notifications-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [payment.chargeback](https://apis.io/channels/ebanx/payment-chargeback/)
- [payment.med-pix](https://apis.io/channels/ebanx/payment-med-pix/)
- [payment.refund](https://apis.io/channels/ebanx/payment-refund/)
- [payment.update](https://apis.io/channels/ebanx/payment-update/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ebanx](https://apis.io/servers/ebanx/ebanx/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ebanx Agentic Access](https://apis.io/agentic-access/ebanx/ebanx-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [EBANX Card Token](https://apis.io/schemas/ebanx/ebanx-card-token/)
- [EBANX Payment](https://apis.io/schemas/ebanx/ebanx-payment/)
- [EBANX Payout](https://apis.io/schemas/ebanx/ebanx-payout/)
- [EBANX Refund](https://apis.io/schemas/ebanx/ebanx-refund/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Ebanx Payment Structure](https://apis.io/json-structure/ebanx/ebanx-payment-structure/)
- [Ebanx Payout Structure](https://apis.io/json-structure/ebanx/ebanx-payout-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ebanx Context](https://apis.io/jsonld/ebanx/ebanx-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [EBANX Vocabulary](https://apis.io/vocabularies/ebanx/ebanx-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Ebanx Create Direct Payment Card Example](https://apis.io/examples/ebanx/ebanx-create-direct-payment-card-example/)
- [Ebanx Create Direct Payment Pix Example](https://apis.io/examples/ebanx/ebanx-create-direct-payment-pix-example/)
- [Ebanx Create Payout Example](https://apis.io/examples/ebanx/ebanx-create-payout-example/)
- [Ebanx Payment Notification Example](https://apis.io/examples/ebanx/ebanx-payment-notification-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [EBANX FX API](https://apis.io/collections/ebanx/open-ebanx-fx-api/)
- [EBANX Pay-in Direct API](https://apis.io/collections/ebanx/open-ebanx-pay-in-direct-api/)
- [EBANX Payment Page API](https://apis.io/collections/ebanx/open-ebanx-payment-page-api/)
- [EBANX FX PaymentPage API](https://apis.io/collections/ebanx/open-ebanx-paymentpage-api/)
- [EBANX FX Payments API](https://apis.io/collections/ebanx/open-ebanx-payments-api/)
- [EBANX Payout API](https://apis.io/collections/ebanx/open-ebanx-payout-api/)
- [EBANX FX Payouts API](https://apis.io/collections/ebanx/open-ebanx-payouts-api/)
- [EBANX FX Tokenization API](https://apis.io/collections/ebanx/open-ebanx-tokenization-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [EBANX — asyncapi rules](https://apis.io/rules/ebanx/ebanx-asyncapi-spectral-rules/)
- [EBANX — jsonschema rules](https://apis.io/rules/ebanx/ebanx-jsonschema-spectral-rules/)
- [EBANX API Rules](https://apis.io/rules/ebanx/ebanx-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ebanx Authentication](https://apis.io/security/ebanx/ebanx-authentication/)
- [Ebanx Domain Security](https://apis.io/security/ebanx/ebanx-domain-security/)
- [Ebanx Trust Center](https://apis.io/security/ebanx/ebanx-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ebanx Plans Pricing](https://apis.io/plans/ebanx/ebanx-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ebanx Rate Limits](https://apis.io/rate-limits/ebanx/ebanx-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ebanx Finops](https://apis.io/finops/ebanx/ebanx-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://ebanx.com)
- [Blog](https://www.ebanx.com/en/insights/)

## API Evangelist rating

**Kin Score 34.7** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 67.6 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 13.2 |

**Agent readiness 32.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 23.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ebanx/](https://apis.io/providers/ebanx/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for EBANX: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ebanx/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
