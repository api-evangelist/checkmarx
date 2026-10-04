---
name: checkmarx-reports-create-and-fetch
description: Create a new SAST scan report, poll its generation status, and retrieve the completed report.
api: openapi/checkmarx-reports-api-openapi.yml
operations:
- createReport
- getReportStatus
- getReportById
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/checkmarx-reports-api-openapi.yml ; every operationId checked against the contract
---

# checkmarx-reports-create-and-fetch

Create a new SAST scan report, poll its generation status, and retrieve the completed report.

## Steps

1. 1. Call `createReport` with the required request body describing the scan parameters (uses bearerAuth header).
2. 2. Call `getReportStatus` with the path parameter `reportId` returned from `createReport` to check if the report is ready.
3. 3. Once the status indicates completion, call `getReportById` with the same `reportId` to download the final report.

## Rules

- Authentication: Include an `Authorization: Bearer <token>` header (bearerAuth).
- Idempotency: Not applicable; the `createReport` operation creates a new resource each call.
- Pagination: Not applicable; the report endpoints return single resources.
- Errors: Follow standard HTTP error responses; no specific error codes are documented.
