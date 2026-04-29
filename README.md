# Cyclr (cyclr)

Cyclr is an embedded iPaaS used by SaaS vendors to deliver native integrations to their customers without each vendor building and maintaining one-off connectors. The platform provides a connector library covering hundreds of business applications (CRM, marketing, finance, support, ERP, e-commerce), drag-and-drop integration templates, embedded LAUNCH and Marketplace UIs, custom connector creation, fully managed authentication, and workflow orchestration. Cyclr exposes a public REST API at `api.cyclr.com` (with regional siblings) protected by OAuth 2.0 client credentials.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Connectors, Custom Connectors, Data Synchronization, Embedded iPaaS, Embedded SaaS Integration, Embedded UI, Integration Platform, Integrations, Marketplace, OAuth 2.0, REST API, SaaS, Templates, Webhooks, White Label, Workflows

## Timestamps

- **Created:** 2025-06-06
- **Modified:** 2026-04-28

## APIs

### Cyclr API

REST API for managing accounts, installing connectors and templates, building and configuring integration cycles, and embedding LAUNCH and Marketplace UIs. OAuth 2.0 client credentials; account-scoped operations include the `X-Cyclr-Account` HTTP header.

- **Human URL:** https://cyclr.com
- **Base URL:** `https://api.cyclr.com/v1.0`
- **OpenAPI:** [openapi/cyclr-cyclr-openapi.yml](openapi/cyclr-cyclr-openapi.yml)
- **AsyncAPI:** [asyncapi/cyclr-cyclr-asyncapi.yml](asyncapi/cyclr-cyclr-asyncapi.yml)
- **Capabilities:** [capabilities/cyclr-api-capabilities.yml](capabilities/cyclr-api-capabilities.yml)
- **Rules:** [rules/cyclr-api-rules.yml](rules/cyclr-api-rules.yml)

## Capabilities

- Partner-level account creation and authorization
- Connector installation and OAuth-managed authentication
- Template browsing and installation as runnable cycles
- Cycle, step, parameter, and field-mapping configuration
- Data on Demand proxy calls to authenticated connector methods
- Embedded LAUNCH and Marketplace UIs in host SaaS products
- Custom connector creation
- Webhook-driven and event-driven integration flows

## Use Cases

- SaaS vendors offering native integrations to customers without building each one
- White-labeled integration marketplaces inside the host product
- Application interconnect and bidirectional data sync
- Workflow automation across CRM, marketing, finance, and support
- Standardizing integrations across customer accounts
- API-driven Data on Demand for runtime data lookups

## Common Resources

- [Cyclr Website](https://cyclr.com/)
- [Connectors](https://cyclr.com/connectors)
- [Pricing](https://cyclr.com/product/pricing)
- [Webinars](https://cyclr.com/resources/webinars)
- [Blog](https://cyclr.com/blog)
- [Security and Compliance](https://cyclr.com/security-and-compliance)
- [Release Notes](https://community.cyclr.com/user-documentation/release-notes/introduction-to-release-notes)
- [JSON-LD Context](json-ld/cyclr-context.jsonld)
- [Account Schema](json-schema/cyclr-account.json)
- [Connector Schema](json-schema/cyclr-connector.json)
- [Cycle Schema](json-schema/cyclr-cycle.json)
- [Step Schema](json-schema/cyclr-step.json)
- [Template Schema](json-schema/cyclr-template.json)
- [Vocabulary](vocabulary/cyclr-vocabulary.yml)
- [Capabilities](capabilities/cyclr-api-capabilities.yml)
- [Rules](rules/cyclr-api-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
