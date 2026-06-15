# Workday Report Writer (workday-report-writer)

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
