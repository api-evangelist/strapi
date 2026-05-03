# Strapi

Strapi is an open-source, headless CMS built with Node.js that gives developers full control over their content API. It provides a customizable admin panel for content management, automatically generates REST and GraphQL APIs for every content-type, and supports flexible database options including SQLite, PostgreSQL, MySQL, and MongoDB. Strapi v5 introduces a Document Service API with flattened response format, improved TypeScript support, and an enhanced content delivery API for building fast, decoupled frontends.

**Human URL:** [https://strapi.io](https://strapi.io)  
**Base URL:** `https://{host}`

## Links

- [Documentation](https://docs.strapi.io)
- [GitHub](https://github.com/strapi/strapi)
- [Blog](https://strapi.io/blog)
- [Forum](https://forum.strapi.io)
- [Discord](https://discord.strapi.io)
- [Roadmap](https://feedback.strapi.io)
- [Changelog](https://github.com/strapi/strapi/releases)
- [Pricing](https://strapi.io/pricing-cloud)

## APIs

### Strapi REST API

The Strapi REST API provides automatically generated endpoints for accessing and managing content-types. Supports full CRUD operations with filtering, sorting, pagination, and population of relational fields. Also includes the Upload plugin for media library management.

- [OpenAPI Spec](openapi/strapi-rest-api-openapi.yml)
- [Documentation](https://docs.strapi.io/cms/api/rest)

### Strapi Admin Panel API

Powers the back-office interface for managing content-types, admin accounts, roles, webhooks, and API tokens. Supports three default roles (Super Admin, Editor, Author) with granular permissions.

- [OpenAPI Spec](openapi/strapi-admin-panel-api-openapi.yml)
- [Documentation](https://docs.strapi.io/cms/features/admin-panel)

### Strapi Users and Permissions API

Full JWT-based authentication system with user registration, login, password management, social provider OAuth callbacks, and role/permission configuration for end-user access control.

- [OpenAPI Spec](openapi/strapi-users-and-permissions-api-openapi.yml)
- [Documentation](https://docs.strapi.io/cms/features/users-permissions)

### Strapi Webhooks

Event-driven webhook system notifying external services when content entries or media assets are created, updated, deleted, published, or unpublished.

- [AsyncAPI Spec](asyncapi/strapi-webhooks-asyncapi.yml)
- [Documentation](https://docs.strapi.io/cms/backend-customization/webhooks)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [strapi-rest-api-openapi.yml](openapi/strapi-rest-api-openapi.yml) | REST API for content entry CRUD and media management |
| [strapi-admin-panel-api-openapi.yml](openapi/strapi-admin-panel-api-openapi.yml) | Admin panel API for platform administration |
| [strapi-users-and-permissions-api-openapi.yml](openapi/strapi-users-and-permissions-api-openapi.yml) | Users, authentication, and permissions API |

### AsyncAPI Specifications

| File | Description |
|---|---|
| [strapi-webhooks-asyncapi.yml](asyncapi/strapi-webhooks-asyncapi.yml) | Webhook event definitions for content and media lifecycle events |

### JSON Schema

| File | Description |
|---|---|
| [strapi-content-entry-schema.json](json-schema/strapi-content-entry-schema.json) | JSON Schema for Strapi v5 content entries |

### JSON Structure

| File | Description |
|---|---|
| [strapi-content-entry-structure.json](json-structure/strapi-content-entry-structure.json) | Field structure documentation for content entries |

### JSON-LD Context

| File | Description |
|---|---|
| [strapi-context.jsonld](json-ld/strapi-context.jsonld) | JSON-LD context mapping Strapi vocabulary to linked data ontologies |

### Examples

| File | Description |
|---|---|
| [strapi-find-entries-example.json](examples/strapi-find-entries-example.json) | List content entries with pagination |
| [strapi-create-entry-example.json](examples/strapi-create-entry-example.json) | Create a new content entry |
| [strapi-admin-login-example.json](examples/strapi-admin-login-example.json) | Admin panel login and JWT token retrieval |
| [strapi-register-user-example.json](examples/strapi-register-user-example.json) | Register a new end-user account |

### Spectral Rules

| File | Description |
|---|---|
| [strapi-rules.yml](rules/strapi-rules.yml) | Spectral ruleset enforcing Strapi API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/rest-api.yaml](capabilities/shared/rest-api.yaml) | Strapi REST API — content entry and media operations |
| [capabilities/shared/admin-panel-api.yaml](capabilities/shared/admin-panel-api.yaml) | Admin Panel API — users, roles, tokens, webhooks |
| [capabilities/shared/users-permissions-api.yaml](capabilities/shared/users-permissions-api.yaml) | Users and Permissions API — auth and role management |

#### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/content-management.yaml](capabilities/content-management.yaml) | Unified content management (REST + Admin + Users, 17 tools) |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/strapi-vocabulary.yml](vocabulary/strapi-vocabulary.yml) | Strapi domain vocabulary and terminology definitions |

## Tags

- CMS
- Content Management
- Headless CMS
- Node.js
- Open Source

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
