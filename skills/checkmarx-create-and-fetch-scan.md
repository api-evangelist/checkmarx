---
name: checkmarx-create-and-fetch-scan
description: Create a new scan and retrieve its details.
api: openapi/checkmarx-scans-api-openapi.yml
operations:
- createScan
- getScan
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/checkmarx-scans-api-openapi.yml ; every operationId checked against the contract
---

# checkmarx-create-and-fetch-scan

Create a new scan and retrieve its details.

## Steps

1. 1. Call `createScan` with the required request body fields as defined in the contract.
2. 2. Call `getScan` with the `scanId` returned from `createScan` as a path parameter.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (scheme: bearerAuth).
- Errors: On failure the API returns appropriate HTTP status codes; no specific idempotency or pagination applies to this task.
