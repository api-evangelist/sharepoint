# Microsoft SharePoint (sharepoint)
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

## Vocabulary

- [SharePoint Vocabulary](vocabulary/sharepoint-vocabulary.yaml) — 10 resources, 4 APIs, 5 domains, 5 personas

## Rules

- [SharePoint Spectral Rules](rules/sharepoint-spectral-rules.yml) — 17 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
