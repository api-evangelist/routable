# Routable (routable)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Routable is a B2B payments platform automating accounts payable and accounts receivable, mass payouts, and vendor management. Its API-first REST API lets teams onboard vendors and customers, collect payment and tax information, create payables and receivables, and move money via ACH, SWIFT, and check to more than 200 countries, with webhook events for end-to-end automation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/routable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/routable/refs/heads/main/apis.yml)

## Tags

- Payments
- Accounts Payable
- Accounts Receivable
- B2B Payments
- Mass Payouts
- FinTech

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Routable Vendors API

Create, list, update, archive, and invite vendor companies, manage their contacts and payment methods, and collect tax and compliance information before paying them.

- **Human URL:** [https://developers.routable.com/reference/introduction](https://developers.routable.com/reference/introduction)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Vendors
- Companies
- Onboarding

#### Properties

- [Documentation](https://developers.routable.com/docs/companies-1)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Customers API

Manage customer companies and their contacts that you bill through receivables, using the same Companies resource that represents both vendors and customers.

- **Human URL:** [https://developers.routable.com/reference/introduction](https://developers.routable.com/reference/introduction)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Customers
- Companies
- Onboarding

#### Properties

- [Documentation](https://developers.routable.com/docs/companies-1)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Payables API

Create, list, update, and cancel payables (bills owed to vendors), estimate fees, send reminders, and download confirmation PDFs to automate the accounts payable workflow.

- **Human URL:** [https://developers.routable.com/docs/payables-1](https://developers.routable.com/docs/payables-1)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Payables
- Accounts Payable
- Bills

#### Properties

- [Documentation](https://developers.routable.com/docs/payables-1)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Receivables API

Create, list, update, and cancel receivables (amounts owed to you by customers) and send reminders to automate the accounts receivable workflow.

- **Human URL:** [https://developers.routable.com/docs/receivables-1](https://developers.routable.com/docs/receivables-1)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Receivables
- Accounts Receivable
- Invoices

#### Properties

- [Documentation](https://developers.routable.com/docs/receivables-1)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Payments API

Create, validate, and manage payment methods (bank, international, and check) and estimate currency conversions and fees for payments to vendors in more than 200 countries via ACH, SWIFT, and check.

- **Human URL:** [https://developers.routable.com/docs/payment-methods-1](https://developers.routable.com/docs/payment-methods-1)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Payments
- ACH
- SWIFT
- Check
- Mass Payouts

#### Properties

- [Documentation](https://developers.routable.com/docs/payment-methods-1)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Funding Sources API

List and retrieve your organization's funding accounts, retrieve the Routable Balance account, and deposit funds into the balance to source payments.

- **Human URL:** [https://developers.routable.com/docs/collecting-payment-information](https://developers.routable.com/docs/collecting-payment-information)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Funding Sources
- Accounts
- Balance

#### Properties

- [Documentation](https://developers.routable.com/docs/collecting-payment-information)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routable Webhooks API

List and retrieve webhook events emitted by Routable and retry failed deliveries to keep external systems synchronized with payment lifecycle changes.

- **Human URL:** [https://developers.routable.com/docs/webhooks](https://developers.routable.com/docs/webhooks)
- **Base URL:** `https://api.routable.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.routable.com/docs/webhooks)
- [API Reference](https://developers.routable.com/reference/introduction)
- [OpenAPI](openapi/routable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/routable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/routable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/routablehq)
- [LinkedIn](https://www.linkedin.com/company/routable)
- [Website](https://www.routable.com/)
- [Documentation](https://developers.routable.com/docs)
- [Plans](plans/routable-plans-pricing.yml)
- [Rate Limits](rate-limits/routable-rate-limits.yml)
- [Fin Ops](finops/routable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
