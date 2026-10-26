# MLflow (mlflow)

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
