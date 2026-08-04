# Cyclr (cyclr)

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

Cyclr is an embedded iPaaS (integration platform as a service) used by SaaS vendors to deliver native integrations to their customers without each vendor building and maintaining one-off connectors. The platform provides a connector library covering hundreds of business applications (CRM, marketing, finance, support, ERP, e-commerce), drag-and-drop integration templates, embedded LAUNCH and Marketplace UIs, custom connector creation, fully managed authentication, and workflow orchestration. Cyclr exposes a public REST API at api.cyclr.com (with regional EU / AU / UK / US2 siblings) protected by OAuth 2.0 client credentials. Account-scoped calls require an X-Cyclr-Account header to identify the target Cyclr account.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Connectors
- Custom Connectors
- Data Synchronization
- Embedded iPaaS
- Embedded SaaS Integration
- Embedded UI
- Integration Platform
- Integrations
- Marketplace
- OAuth 2.0
- REST API
- SaaS
- Templates
- Webhooks
- White Label
- Workflows

## Timestamps

- **Created:** 2025-06-06
- **Modified:** 2026-05-19

## APIs

### Cyclr API

Cyclr's REST API allows partners to manage their accounts, install and authenticate connectors, install templates as cycles, build and configure cycle steps, and embed LAUNCH and Marketplace UIs into their host SaaS product. Authentication uses OAuth 2.0 client credentials issued in the Cyclr Console; account-scoped operations include the X-Cyclr-Account HTTP header.

- **Human URL:** [https://cyclr.com](https://cyclr.com)
- **Base URL:** `https://api.cyclr.com/v1.0`

#### Tags

- Accounts
- Connectors
- Cycles
- Embedded UI
- OAuth 2.0
- REST
- Steps
- Templates

#### Properties

- [Documentation](https://cyclr.com)
- [A P I Documentation](https://docs.cyclr.com/api/)
- [API Reference](https://api.cyclr.com/docs/index)
- [OpenAPI](openapi/cyclr-cyclr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cyclr-cyclr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cyclr-cyclr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/cyclr-cyclr-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/cyclr-account.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cyclr-connector.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cyclr-installed-connector.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cyclr-template.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cyclr-cycle.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cyclr-step.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cyclr-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Capabilities](capabilities/cyclr-api-capabilities.yml)
- [Rules](rules/cyclr-api-rules.yml)

## Common Properties

- [GitHub Organization](https://github.com/cyclr)
- [LinkedIn](https://www.linkedin.com/company/cyclr-systems-ltd)
- [Website](https://cyclr.com/)
- [Connectors](https://cyclr.com/connectors)
- [Pricing](https://cyclr.com/product/pricing)
- [Case Studies](https://cyclr.com/case-studies)
- [Webinars](https://cyclr.com/resources/webinars)
- [Blog](https://cyclr.com/blog)
- [Branding](https://cyclr.com/brand)
- [Partners](https://cyclr.com/become-a-partner)
- [Security](https://cyclr.com/security-and-compliance)
- [G D P R](https://cyclr.com/legal/gdpr-compliance)
- [S L A](https://cyclr.com/sla)
- [Changelog](https://community.cyclr.com/user-documentation/release-notes/introduction-to-release-notes)
- [Login](https://my.cyclr.com/account/login)
- [Get Started](https://cyclr.com/get-started)
- [Vocabulary](vocabulary/cyclr-vocabulary.yml)
- [Capabilities](capabilities/cyclr-api-capabilities.yml)
- [Rules](rules/cyclr-api-rules.yml)
- [Integrations](https://cyclr.com/connectors)
- [L L Ms Txt](https://cyclr.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
