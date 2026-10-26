# Checkmarx (checkmarx)

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

Checkmarx is a leading application security testing solution provider, offering static application security testing (SAST), software composition analysis (SCA), and other security tools to help organizations identify and remediate vulnerabilities in their code.

**APIs.json:** [https://www.checkmarx.com](https://www.checkmarx.com)

## Tags

- Application Security
- Code Analysis
- DevSecOps
- SAST
- Security Testing
- Vulnerability Scanning

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Checkmarx SAST API

API for Checkmarx Static Application Security Testing (SAST) to scan source code for security vulnerabilities.

- **Human URL:** [https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html](https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html)
- **Base URL:** `https://your-checkmarx-instance.com/cxrestapi`

#### Tags

- SAST
- Security Scanning
- Static Analysis
- Vulnerability Detection

#### Properties

- [Documentation](https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html)
- [OpenAPI](https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://checkmarx.com/resource/documents/en/34965-8158-authentication.html)
- [OpenAPI](openapi/checkmarx-sast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkmarx-sast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkmarx-sast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Checkmarx SCA API

API for Software Composition Analysis to identify open source vulnerabilities and license compliance issues.

- **Human URL:** [https://checkmarx.com/resource/documents/en/34965-68617-api.html](https://checkmarx.com/resource/documents/en/34965-68617-api.html)
- **Base URL:** `https://api-sca.checkmarx.net`

#### Tags

- Dependency Scanning
- License Compliance
- Open Source Security
- SCA

#### Properties

- [Documentation](https://checkmarx.com/resource/documents/en/34965-68617-api.html)
- [Authentication](https://checkmarx.com/resource/documents/en/34965-68617-authentication.html)
- [OpenAPI](openapi/checkmarx-sca-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkmarx-sca.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkmarx-sca.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Checkmarx One API

Unified API for Checkmarx One cloud-native application security platform.

- **Human URL:** [https://checkmarx.com/resource/documents/en/34965-128036-checkmarx-one-api.html](https://checkmarx.com/resource/documents/en/34965-128036-checkmarx-one-api.html)
- **Base URL:** `https://ast.checkmarx.net/api`

#### Tags

- Application Security
- Cloud Security
- DevSecOps
- Unified Platform

#### Properties

- [Documentation](https://checkmarx.com/resource/documents/en/34965-128036-checkmarx-one-api.html)
- [API Reference](https://checkmarx.com/resource/documents/en/34965-128036-api-reference.html)
- [OpenAPI](openapi/checkmarx-one-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/checkmarx-one.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/checkmarx-one.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/checkmarx)
- [Website](https://www.checkmarx.com)
- [Documentation](https://checkmarx.com/resource/documents/)
- [Support](https://support.checkmarx.com/)
- [Login](https://checkmarx.com/login/)
- [Blog](https://checkmarx.com/blog/)
- [News](https://checkmarx.com/news/)
- [Git Hub](https://github.com/checkmarx)
- [Status Page](https://status.checkmarx.com/)
- [Privacy Policy](https://checkmarx.com/privacy-policy/)
- [Terms of Service](https://checkmarx.com/terms-of-use/)
- [JSON-LD](json-ld/checkmarx-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/checkmarx-scan-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/checkmarx-vulnerability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/checkmarx-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://checkmarx.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
