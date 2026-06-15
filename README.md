# Strapi (strapi)

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
