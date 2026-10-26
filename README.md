# Kestra (kestra)

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

Kestra is a declarative workflow orchestration platform where pipelines are defined in YAML, combining visual and code-first approaches.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kestra/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kestra/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automation
- Data Pipelines
- Event-Driven
- Orchestration
- Workflows

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-04-28

## APIs

### Kestra Flows API

The Kestra Flows API provides programmatic access to manage workflow definitions in the Kestra orchestration platform. It enables creating, updating, retrieving, and deleting flows defined in YAML, supporting the full lifecycle of workflow management via REST endpoints.

- **Human URL:** [https://kestra.io/docs/api-reference](https://kestra.io/docs/api-reference)

#### Tags

- Flows
- Orchestration
- Workflows

#### Properties

- [Documentation](https://kestra.io/docs/api-reference)
- [OpenAPI](https://kestra.io/docs/api-reference/open-source) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kestra Executions API

The Kestra Executions API allows triggering workflow executions, monitoring their state, retrieving execution details including task run outputs and state transitions, and managing the lifecycle of running workflows programmatically.

- **Human URL:** [https://kestra.io/docs/api-reference](https://kestra.io/docs/api-reference)

#### Tags

- Executions
- Orchestration
- Workflows

#### Properties

- [Documentation](https://kestra.io/docs/api-reference)
- [OpenAPI](https://kestra.io/docs/api-reference/open-source) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kestra Namespaces API

The Kestra Namespaces API provides endpoints for managing namespaces, which serve as logical groupings for organizing flows, files, secrets, and key-value pairs within the Kestra platform.

- **Human URL:** [https://kestra.io/docs/api-reference](https://kestra.io/docs/api-reference)

#### Tags

- Namespaces
- Orchestration
- Organization

#### Properties

- [Documentation](https://kestra.io/docs/api-reference)
- [OpenAPI](https://kestra.io/docs/api-reference/open-source) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kestra Key-Value Store API

The Kestra Key-Value Store API enables storing and retrieving key-value pairs within namespaces, providing a simple data persistence mechanism for workflows to share state and configuration across executions.

- **Human URL:** [https://kestra.io/docs/how-to-guides/api](https://kestra.io/docs/how-to-guides/api)

#### Tags

- Key-Value Store
- State Management
- Storage

#### Properties

- [Documentation](https://kestra.io/docs/how-to-guides/api)
- [OpenAPI](https://kestra.io/docs/api-reference/open-source) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kestra Namespace Files API

The Kestra Namespace Files API provides endpoints for listing, uploading, and downloading files within namespaces, enabling file management for workflows that need to work with scripts, configurations, or other file-based resources.

- **Human URL:** [https://kestra.io/docs/how-to-guides/api](https://kestra.io/docs/how-to-guides/api)

#### Tags

- Files
- Namespaces
- Storage

#### Properties

- [Documentation](https://kestra.io/docs/how-to-guides/api)
- [OpenAPI](https://kestra.io/docs/api-reference/open-source) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kestra Enterprise API

The Kestra Enterprise API extends the open-source API with additional endpoints for enterprise features including authentication, RBAC, audit logging, multi-tenancy, SSO, and advanced governance capabilities for production deployments.

- **Human URL:** [https://kestra.io/docs/api-reference/enterprise](https://kestra.io/docs/api-reference/enterprise)

#### Tags

- Authentication
- Enterprise
- Governance
- RBAC

#### Properties

- [Documentation](https://kestra.io/docs/api-reference/enterprise)
- [Authentication](https://kestra.io/docs/enterprise/auth/api)
- [Postman Collection](collections/kestra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kestra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/kestra)
- [Portal](https://kestra.io/)
- [Documentation](https://kestra.io/docs)
- [Getting Started](https://kestra.io/docs/quickstart)
- [Tutorials](https://kestra.io/docs/tutorial)
- [API Reference](https://kestra.io/docs/api-reference)
- [API Reference](https://kestra.io/docs/api-reference/open-source)
- [Authentication](https://kestra.io/docs/enterprise/auth/api)
- [S D Ks](https://kestra.io/docs/api-reference/kestra-sdk)
- [Blog](https://kestra.io/blogs)
- [Changelog](https://kestra.io/docs/changelog)
- [Pricing](https://kestra.io/pricing)
- [Support](https://support.kestra.io/hc/en-us)
- [Community](https://kestra.io/community)
- [F A Q](https://kestra.io/faq)
- [GitHub Organization](https://github.com/kestra-io)
- [GitHub Repository](https://github.com/kestra-io/kestra)
- [Integrations](https://kestra.io/plugins/)
- [Terraform](https://kestra.io/docs/terraform)
- [Privacy Policy](https://kestra.io/privacy-policy)
- [Terms of Service](https://kestra.io/terms-and-services)
- [Contact](https://kestra.io/contact-us)
- [Features](https://kestra.io/features/api-first)
- [L L Ms Txt](https://kestra.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
