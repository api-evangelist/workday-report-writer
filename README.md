# Workday Report Writer (workday-report-writer)
APIs for Workday Report Writer - a tool for creating custom reports and data extracts from Workday HCM and Financial systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Enterprise, Erp, Financials, Hrms, Reporting, Saas

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### Workday Report Writer API
SOAP web service API for creating, managing, and executing custom reports in Workday using Report Writer functionality. Provides programmatic access to report definitions, calculated fields, and report output across HCM and Financial Management modules.

**Human URL:** [https://www.workday.com/en-us/products/financial-management/reporting-analytics.html](https://www.workday.com/en-us/products/financial-management/reporting-analytics.html)

#### Tags:

 - Analytics, Custom Reports, Data Extraction, Reports, SOAP

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [APIReference](https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v41.0/Report_as_a_Service.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)

### Workday Report-as-a-Service (RaaS) REST API
REST API that exposes custom Workday reports as web service endpoints. Advanced-type reports enabled as web services can be consumed via RESTful endpoints, returning data in JSON, CSV, XML, and other formats. Supports query parameters for report prompts and filtering.

**Human URL:** [https://community.workday.com/api](https://community.workday.com/api)

#### Tags:

 - Custom Reports, Data Export, Report as a Service, Reports, REST

#### Properties

- [Documentation](https://community.workday.com/api)
- [OpenAPI](openapi/workday-report-writer-raas-openapi.yml)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [SDK: Python SDK](https://github.com/Workday/raas-python)
- [CLI: RaaS Python CLI](https://github.com/Workday/raas-python)
- [GitHubRepository](https://github.com/Workday/raas-python)

### Workday WQL API
Workday Query Language (WQL) API enabling SQL-like querying of Workday data through REST endpoints. Allows developers to construct queries using SELECT, FROM, WHERE, ORDER BY, and LIMIT syntax to retrieve report data with high performance, controlled via OAuth 2.0 tokens.

**Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)

#### Tags:

 - Analytics, Data Access, Query Language, Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](openapi/workday-report-writer-wql-openapi.yml)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)

### Workday Prism Analytics API
REST API for working with Workday Prism Analytics tables, datasets, and data change tasks. Enables programmatic loading of external data into Prism Analytics for advanced reporting and analytics that combines internal Workday data with external sources.

**Human URL:** [https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)

#### Tags:

 - Analytics, Data Loading, Datasets, Prism Analytics

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- [OpenAPI](openapi/workday-report-writer-prism-analytics-openapi.yml)
- [JSONSchema: Prism Table Schema Definition](json-schema/workday-report-writer-prism-table-schema.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [SDK: Python SDK](https://github.com/Workday/prism-python)
- [CLI: Prism Python CLI](https://github.com/Workday/prism-python)
- [GitHubRepository](https://github.com/Workday/prism-python)

## Common Properties

- [Portal](https://developer.workday.com/about)
- [GettingStarted](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/KfHiRHLBJB0O63TxIyZCFA)
- [Documentation](https://community.workday.com/api)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html)
- [Sandbox](https://community.workday.com/articles/6394)
- [Hub](https://community.workday.com/)
- [RateLimits](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/a3a_TL5Tde61ZFJKLtycjg)
- [TermsOfService](https://www.workday.com/en-us/legal.html)
- [PrivacyPolicy](https://www.workday.com/en-us/privacy.html)
- [StatusPage](https://community.workday.com/trust/status)
- [Support](https://www.workday.com/en-us/services/support.html)
- [Blog](https://blog.workday.com/en-us/technology.html)
- [SignUp](https://resourcecenter.workday.com/)
- [Console](https://developer.workday.com/about)
- [GitHubOrganization](https://github.com/Workday)
- [APIReference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)

## Features

| Name | Description |
|------|-------------|
| Custom Report Authoring | Build custom reports using Report Writer with calculated fields, subfilters, and grouping across HCM and Financial Management data. |
| Report-as-a-Service Web Endpoints | Expose any advanced custom report as a REST or SOAP web service returning JSON, CSV, XML, or RSS for programmatic consumption. |
| SQL-Like Data Access via WQL | Query Workday data with SQL-like SELECT/FROM/WHERE/ORDER BY/LIMIT syntax against governed data sources for high-performance retrieval. |
| External Data Loading with Prism Analytics | Programmatically create tables, upload compressed files via buckets, and run data change tasks (insert, update, upsert, delete) in Prism. |
| OAuth 2.0 Authentication | Secure access to REST endpoints using OAuth 2.0 client credentials, refresh tokens, and bearer tokens managed through API client setup. |
| Multi-Format Output | Retrieve report data in JSON, CSV, XML, RSS, and other formats with query parameter control over filtering, prompts, and pagination. |

## Use Cases

| Name | Description |
|------|-------------|
| HR Analytics and Workforce Reporting | Extract headcount, compensation, and turnover metrics from Workday HCM for downstream analytics, dashboards, and board reporting. |
| Financial Reporting and Close | Pull custom financial reports for general ledger, accounts payable, and budget variance analysis in support of period close processes. |
| Data Warehouse and Lake Hydration | Schedule RaaS or WQL extracts to feed Snowflake, BigQuery, Redshift, Databricks, or other downstream systems with Workday data. |
| External Data Blending in Prism | Load external CSV or Parquet datasets into Prism Analytics tables to combine with native Workday data for cross-source reporting. |
| Operational Integrations | Drive payroll vendors, benefits providers, and identity systems with scheduled report extracts derived from Workday source-of-truth data. |
| Compliance and Audit Reporting | Generate audit-ready extracts of personnel actions, journal entries, and security configurations for regulatory and SOX compliance. |

## Integrations

| Name | Description |
|------|-------------|
| Snowflake | Land Workday RaaS and WQL extracts into Snowflake stages for use in enterprise data warehouse pipelines. |
| Databricks | Ingest Workday report data into Databricks for analytics, ML feature engineering, and lakehouse modeling. |
| Tableau | Connect Tableau to RaaS endpoints or downstream warehouses to build interactive dashboards on Workday HCM and financial data. |
| Power BI | Use RaaS JSON or CSV outputs as data sources for Microsoft Power BI reports and semantic models. |
| Workato | Orchestrate Workday API calls in iPaaS workflows that move data between Workday and third-party SaaS applications. |
| SnapLogic | Build integration pipelines using SnapLogic's Workday Snap Pack to read RaaS, WQL, and Prism endpoints. |
| Boomi | Connect Workday APIs to ERP, CRM, and HRIS systems through Boomi AtomSphere integration processes. |

## Solutions

| Name | Description |
|------|-------------|
| HCM Reporting | End-to-end workforce and people analytics built on Report Writer, RaaS, and WQL across the Workday HCM suite. |
| Financial Management Reporting | Custom financial reporting and extracts spanning ledgers, projects, procurement, and revenue across Workday Financial Management. |
| Prism Analytics | Bring external data into Workday and combine with native data sets to deliver advanced analytics and self-service reporting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Workday Prism Analytics API](openapi/workday-report-writer-prism-analytics-openapi.yml)
- [Workday Report-as-a-Service (RaaS) REST API](openapi/workday-report-writer-raas-openapi.yml)
- [Workday WQL API](openapi/workday-report-writer-wql-openapi.yml)

### JSON Schema

- [Workday Prism Analytics Table Schema](json-schema/workday-report-writer-prism-table-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
