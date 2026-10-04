---
name: checkmarx-manage-applications
description: Create, view, update, and delete applications in Checkmarx.
api: openapi/checkmarx-applications-api-openapi.yml
operations:
- createApplication
- listApplications
- getApplication
- updateApplication
- deleteApplication
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/checkmarx-applications-api-openapi.yml ; every operationId checked against the contract
---

# checkmarx-manage-applications

Create, view, update, and delete applications in Checkmarx.

## Steps

1. 1. `createApplication` – send a POST to `/applications` with the required application fields in the request body and include the `Authorization: Bearer <token>` header.
2. 2. `listApplications` – send a GET to `/applications` with the `Authorization` header to retrieve all applications.
3. 3. `getApplication` – send a GET to `/applications/{applicationId}` with the `Authorization` header to fetch details of a specific application.
4. 4. `updateApplication` – send a PUT to `/applications/{applicationId}` with the updated application fields in the request body and the `Authorization` header.
5. 5. `deleteApplication` – send a DELETE to `/applications/{applicationId}` with the `Authorization` header to remove the application.

## Rules

- All requests must include an `Authorization: Bearer <token>` header (bearerAuth).
- No rate limiting is documented; exhaustion returns no specific HTTP status.
