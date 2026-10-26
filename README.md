# Prismatic (prismatic)

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

The integration platform for B2B SaaS teams. Prismatic empowers everyone on your team with integration tools for devs and non-devs alike, combining a code-native TypeScript SDK with a low-code designer and an embedded marketplace for shipping customer-facing integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/apis.yml)

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

- **Human URL:** [https://prismatic.io/docs/api/](https://prismatic.io/docs/api/)

#### Tags

- Connectors
- Embedded SaaS
- Embedded SaaS Integration
- Integrations
- Workflows
- GraphQL
- Management API

#### Properties

- [OpenAPI](openapi/prismatic-graphql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prismatic-graphql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prismatic-graphql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://prismatic.io/docs/api/)
- [Authentication](https://prismatic.io/docs/api/authentication/)
- [Pagination](https://prismatic.io/docs/api/pagination/)
- [Explorer](https://prismatic.io/docs/explorer/)
- [Spectral Rules](rules/prismatic-graphql-api-rules.yml)
- [Vocabulary](vocabulary/prismatic-vocabulary.yml)
- [JSON-LD](json-ld/prismatic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/integration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instance.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/component.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flow.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/config-variable.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alert-monitor.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/execution.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/customer.json)
- [JSON Structure](json-structure/integration.json)
- [JSON Structure](json-structure/instance.json)
- [JSON Structure](json-structure/component.json)
- [JSON Structure](json-structure/flow.json)
- [Example](examples/list-customers-example.json)
- [Example](examples/list-integrations-example.json)
- [Example](examples/list-components-example.json)
- [Example](examples/list-instances-example.json)
- [Example](examples/create-customer-example.json)
- [Example](examples/refresh-token-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://prismatic.io)
- [Documentation](https://prismatic.io/docs/)
- [Getting Started](https://prismatic.io/docs/integrations/low-code-integration-designer/get-started/first-integration/)
- [C L I](https://prismatic.io/docs/cli/)
- [C L I](https://www.npmjs.com/package/@prismatic-io/prism)
- [SDK](https://www.npmjs.com/package/@prismatic-io/spectral)
- [SDK](https://www.npmjs.com/package/@prismatic-io/embedded)
- [S D Ks](https://prismatic.io/docs/custom-connectors/)
- [SDK](https://github.com/prismatic-io/spectral)
- [SDK](https://github.com/prismatic-io/embedded)
- [I D E](https://github.com/prismatic-io/vscode)
- [Terraform](https://github.com/prismatic-io/terraform-provider-prismatic)
- [M C P](https://github.com/prismatic-io/prism-mcp)
- [Agent Skill](https://github.com/prismatic-io/prismatic-skills)
- [C I/ C D](https://prismatic.io/docs/api/ci-cd-system/)
- [Git Hub Actions](https://prismatic.io/docs/api/github-actions/)
- [Changelog](https://prismatic.io/docs/changelog/)
- [Status Page](https://www.prismatic-status.io/)
- [R S S](https://www.prismatic-status.io/history.rss)
- [Atom](https://www.prismatic-status.io/history.atom)
- [Blog](https://prismatic.io/blog/)
- [Pricing](https://prismatic.io/pricing/)
- [Plans](plans/prismatic-plans-pricing.yml)
- [Rate Limits](rate-limits/prismatic-rate-limits.yml)
- [Fin Ops](finops/prismatic-finops.yml)
- [Privacy Policy](https://prismatic.io/legal/privacy/)
- [Terms of Service](https://prismatic.io/legal/terms/)
- [Security](https://prismatic.io/legal/security/)
- [GitHub Organization](https://github.com/prismatic-io)
- [LinkedIn](https://www.linkedin.com/company/prismatic-io)
- [Integrations](https://prismatic.io/connectors/)
- [Features](undefined)
- [Benefits](undefined)
- [Agent Skill](https://github.com/prismatic-io/prismatic-skills)
- [M C P](https://github.com/prismatic-io/prism-mcp)
- [A I Agent](undefined)
- [L L Ms Txt](https://prismatic.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
