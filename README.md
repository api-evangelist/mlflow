# MLflow (mlflow)

MLflow is an Apache 2.0 open-source platform for the end-to-end ML and GenAI lifecycle: tracking, model registry, deployment, evaluation, traces, prompts, and GenAI gateway. The tracking server exposes a REST API under `/api/2.0/mlflow`.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mlflow/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=mlflow-api-evangelist&utm_content=repo)

## Type
- **x-type:** opensource

## APIs
- **MLflow REST API** - `/api/2.0/mlflow` on the tracking server. Experiments, runs, params, metrics, tags, registered models, model versions, model aliases, artifacts, traces, prompts, datasets, AI gateway. JSON over HTTP.
- **MLflow AI Gateway API** - Unified HTTP interface to LLM providers with routing, rate-limiting, secrets.

## Tags
- ML, MLOps, GenAI, Experiment Tracking, Open Source

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://mlflow.org/)
- [Documentation](https://mlflow.org/docs/latest/)
- [Source (Apache 2.0)](https://github.com/mlflow/mlflow)
- [Commercial: Databricks Managed MLflow](https://www.databricks.com/product/managed-mlflow)
- [Plans](plans/mlflow-plans-pricing.yml)
- [RateLimits](rate-limits/mlflow-rate-limits.yml)
- [FinOps](finops/mlflow-finops.yml)

## Notes
- FOSS, no commercial API surface. Self-host the tracking server. Databricks Managed MLflow is the canonical hosted offering; DagsHub also exposes a per-repo MLflow endpoint.
- REST API is well-documented at https://mlflow.org/docs/latest/rest-api.html.
- Authentication is deployment-specific (basic/OIDC/none).

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
