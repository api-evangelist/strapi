# Strapi (strapi)

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

Strapi is an open-source, headless CMS built with Node.js that gives developers full control over their content API. It provides a customizable admin panel for content management, automatically generates REST and GraphQL APIs for every content-type, and supports flexible database options including SQLite, PostgreSQL, MySQL, and MongoDB. Strapi v5 introduces a Document Service API with flattened response format, improved TypeScript support, and an enhanced content delivery API for building fast, decoupled frontends.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS
- Content Management
- Headless CMS
- Node.js
- Open Source

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Strapi REST API

The Strapi REST API provides automatically generated endpoints for accessing and managing content-types created within the Strapi headless CMS. Supports full CRUD operations with filtering, sorting, pagination, population of relational fields, and internationalization. Content-types are private by default and require authenticated requests or configured public permissions. The API also includes a media library Upload plugin for file management.

- **Human URL:** [https://docs.strapi.io/cms/api/rest](https://docs.strapi.io/cms/api/rest)
- **Base URL:** `https://{host}`

#### Tags

- CMS
- Content Management
- REST API
- Headless CMS

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.strapi.io/cms/api/rest)
- [Documentation](https://docs.strapi.io/cms/api/rest/parameters)
- [Postman Collection](collections/strapi-admin-panel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-admin-panel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-users-and-permissions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-users-and-permissions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Strapi Admin Panel API

The Strapi Admin Panel API powers the back-office interface for managing content-types, content entries, media assets, and administrator accounts. Provides endpoints for the Content-Type Builder, Content Manager, Media Library, and role-based access control configuration. Supports three default roles (Super Admin, Editor, Author) and includes management of API tokens, transfer tokens, and webhooks.

- **Human URL:** [https://docs.strapi.io/cms/features/admin-panel](https://docs.strapi.io/cms/features/admin-panel)
- **Base URL:** `https://{host}`

#### Tags

- Admin
- CMS
- Content Management
- RBAC

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.strapi.io/cms/features/admin-panel)
- [Documentation](https://docs.strapi.io/cms/features/rbac)
- [Postman Collection](collections/strapi-admin-panel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-admin-panel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-users-and-permissions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-users-and-permissions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Strapi Users and Permissions API

The Strapi Users and Permissions API provides a full JWT-based authentication system for protecting API endpoints, along with an access-control list strategy for managing permissions between user groups. Supports user registration, login, password reset, email confirmation, and social provider authentication via OAuth. The API enables configuration of roles and permissions to control endpoint accessibility.

- **Human URL:** [https://docs.strapi.io/cms/features/users-permissions](https://docs.strapi.io/cms/features/users-permissions)
- **Base URL:** `https://{host}`

#### Tags

- Authentication
- CMS
- Permissions
- User Management

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.strapi.io/cms/features/users-permissions)
- [Postman Collection](collections/strapi-admin-panel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-admin-panel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-users-and-permissions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-users-and-permissions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Strapi Webhooks

Strapi includes a built-in webhook system that notifies external services whenever content entries or media assets are created, updated, deleted, published, or unpublished. Webhooks are configured through the admin panel and include a custom X-Strapi-Event header identifying the event type.

- **Human URL:** [https://docs.strapi.io/cms/backend-customization/webhooks](https://docs.strapi.io/cms/backend-customization/webhooks)

#### Tags

- CMS
- Events
- Webhooks

#### Properties

- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Documentation](https://docs.strapi.io/cms/backend-customization/webhooks)
- [Postman Collection](collections/strapi-admin-panel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-admin-panel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/strapi-users-and-permissions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/strapi-users-and-permissions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/strapi)
- [Website](https://strapi.io)
- [Documentation](https://docs.strapi.io)
- [Git Hub](https://github.com/strapi/strapi)
- [Blog](https://strapi.io/blog)
- [Forum](https://forum.strapi.io)
- [Discord](https://discord.strapi.io)
- [Roadmap](https://feedback.strapi.io)
- [Changelog](https://github.com/strapi/strapi/releases)
- [Pricing](https://strapi.io/pricing-cloud)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-schema/strapi-content-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-ld/strapi-context.jsonld)
- [Integrations](https://strapi.io/integrations)
- [L L Ms Txt](https://docs.strapi.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
