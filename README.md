# Cyclr (cyclr)

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
