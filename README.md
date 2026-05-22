# Prismatic (prismatic)

The integration platform for B2B SaaS teams. Prismatic empowers everyone on your team with integration tools for devs and non-devs alike, combining a code-native TypeScript SDK with a low-code designer and an embedded marketplace for shipping customer-facing integrations.

**APIs.yml:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Embedded iPaaS
- Integrations
- Workflows
- Connectors
- AI Agents
- MCP
- Code-Native
- Low-Code

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-22

## APIs

### Prismatics GraphQL API

Prismatic provides a GraphQL-based API for you to build, deploy, and support your integrations programmatically. While Prismatic recommends that new users use the web app or Prismatic CLI tool (prism) to manage Prismatic resources, developer users will likely want to use the API to script integration management, embed in CI/CD pipelines, and drive multi-tenant deployments.

**Human URL:** [https://prismatic.io/docs/api/](https://prismatic.io/docs/api/)

#### Tags

- Connectors
- Embedded SaaS
- Embedded SaaS Integration
- Integrations
- Workflows
- GraphQL
- Management API

#### Specifications & Rules

- [OpenAPI](openapi/prismatic-graphql-api-openapi.yml)
- [Documentation](https://prismatic.io/docs/api/)
- [Authentication](https://prismatic.io/docs/api/authentication/)
- [Pagination](https://prismatic.io/docs/api/pagination/)
- [GraphiQL Explorer](https://prismatic.io/docs/explorer/)
- [Spectral Rules](rules/prismatic-graphql-api-rules.yml)
- [Vocabulary](vocabulary/prismatic-vocabulary.yml)
- [JSON-LD Context](json-ld/prismatic-context.jsonld)

#### JSON Schemas

- [Customer](json-schema/customer.json)
- [Integration](json-schema/integration.json)
- [Instance](json-schema/instance.json)
- [Component](json-schema/component.json)
- [Flow](json-schema/flow.json)
- [Config Variable](json-schema/config-variable.json)
- [User](json-schema/user.json)
- [Alert Monitor](json-schema/alert-monitor.json)
- [Execution](json-schema/execution.json)

#### JSON Structures

- [Customer](json-structure/customer.json)
- [Integration](json-structure/integration.json)
- [Instance](json-structure/instance.json)
- [Component](json-structure/component.json)
- [Flow](json-structure/flow.json)

#### Examples

- [List Customers](examples/list-customers-example.json)
- [List Integrations](examples/list-integrations-example.json)
- [List Components](examples/list-components-example.json)
- [List Instances](examples/list-instances-example.json)
- [Create Customer](examples/create-customer-example.json)
- [Refresh Auth Token](examples/refresh-token-example.json)

#### Naftiko Capabilities

- [GraphQL Authentication](capabilities/graphql-authentication.yaml)
- [GraphQL Operation](capabilities/graphql-graphql.yaml)

## SDKs, CLI, IDE & MCP

- [Prism CLI Documentation](https://prismatic.io/docs/cli/)
- [`@prismatic-io/prism` (npm)](https://www.npmjs.com/package/@prismatic-io/prism) — CLI
- [`@prismatic-io/spectral` (npm)](https://www.npmjs.com/package/@prismatic-io/spectral) — TypeScript SDK for components and code-native integrations
- [`@prismatic-io/embedded` (npm)](https://www.npmjs.com/package/@prismatic-io/embedded) — Embed marketplace & workflow builder
- [Spectral on GitHub](https://github.com/prismatic-io/spectral)
- [Embedded SDK on GitHub](https://github.com/prismatic-io/embedded)
- [VSCode / Cursor Extension](https://github.com/prismatic-io/vscode)
- [Terraform Provider](https://github.com/prismatic-io/terraform-provider-prismatic)
- [Custom Connectors Overview](https://prismatic.io/docs/custom-connectors/)

## AI Agent Surfaces

- [Prism MCP Server](https://github.com/prismatic-io/prism-mcp) — Local Model Context Protocol server exposing Prismatic dev tools to AI coding agents.
- [Prismatic Skills for Claude Code](https://github.com/prismatic-io/prismatic-skills) — Open-source Claude Code plugin bundling 7 specialized agent skills (component-builder, cni-builder, external-api-researcher, embedded-advisor, migration-analyzer, migration-reviewer, orby).
- [AI Copilot for Embedded Workflow Builder](https://prismatic.io/docs/changelog/) — Natural-language assistant inside the customer-facing workflow builder.

## Operations & CI/CD

- [Prismatic API in CI/CD](https://prismatic.io/docs/api/ci-cd-system/)
- [GitHub Actions](https://prismatic.io/docs/api/github-actions/)
- [Changelog](https://prismatic.io/docs/changelog/)
- [Status Page](https://www.prismatic-status.io/)
- [Status RSS Feed](https://www.prismatic-status.io/history.rss)
- [Status Atom Feed](https://www.prismatic-status.io/history.atom)
- [Blog](https://prismatic.io/blog/)

## Commercial

- [Pricing Page](https://prismatic.io/pricing/) — Quote-based; Scale, Enterprise, and Custom tiers.
- [Plans (API Commons)](plans/prismatic-plans-pricing.yml)
- [Rate Limits](rate-limits/prismatic-rate-limits.yml)
- [FinOps Mapping](finops/prismatic-finops.yml)

## Legal

- [Privacy Policy](https://prismatic.io/legal/privacy/)
- [Terms of Use](https://prismatic.io/legal/terms/)
- [Security Policy](https://prismatic.io/legal/security/)

## Organization

- [GitHub Organization](https://github.com/prismatic-io)
- [LinkedIn](https://www.linkedin.com/company/prismatic-io)
- [Connectors Catalog](https://prismatic.io/connectors/)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
