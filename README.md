# Microsoft SharePoint (sharepoint)

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

Microsoft SharePoint is a web-based collaborative platform providing enterprise content management, document management, and collaboration capabilities with comprehensive REST and Graph APIs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Collaboration, Document Management, Enterprise Content Management, Intranet, Microsoft

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-17

## APIs

4 APIs: SharePoint REST API, Microsoft Graph API (SharePoint), SharePoint CSOM, SharePoint Webhooks API.

## Features

| Name | Description |
|------|-------------|
| Sites and Webs | Create, read, update, and delete SharePoint sites and subsites. |
| Lists and Libraries | Full CRUD operations on lists, document libraries, and list items. |
| Document Management | Upload, download, check in/out, and manage documents and versions. |
| Folders and Files | Create folder hierarchies and manage files within libraries. |
| Permissions and Security | Manage site, list, and item-level permissions. |
| Search | Full-text search across sites, documents, and content. |
| User Profiles | Access user profile properties and organizational data. |
| Content Types | Manage content types, site columns, and metadata schemas. |
| Webhooks | Subscribe to change notifications for lists and libraries. |
| Microsoft Graph Integration | Access SharePoint through unified Microsoft 365 API. |
| Batch Requests | Combine multiple REST operations in a single request. |
| OData Query Support | Filter, select, expand, and order using OData operators. |

## Use Cases

| Name | Description |
|------|-------------|
| Document Automation | Automate upload, metadata tagging, and approval workflows. |
| Intranet Content Management | Manage site pages, news posts, and navigation. |
| Data Integration | Sync list data with external databases and applications. |
| Migration | Migrate content between sites or from file shares. |
| Custom Applications | Build SPFx web parts and extensions. |
| Compliance and Governance | Manage retention policies and audit logs. |
| Search Integration | Build custom search with facets and refiners. |
| Power Automate Flows | Trigger workflows based on SharePoint events. |

## Solutions

| Name | Description |
|------|-------------|
| SharePoint Online | Cloud-hosted SharePoint with REST and Graph APIs. |
| SharePoint Server | On-premises with REST, CSOM, and server-side APIs. |
| SharePoint Framework (SPFx) | Modern client-side development for web parts and extensions. |

## Artifacts

### OpenAPI

- [SharePoint REST API](openapi/sharepoint-rest-api.yaml) — 14 endpoints, 11 schemas (generated from documentation)

### JSON Schema

11 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

11 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [SharePoint Context](json-ld/sharepoint-context.jsonld) — 11 types, 35 properties

### Examples

11 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Sites and Lists](capabilities/shared/sites-and-lists.yaml) — 10 operations for site, list, and item management
- [Files and Search](capabilities/shared/files-and-search.yaml) — 5 operations for file management, search, and user profiles

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Content Management](capabilities/content-management.yaml) | Sites/Lists + Files/Search | 12 | Content Manager / Site Admin |

## Vocabulary

- [SharePoint Vocabulary](vocabulary/sharepoint-vocabulary.yaml) — 10 resources, 4 APIs, 5 domains, 5 personas

## Rules

- [SharePoint Spectral Rules](rules/sharepoint-spectral-rules.yml) — 17 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
