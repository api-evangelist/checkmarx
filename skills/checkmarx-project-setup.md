---
name: checkmarx-project-setup
description: Create a new Checkmarx project and configure its Git remote source settings.
api: openapi/checkmarx-projects-api-openapi.yml
operations:
- createProject
- setProjectGitSettings
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/checkmarx-projects-api-openapi.yml ; every operationId checked against the contract
---

# checkmarx-project-setup

Create a new Checkmarx project and configure its Git remote source settings.

## Steps

1. 1. `createProject` – body fields: name, description, tags, ... (as defined in the contract)
2. 2. `setProjectGitSettings` – path parameter: projectId (from createProject response); body fields: repositoryUrl, branch, authenticationType, credentials

## Rules

- Auth: Include a Bearer token in the `Authorization` header (scheme: bearerAuth).
- Idempotency: Not applicable; operations are not idempotent.
- Errors: Follow HTTP status codes defined in the API (e.g., 400 for bad request, 401 for unauthorized, 404 for not found).
