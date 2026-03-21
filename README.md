# Strapi (strapi)
Strapi is an open-source headless CMS that provides developers with a flexible content management framework and a powerful developer platform. It offers both REST and GraphQL APIs for delivering content to any frontend, along with an extensible admin panel, user authentication, and backend customization capabilities for building tailored content workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Headless CMS, Content Management, REST, GraphQL, Open Source, API

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Strapi REST API
The Strapi REST API provides endpoints for accessing and managing content-types created within the Strapi headless CMS. When a new content-type is created in Strapi, REST API endpoints are automatically generated, supporting full CRUD operations including filtering, sorting, pagination, and population of relational fields. Developers can use these endpoints to deliver content to any frontend application, mobile app, or third-party service.

**Human URL:** [https://docs.strapi.io/cms/api/rest](https://docs.strapi.io/cms/api/rest)


#### Tags:

 - Content Management, Headless CMS, REST, CRUD, Content Delivery

#### Properties

- [Documentation](https://docs.strapi.io/cms/api/rest)
- [OpenAPI](openapi/strapi-rest-api-openapi.yml)

### Strapi GraphQL API
The Strapi GraphQL API enables developers to query and mutate content using GraphQL instead of REST. Powered by the GraphQL plugin, it automatically generates type definitions, queries, mutations, and resolvers based on the content-types defined in Strapi through a Shadow CRUD feature. The API includes an interactive GraphQL playground for building and testing queries, and supports custom resolvers, policies, and middlewares for extending the generated schema.

**Human URL:** [https://docs.strapi.io/cms/api/graphql](https://docs.strapi.io/cms/api/graphql)


#### Tags:

 - Content Management, Headless CMS, GraphQL, Content Delivery, Query Language

#### Properties

- [Documentation](https://docs.strapi.io/cms/api/graphql)

### Strapi Users and Permissions API
The Strapi Users and Permissions API provides a full authentication process based on JSON Web Tokens (JWT) to protect API endpoints, along with an access-control list (ACL) strategy for managing permissions between groups of users. It supports user registration, login, password reset, and email confirmation workflows. End users and their account information are managed as a content-type, and the API enables configuration of roles and permissions to control which API endpoints are accessible to authenticated and public users.

**Human URL:** [https://docs.strapi.io/cms/features/users-permissions](https://docs.strapi.io/cms/features/users-permissions)


#### Tags:

 - Authentication, Authorization, Users, JWT, Access Control

#### Properties

- [Documentation](https://docs.strapi.io/cms/features/users-permissions)
- [OpenAPI](openapi/strapi-users-and-permissions-api-openapi.yml)

### Strapi Admin Panel API
The Strapi Admin Panel API powers the back-office interface used to manage content-types, content entries, media assets, and administrator accounts. It provides endpoints for the Content-Type Builder, Content Manager, Media Library, and role-based access control configuration. The API supports three default administrator roles (Super Admin, Editor, and Author) with granular permission management, allowing organizations to control which administrative functions each role can access.

**Human URL:** [https://docs.strapi.io/cms/features/admin-panel](https://docs.strapi.io/cms/features/admin-panel)


#### Tags:

 - Administration, Content Management, Role-Based Access Control, Headless CMS

#### Properties

- [Documentation](https://docs.strapi.io/cms/features/admin-panel)
- [OpenAPI](openapi/strapi-admin-panel-api-openapi.yml)

### Strapi Backend Customization API
The Strapi Backend Customization API allows developers to extend and customize the default behavior of Strapi's core backend. It provides programmatic interfaces for creating custom controllers, services, routes, policies, and middlewares. Developers can use this API to add custom business logic, integrate with third-party services, modify request and response handling, and build custom plugins that extend Strapi's functionality beyond the default content management features.

**Human URL:** [https://docs.strapi.io/cms/backend-customization](https://docs.strapi.io/cms/backend-customization)


#### Tags:

 - Customization, Middleware, Plugins, Controllers, Services

#### Properties

- [Documentation](https://docs.strapi.io/cms/backend-customization)

## Common Properties

- [Portal](https://docs.strapi.io/dev-docs/intro)
- [Documentation](https://docs.strapi.io/)
- [Website](https://strapi.io/)
- [PrivacyPolicy](https://strapi.io/privacy)
- [TermsOfService](https://strapi.io/terms)
- [Blog](https://strapi.io/blog)
- [Login](https://cloud.strapi.io/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
