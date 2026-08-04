# Edlink (edlink)

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
