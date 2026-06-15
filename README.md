# MLflow (mlflow)

MLflow is an Apache 2.0 open-source platform for the end-to-end ML and GenAI lifecycle: tracking, model registry, deployment, evaluation, traces, prompts, and GenAI gateway. The tracking server exposes a REST API under `/api/2.0/mlflow`.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mlflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mlflow/refs/heads/main/apis.yml)

## Tags

- ML
- MLOps
- GenAI
- Experiment Tracking
- Open Source

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### MLflow REST API

The MLflow tracking server exposes a REST API for experiments, runs, parameters, metrics, tags, registered models, model versions, model aliases, and artifacts, plus newer endpoints for traces, prompts, datasets, and the AI gateway. POST requests use `application/json`. Pagination via `max_results` / `page_token`. Authentication is deployment-specific (basic auth, OIDC, or none).

- **Human URL:** [https://mlflow.org/docs/latest/rest-api.html](https://mlflow.org/docs/latest/rest-api.html)
- **Base URL:** `http://{tracking_server}/api/2.0/mlflow`

#### Tags

- REST
- Experiments
- Runs
- Model Registry
- Artifacts

#### Properties

- [Documentation](https://mlflow.org/docs/latest/rest-api.html)
- [SDK](https://mlflow.org/docs/latest/python_api/index.html)
- [SDK](https://mlflow.org/docs/latest/java_api/index.html)
- [SDK](https://mlflow.org/docs/latest/R-api.html)
- [Postman Collection](collections/mlflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mlflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MLflow AI Gateway API

The MLflow AI Gateway provides a unified HTTP interface to LLM providers with routing, rate-limiting, and secret management features.

- **Human URL:** [https://mlflow.org/docs/latest/llms/gateway/index.html](https://mlflow.org/docs/latest/llms/gateway/index.html)
- **Base URL:** `http://{gateway}/gateway`

#### Tags

- GenAI
- LLM Gateway
- REST

#### Properties

- [Documentation](https://mlflow.org/docs/latest/llms/gateway/index.html)
- [Postman Collection](collections/mlflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mlflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mlflow-org)
- [Website](https://mlflow.org/)
- [Portal](https://mlflow.org/docs/latest/)
- [Source Code](https://github.com/mlflow/mlflow)
- [License](https://github.com/mlflow/mlflow/blob/master/LICENSE.txt)
- [Commercial Offering](https://www.databricks.com/product/managed-mlflow)
- [Plans](plans/mlflow-plans-pricing.yml)
- [Rate Limits](rate-limits/mlflow-rate-limits.yml)
- [Fin Ops](finops/mlflow-finops.yml)
- [L L Ms Txt](https://mlflow.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
