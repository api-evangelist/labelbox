# Labelbox GraphQL API

The Labelbox GraphQL API provides programmatic access to the full range of Labelbox platform resources, including projects, datasets, data rows, labels, ontologies, model runs, and annotation imports. It is the underlying transport layer used by the official Labelbox Python SDK and Node.js SDK, exposing a rich set of queries and mutations for managing the complete data labeling and AI training data lifecycle. The API follows standard GraphQL conventions with a single endpoint for all operations, supporting pagination via cursor-based collections and filtering via where-clause arguments on most list queries.

Authentication is performed by passing an API key in the `Authorization` HTTP header with the format `Bearer <API_KEY>`. API keys can be generated from the Labelbox account settings page and are scoped to a specific organization. Labelbox strongly recommends using their official Python SDK (`labelbox` on PyPI) as the primary interface rather than querying the GraphQL endpoint directly, since the schema may change without notice. For teams that need direct GraphQL access, the endpoint and authentication mechanism are stable, but individual type and field names are subject to change across SDK versions.

The GraphQL endpoint accepts `application/json` POST requests with a `query` string and optional `variables` map. Error responses follow the standard GraphQL error format with an `errors` array alongside a partial `data` object. Rate limits apply at the organization level. The schema covers core types — Project, Dataset, DataRow, Label, Ontology, FeatureSchema, Task, ModelRun, Batch, Webhook, User, and Organization — as well as supporting types for annotation imports, reviews, asset attachments, and media metadata.

**Endpoint:** https://api.labelbox.com/graphql

**Documentation:** https://docs.labelbox.com/reference/graphql-overview

**References:**

- Documentation: https://docs.labelbox.com/reference/graphql-overview
- GettingStarted: https://docs.labelbox.com/reference/getting-started
