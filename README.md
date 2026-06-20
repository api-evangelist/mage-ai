# Mage (mage-ai)

Mage is an open-source data pipeline tool for building, running, and managing data pipelines from transformer, data loader, and data exporter blocks. The self-hosted Mage app exposes a REST API for triggering pipeline runs and managing pipelines, blocks, pipeline runs, and schedules; Mage Pro is the managed cloud edition.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mage-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mage-ai/refs/heads/main/apis.yml)

## Tags

- Data Pipelines
- Orchestration
- ETL
- Data Engineering
- Open Source

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Mage Pipeline Triggers & Runs API

Trigger a configured API trigger by POSTing to its pipeline schedule to create a pipeline run, optionally passing runtime variables, and read the status of resulting pipeline runs.

- **Human URL:** [https://docs.mage.ai/orchestration/triggers/trigger-pipeline-api](https://docs.mage.ai/orchestration/triggers/trigger-pipeline-api)
- **Base URL:** `http://localhost:6789/api`

#### Tags

- Triggers
- Pipeline Runs
- Orchestration

#### Properties

- [Documentation](https://docs.mage.ai/orchestration/triggers/trigger-pipeline-api)
- [API Reference](https://docs.mage.ai/extensibility/api-reference/pipeline-runs/overview)
- [OpenAPI](openapi/mage-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mage-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mage-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/mage-ai/mage-ai)

### Mage Pipelines API

List, create, read, update, and delete pipelines in a Mage project using the standard /api/pipelines REST resource with api_key and oauth_token authentication.

- **Human URL:** [https://docs.mage.ai/extensibility/api-reference/pipelines/create-pipeline](https://docs.mage.ai/extensibility/api-reference/pipelines/create-pipeline)
- **Base URL:** `http://localhost:6789/api`

#### Tags

- Pipelines
- CRUD
- Data Engineering

#### Properties

- [Documentation](https://docs.mage.ai/extensibility/api-reference/overview)
- [API Reference](https://docs.mage.ai/extensibility/api-reference/pipelines/create-pipeline)
- [OpenAPI](openapi/mage-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mage-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mage-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/mage-ai/mage-ai)

### Mage Blocks API

Create, read, update, and delete the data loader, transformer, and data exporter blocks that make up a pipeline, nested under the parent pipeline resource.

- **Human URL:** [https://docs.mage.ai/extensibility/api-reference/overview](https://docs.mage.ai/extensibility/api-reference/overview)
- **Base URL:** `http://localhost:6789/api`

#### Tags

- Blocks
- Transformers
- Loaders

#### Properties

- [Documentation](https://docs.mage.ai/extensibility/api-reference/overview)
- [OpenAPI](openapi/mage-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mage-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mage-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/mage-ai/mage-ai)

### Mage Pipeline Schedules API

Create, read, and update pipeline schedules (triggers) - including schedule, event, and API trigger types - that govern when and how pipelines run.

- **Human URL:** [https://docs.mage.ai/extensibility/api-reference/overview](https://docs.mage.ai/extensibility/api-reference/overview)
- **Base URL:** `http://localhost:6789/api`

#### Tags

- Schedules
- Triggers
- Scheduling

#### Properties

- [Documentation](https://docs.mage.ai/extensibility/api-reference/overview)
- [OpenAPI](openapi/mage-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mage-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mage-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/mage-ai/mage-ai)

## Common Properties

- [GitHub Organization](https://github.com/mage-ai)
- [LinkedIn](https://www.linkedin.com/company/magetech)
- [Website](https://www.mage.ai)
- [Documentation](https://docs.mage.ai)
- [Plans](plans/mage-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/mage-ai-rate-limits.yml)
- [Fin Ops](finops/mage-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
