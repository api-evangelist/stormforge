# StormForge (stormforge)

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

StormForge provides machine learning-based Kubernetes resource optimization (rightsizing) for reducing cloud infrastructure costs while maintaining application performance. The Optimize Live product deploys an agent to Kubernetes clusters that collects workload metrics, applies ML algorithms, and generates CPU and memory recommendations for containers. Recommendations can be applied automatically, on-demand, or exported as Kubernetes patches for GitOps workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Machine Learning
- Resource Management
- Rightsizing

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## APIs

### StormForge Optimize Live
Machine learning-based Kubernetes resource rightsizing product. Deploys an agent to clusters to collect metrics, generates CPU and memory recommendations, and supports automatic or GitOps-based application.

**Human URL:** [https://www.stormforge.io/optimize-live/](https://www.stormforge.io/optimize-live/)

#### Tags

- Cloud Cost Optimization, FinOps, Kubernetes, Machine Learning, Rightsizing

#### Properties

- [Documentation](https://docs.stormforge.io/docs/)
- [Getting Started](https://docs.stormforge.io/docs/get-started/)
- [Pricing](https://www.stormforge.io/pricing/)
- [Sign Up](https://app.stormforge.io/)

### StormForge CLI
Command-line interface for managing clusters, workloads, and optimization recommendations. Supports authentication, resource inspection, recommendation generation and application, and MCP server for AI integration.

**Human URL:** [https://docs.stormforge.io/docs/stormforge-cli/reference/](https://docs.stormforge.io/docs/stormforge-cli/reference/)

#### Tags

- CLI, DevOps, FinOps, Kubernetes

#### Properties

- [Documentation](https://docs.stormforge.io/docs/stormforge-cli/reference/)
- [GitHub Repository](https://github.com/thestormforge)

## Artifacts

### JSON Schemas

| File | Description |
|---|---|
| [stormforge-recommendation-schema.json](json-schema/stormforge-recommendation-schema.json) | Schema for StormForge rightsizing recommendations |

### JSON Structure

| File | Description |
|---|---|
| [stormforge-recommendation-structure.json](json-structure/stormforge-recommendation-structure.json) | Recommendation object field documentation |

### JSON-LD

| File | Description |
|---|---|
| [stormforge-context.jsonld](json-ld/stormforge-context.jsonld) | JSON-LD context for Kubernetes optimization vocabulary |

### Vocabulary

| File | Description |
|---|---|
| [stormforge-vocabulary.yml](vocabulary/stormforge-vocabulary.yml) | Domain vocabulary for Kubernetes rightsizing and FinOps |

## Common Properties

- [Website](https://www.stormforge.io/)
- [Documentation](https://docs.stormforge.io/)
- [Pricing](https://www.stormforge.io/pricing/)
- [Blog](https://www.stormforge.io/blog/)
- [About](https://www.stormforge.io/about/)
- [Contact](https://www.stormforge.io/contact/)
- [Getting Started](https://docs.stormforge.io/docs/get-started/)
- [Sign Up](https://app.stormforge.io/)
- [GitHub Org](https://github.com/thestormforge)
- [Sandbox](https://docs.stormforge.io/docs/sandbox/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
