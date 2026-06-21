# Edlink (edlink)

Edlink is an education-integration platform offering a unified API for rostering and school data across SIS and LMS systems. The Edlink Graph API exposes normalized districts, schools, classes, sections, courses, people, and enrollments from hundreds of source systems behind a single Bearer-authenticated REST interface, plus SSO, source integrations, and change events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/edlink/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/edlink/refs/heads/main/apis.yml)

## Tags

- Education
- EdTech
- Rostering
- SIS
- LMS
- Integration
- Unified API

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Graph API - Users, Classes, Enrollments

Institution-level access to normalized people, classes, and enrollments via the Graph API using an Integration Access Token, ideal for bulk roster sync across SIS and LMS sources.

- **Human URL:** [https://ed.link/docs/api](https://ed.link/docs/api)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- Rostering
- People
- Classes
- Enrollments

#### Properties

- [Documentation](https://ed.link/docs/api)
- [API Reference](https://ed.link/docs/guides/v2.0/getting-started/graph-user-meta-apis)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Graph API - Schools, Districts

Organizational hierarchy of districts and schools shared with an integration, including locale, time zone, grade levels, and location metadata.

- **Human URL:** [https://ed.link/docs/api](https://ed.link/docs/api)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- Schools
- Districts
- Organizations

#### Properties

- [Documentation](https://ed.link/docs/api)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Graph API - Courses, Sections

Course catalog and the sections that subdivide classes, with codes, subjects, grade levels, sessions, and class relationships.

- **Human URL:** [https://ed.link/docs/api](https://ed.link/docs/api)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- Courses
- Sections
- Catalog

#### Properties

- [Documentation](https://ed.link/docs/api)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SSO

Single Sign-On via OAuth 2.0 and OpenID Connect, letting teachers and students authenticate into a learning platform through their source identity provider and returning a User Access Token.

- **Human URL:** [https://ed.link/docs/guides/v2.0/sso/overview](https://ed.link/docs/guides/v2.0/sso/overview)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- SSO
- OAuth2
- OIDC
- Authentication

#### Properties

- [Documentation](https://ed.link/docs/guides/v2.0/sso/overview)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sources, Integrations

Integration and source metadata describing each connected district data source (SIS/LMS), its provider, status, and sharing configuration, accessible via the Graph and Meta APIs.

- **Human URL:** [https://ed.link/docs/api](https://ed.link/docs/api)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- Sources
- Integrations
- Connections

#### Properties

- [Documentation](https://ed.link/docs/api)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Events, Webhooks

Change events stream describing creates, updates, and deletes to roster objects so integrations can incrementally sync rather than re-fetching the full graph.

- **Human URL:** [https://ed.link/docs/api](https://ed.link/docs/api)
- **Base URL:** `https://ed.link/api/v2`

#### Tags

- Events
- Webhooks
- Change Data

#### Properties

- [Documentation](https://ed.link/docs/api)
- [OpenAPI](openapi/edlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/edlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/edlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/edlink)
- [LinkedIn](https://www.linkedin.com/company/edlink-inc)
- [Website](https://ed.link/)
- [Documentation](https://ed.link/docs)
- [Plans](plans/edlink-plans-pricing.yml)
- [Rate Limits](rate-limits/edlink-rate-limits.yml)
- [Fin Ops](finops/edlink-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
