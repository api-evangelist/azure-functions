# Azure Functions (azure-functions)

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

Azure Functions is a serverless compute service for event-triggered code execution supporting multiple languages and integration patterns including HTTP triggers, timers, queues, and more.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud, Compute, Event-Driven, Functions, Serverless

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Azure Functions
Azure Functions is a serverless compute service for event-triggered code execution supporting multiple languages and integration patterns including HTTP triggers, timers, queues, and more.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-functions/](https://learn.microsoft.com/en-us/azure/azure-functions/)

#### Tags:

 - Deployment, Functions, Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/azure-functions/)
- [OpenAPI](openapi/azure-functions-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Functions](openapi/azure-functions-openapi.yaml)

### JSON Schema

- [Backup Request](json-schema/azure-functions-backup-request-schema.json)
- [Backup Item](json-schema/azure-functions-backup-item-schema.json)
- [Container Memory Statistics](json-schema/azure-functions-container-memory-statistics-schema.json)
- [Api Kv Reference](json-schema/azure-functions-api-kv-reference-schema.json)
- [Container Info](json-schema/azure-functions-container-info-schema.json)
- [Continuous Web Job](json-schema/azure-functions-continuous-web-job-schema.json)
- [Azure Storage Property Dictionary Resource](json-schema/azure-functions-azure-storage-property-dictionary-resource-schema.json)
- [Backup Schedule](json-schema/azure-functions-backup-schedule-schema.json)
- [Container Cpu Statistics](json-schema/azure-functions-container-cpu-statistics-schema.json)
- [Container Network Interface Statistics](json-schema/azure-functions-container-network-interface-statistics-schema.json)

### JSON-LD

- [Azure Functions Context](json-ld/azure-functions-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Functions](capabilities/shared/azure-functions.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Functions Management](capabilities/azure-functions-management.yaml) | Azure Functions | 5 | Cloud Engineer |

## Vocabulary

- [Azure Functions Vocabulary](vocabulary/azure-functions-vocabulary.yaml)

## Rules

- [Azure Functions Spectral Rules](rules/azure-functions-spectral-rules.yml) — 15 rules enforcing Azure Functions API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
