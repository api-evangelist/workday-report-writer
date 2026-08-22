# Workday Report Writer (workday-report-writer)

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

APIs for Workday Report Writer - a tool for creating custom reports and data extracts from Workday HCM and Financial systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml)

## Tags

- Analytics
- Enterprise
- Erp
- Financials
- Hrms
- Reporting
- Saas

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Workday Report Writer API

SOAP web service API for creating, managing, and executing custom reports in Workday using Report Writer functionality. Provides programmatic access to report definitions, calculated fields, and report output across HCM and Financial Management modules.

- **Human URL:** [https://www.workday.com/en-us/products/financial-management/reporting-analytics.html](https://www.workday.com/en-us/products/financial-management/reporting-analytics.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service`

#### Tags

- Analytics
- Custom Reports
- Data Extraction
- Reports
- SOAP

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [API Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v41.0/Report_as_a_Service.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [Postman Collection](collections/workday-report-writer-prism-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-prism-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-report-writer-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-report-writer-wql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-wql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Report-as-a-Service (RaaS) REST API

REST API that exposes custom Workday reports as web service endpoints. Advanced-type reports enabled as web services can be consumed via RESTful endpoints, returning data in JSON, CSV, XML, and other formats. Supports query parameters for report prompts and filtering.

- **Human URL:** [https://community.workday.com/api](https://community.workday.com/api)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/customreport2`

#### Tags

- Custom Reports
- Data Export
- Report as a Service
- Reports
- REST

#### Properties

- [Documentation](https://community.workday.com/api)
- [OpenAPI](openapi/workday-report-writer-raas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-report-writer-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [SDK](https://github.com/Workday/raas-python)
- [C L I](https://github.com/Workday/raas-python)
- [GitHub Repository](https://github.com/Workday/raas-python)

### Workday WQL API

Workday Query Language (WQL) API enabling SQL-like querying of Workday data through REST endpoints. Allows developers to construct queries using SELECT, FROM, WHERE, ORDER BY, and LIMIT syntax to retrieve report data with high performance, controlled via OAuth 2.0 tokens.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/wql`

#### Tags

- Analytics
- Data Access
- Query Language
- Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](openapi/workday-report-writer-wql-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-report-writer-wql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-wql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)

### Workday Prism Analytics API

REST API for working with Workday Prism Analytics tables, datasets, and data change tasks. Enables programmatic loading of external data into Prism Analytics for advanced reporting and analytics that combines internal Workday data with external sources.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics`

#### Tags

- Analytics
- Data Loading
- Datasets
- Prism Analytics

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- [OpenAPI](openapi/workday-report-writer-prism-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-report-writer-prism-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-report-writer-prism-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/workday-report-writer-prism-table-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [SDK](https://github.com/Workday/prism-python)
- [C L I](https://github.com/Workday/prism-python)
- [GitHub Repository](https://github.com/Workday/prism-python)

## Common Properties

- [Portal](https://developer.workday.com/about)
- [Getting Started](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/KfHiRHLBJB0O63TxIyZCFA)
- [Documentation](https://community.workday.com/api)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [Sandbox](https://community.workday.com/articles/6394)
- [Hub](https://community.workday.com/)
- [Rate Limits](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/a3a_TL5Tde61ZFJKLtycjg)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Status Page](https://community.workday.com/trust/status)
- [Support](https://www.workday.com/en-us/services/support.html)
- [Blog](https://blog.workday.com/en-us/technology.html)
- [Sign Up](https://resourcecenter.workday.com/)
- [Console](https://developer.workday.com/about)
- [GitHub Organization](https://github.com/Workday)
- [API Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
