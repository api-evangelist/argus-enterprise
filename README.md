# ARGUS Enterprise (argus-enterprise)

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

ARGUS Enterprise is the industry-standard commercial property valuation and cash flow forecasting software by Altus Group, now integrated into the ARGUS Intelligence Platform. It provides lease-by-lease cash flow modeling, property valuations using DCF and yield-based methods, budgeting and forecasting, scenario testing, and 40+ industry-standard reports. Trusted by real estate investors, portfolio managers, valuation professionals, and asset managers worldwide and taught at 200+ universities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Altus Group
- Asset Management
- Cash Flow Modeling
- Commercial Real Estate
- Portfolio Management
- Valuation

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### ARGUS Enterprise Core API

Core REST API for the ARGUS Enterprise platform providing programmatic access to commercial real estate investment management capabilities including property data, portfolio management, cash flow projections, valuations, tenants, leases, and reporting. Authentication via bearer token.

- **Human URL:** [https://www.altusgroup.com/solutions/argus-enterprise/](https://www.altusgroup.com/solutions/argus-enterprise/)
- **Base URL:** `https://api.argusenterprise.com/v1`

#### Tags

- Analytics
- Cash Flow
- Leases
- Portfolio Management
- Properties
- Reporting
- Valuations

#### Properties

- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [OpenAPI](openapi/argus-enterprise-core-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argus-enterprise-core.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argus-enterprise-core.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.altusgroup.com/support/start-using-argus-intelligence/)

### ARGUS Enterprise Webhook API

Webhook service for the ARGUS Enterprise platform enabling real-time event notifications for property changes, valuation updates, lease events, portfolio modifications, and report completions.

- **Human URL:** [https://www.altusgroup.com/solutions/argus-enterprise/](https://www.altusgroup.com/solutions/argus-enterprise/)

#### Tags

- Events
- Real-Time
- Webhooks

#### Properties

- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [OpenAPI](openapi/argus-enterprise-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argus-enterprise-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argus-enterprise-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.altusgroup.com/solutions/argus-enterprise/)
- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [Getting Started](https://www.altusgroup.com/support/start-using-argus-intelligence/)
- [Portal](https://cloud.altusplatform.com/login)
- [Support](https://www.altusgroup.com/support/)
- [Terms of Service](https://www.altusgroup.com/terms-of-use/)
- [Privacy Policy](https://www.altusgroup.com/privacy-policy/)
- [Training](https://www.altusgroup.com/argus/training/)
- [Security](https://www.altusgroup.com/security/)
- [JSON-LD](json-ld/argus-enterprise-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/argus-enterprise-spectral-rules.yml)
- [Vocabulary](vocabulary/argus-enterprise-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
