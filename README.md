# Labelbox (labelbox)

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

Labelbox is an enterprise-grade data labeling and AI training data platform that enables teams to build, manage, and evaluate machine learning models at scale. The platform provides a GraphQL API (https://api.labelbox.com/graphql) and a REST API (https://api.labelbox.com/api/v1) for programmatic access to datasets, annotation projects, labels, ontologies, and model evaluation workflows. Labelbox offers official Python and Node.js SDKs, and strongly recommends using the Python SDK rather than querying the GraphQL API directly. The platform supports RLHF preference data generation, model-assisted labeling, auto-labeling, and Foundry model integration.

APIs.json: https://raw.githubusercontent.com/api-evangelist/labelbox/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=labelbox-api-evangelist&utm_content=repo

## Tags

- Data Labeling
- AI Training
- Machine Learning
- Annotation
- Computer Vision
- RLHF
- Model Evaluation
- Dataset Management
- GraphQL
- Python SDK

## APIs

| Name | Description | Base URL |
|------|-------------|----------|
| Labelbox GraphQL API | GraphQL API for programmatic access to platform resources including datasets, projects, labels, and ontologies | https://api.labelbox.com/graphql |
| Labelbox REST API | REST API for accessing Labelbox platform resources | https://api.labelbox.com/api/v1 |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/labelbox-plans-pricing.yml](plans/labelbox-plans-pricing.yml) |
| Rate Limits | [rate-limits/labelbox-rate-limits.yml](rate-limits/labelbox-rate-limits.yml) |
| FinOps | [finops/labelbox-finops.yml](finops/labelbox-finops.yml) |

**Pricing model:** Consumption-based using Labelbox Units (LBUs). Free tier available for evaluation; Subscription tier for production workloads.

**Rate limits:** 429 status code with Retry-After header on limit breach. Use the Python SDK for automatic retry handling.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://labelbox.com |
| Documentation | https://docs.labelbox.com |
| GitHub Organization | https://github.com/Labelbox |
| LinkedIn | https://www.linkedin.com/company/labelbox |
| X | https://x.com/labelbox |
| Blog | https://labelbox.com/blog/ |
| Pricing | https://labelbox.com/pricing/ |
| Status Page | https://status.labelbox.com |
| Python SDK Docs | https://labelbox-python.readthedocs.io/en/latest/ |
| PyPI | https://pypi.org/project/labelbox/ |

## Maintainers

**Kin Lane** — kin@apievangelist.com
