# Labelbox (labelbox)

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
