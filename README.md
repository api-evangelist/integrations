# Integrations (integrations)
An index and topic collection covering the broad integration tooling market, including iPaaS and embedded-iPaaS platforms, workflow automation tools, unified API providers, ETL and reverse-ETL data pipelines, and orchestration engines. Integration platforms reduce the cost of connecting disparate SaaS, on-premise, and AI systems by offering pre-built connectors, declarative flow builders, managed authentication, and normalized data models. This collection includes general-purpose iPaaS leaders like Zapier, Make, and Workato, embedded-iPaaS providers like Paragon and Cobalt, unified API platforms like Merge, Apideck, Nango, and StackOne, data integration and ELT platforms like Fivetran, Airbyte, and Stitch, reverse-ETL tools like Hightouch and Census, and workflow orchestration engines like Airflow, Prefect, Dagster, and Kestra.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Integration, iPaaS, Embedded iPaaS, Workflow Automation, Data Integration, Unified API, ETL, Reverse ETL, Data Pipeline, Orchestration

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Connection Schema](https://raw.githubusercontent.com/api-evangelist/integrations/refs/heads/main/json-schema/integrations-connection-schema.json)
- [JSONSchema - Integration Flow Schema](https://raw.githubusercontent.com/api-evangelist/integrations/refs/heads/main/json-schema/integrations-integration-flow-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/integrations/refs/heads/main/json-ld/integrations-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/integrations/refs/heads/main/vocabulary/integrations-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Pre-Built Connector Libraries | Integration platforms ship hundreds to thousands of pre-built connectors so engineering teams can wire up SaaS systems without authoring custom HTTP clients for each provider. |
| Visual Workflow Builders | iPaaS and workflow automation tools like Zapier, Make, and n8n expose drag-and-drop or node-based canvases that let non-developers compose multi-step automations across APIs. |
| Embedded Integration Marketplaces | Embedded-iPaaS vendors like Paragon, Cobalt, and Integration.app give SaaS companies a white-labeled integration marketplace they can ship inside their own product. |
| Unified API Normalization | Unified API providers like Merge, Apideck, Nango, and StackOne collapse dozens of category-specific APIs (HRIS, CRM, ATS, accounting) into a single normalized schema and auth surface. |
| Managed ETL and ELT Pipelines | Data integration platforms like Fivetran, Airbyte, and Stitch land data from SaaS sources and databases into cloud warehouses on managed schedules with schema evolution handling. |
| Reverse ETL and Operational Sync | Reverse-ETL tools like Hightouch, Census, and Polytomic push warehouse-modeled data back out to SaaS systems of action so sales, marketing, and support teams can act on it. |
| Workflow Orchestration and Scheduling | Orchestration engines like Apache Airflow, Prefect, Dagster, and Kestra schedule, retry, and observe data and integration pipelines as declarative DAGs. |
| Managed Authentication and Connection Storage | Integration platforms handle OAuth dance, token refresh, secret rotation, and per-tenant connection storage so consuming applications never have to manage credentials directly. |

## Use Cases

| Name | Description |
|------|-------------|
| SaaS Product Integration Marketplace | SaaS vendors use embedded iPaaS like Paragon, Cobalt, or Integration.app to ship an in-product "Integrations" tab that lets customers connect to Salesforce, HubSpot, Slack, and Google Workspace. |
| Unified HRIS and ATS Sync | ATS and HR-tech vendors use unified APIs like Merge, Kombo, or Knit to onboard customers running BambooHR, Workday, ADP, and Greenhouse against a single normalized employee model. |
| SaaS-to-Warehouse Data Replication | Analytics teams use Fivetran, Airbyte, or Stitch to land Stripe, Salesforce, HubSpot, NetSuite, and PostgreSQL data into Snowflake, BigQuery, or Redshift on managed schedules. |
| Reverse ETL for Customer 360 | Data teams use Hightouch, Census, or Polytomic to push warehouse-modeled customer segments back into Salesforce, HubSpot, Braze, and Intercom for go-to-market teams. |
| Citizen-Developer Workflow Automation | Operations and revenue-ops teams use Zapier, Make, n8n, or Pabbly Connect to glue together calendars, forms, CRMs, and Slack channels without writing code. |
| Event-Driven Internal Pipelines | Platform teams use n8n, Pipedream, Trigger.dev, Prefect, or Dagster to orchestrate event-driven internal workflows that span webhooks, queues, databases, and AI calls. |
| Enterprise Application Integration | Large enterprises use Boomi, MuleSoft, Informatica, SnapLogic, and TIBCO to connect ERP, CRM, on-premise databases, and message buses with governance and SLAs. |
| AI Agent Tool and Action Integration | AI-application teams use integration platforms and unified APIs to expose hundreds of SaaS actions as governed tools that agents can invoke with managed credentials. |

## Integrations

| Name | Description |
|------|-------------|
| Zapier | General-purpose workflow automation platform with 7,000+ connected apps and a no-code trigger/action builder used by millions of small businesses. |
| Make | Visual scenario builder (formerly Integromat) for multi-step, branching automations with strong data-transformation primitives. |
| Workato | Enterprise iPaaS and intelligent automation platform with strong recipes-as-code model and embedded offering. |
| n8n | Source-available, self-hostable workflow automation tool with code nodes and an open node ecosystem. |
| MuleSoft | Salesforce-owned enterprise iPaaS and API management platform built around the Anypoint Platform and DataWeave. |
| Merge | Unified API for HRIS, ATS, CRM, ticketing, accounting, and file-storage integrations across 200+ providers. |
| Paragon | Embedded iPaaS that ships an in-product integration marketplace and workflow builder for SaaS vendors. |
| Fivetran | Managed ELT platform that lands data from 500+ SaaS sources and databases into cloud warehouses with schema evolution. |
| Airbyte | Open-source ELT platform with a community connector marketplace and a managed cloud offering. |
| Hightouch | Reverse-ETL platform that syncs modeled warehouse data into SaaS systems of action across sales, marketing, and support. |
| Apache Airflow | Widely deployed open-source workflow orchestrator that defines pipelines as Python DAGs with rich scheduling and retry semantics. |
| Nango | Open-source unified API and managed authentication layer for OAuth integrations across 400+ apps. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Connection Schema](json-schema/integrations-connection-schema.json)
- [Integration Flow Schema](json-schema/integrations-integration-flow-schema.json)

### JSON Structure

- [Connection Structure](json-structure/integrations-connection-structure.json)
- [Integration Flow Structure](json-structure/integrations-integration-flow-structure.json)

### JSON-LD

- [Integrations Context](json-ld/integrations-context.jsonld)

## Vocabulary

- [Integrations Vocabulary](vocabulary/integrations-vocabulary.yaml) — Unified taxonomy spanning connections, flows, sync jobs, and field mappings across iPaaS, embedded iPaaS, unified APIs, ETL, reverse ETL, and orchestration platforms

## Network

This index references the following integration platform repositories:

- [Airbyte](https://github.com/api-evangelist/airbyte)
- [Albato](https://github.com/api-evangelist/albato)
- [Apache Airflow](https://github.com/api-evangelist/airflow)
- [Apache NiFi](https://github.com/api-evangelist/apache-nifi)
- [Apideck](https://github.com/api-evangelist/apideck)
- [Appmixer](https://github.com/api-evangelist/appmixer)
- [Automatisch](https://github.com/api-evangelist/automatisch)
- [Bardeen](https://github.com/api-evangelist/bardeen)
- [Boomi](https://github.com/api-evangelist/boomi)
- [Celigo](https://github.com/api-evangelist/celigo)
- [Census](https://github.com/api-evangelist/census)
- [Cobalt](https://github.com/api-evangelist/cobalt)
- [Cyclr](https://github.com/api-evangelist/cyclr)
- [Dagster](https://github.com/api-evangelist/dagster)
- [Elastic.io](https://github.com/api-evangelist/elastic-io)
- [Fivetran](https://github.com/api-evangelist/fivetran)
- [Frends](https://github.com/api-evangelist/frends)
- [Hightouch](https://github.com/api-evangelist/hightouch)
- [Hotglue](https://github.com/api-evangelist/hotglue)
- [Huginn](https://github.com/api-evangelist/huginn)
- [IFTTT](https://github.com/api-evangelist/ifttt)
- [Informatica](https://github.com/api-evangelist/informatica)
- [Integrately](https://github.com/api-evangelist/integrately)
- [Integration.app](https://github.com/api-evangelist/integration-app)
- [Jitterbit](https://github.com/api-evangelist/jitterbit)
- [Kestra](https://github.com/api-evangelist/kestra)
- [Knit](https://github.com/api-evangelist/knit)
- [Kombo](https://github.com/api-evangelist/kombo)
- [Latenode](https://github.com/api-evangelist/latenode)
- [Locoia](https://github.com/api-evangelist/locoia)
- [Make](https://github.com/api-evangelist/make)
- [Merge](https://github.com/api-evangelist/merge)
- [MuleSoft](https://github.com/api-evangelist/mulesoft)
- [n8n](https://github.com/api-evangelist/n8n)
- [Nango](https://github.com/api-evangelist/nango)
- [Node-RED](https://github.com/api-evangelist/node-red)
- [Pabbly Connect](https://github.com/api-evangelist/pabbly-connect)
- [Panora](https://github.com/api-evangelist/panora)
- [Paragon](https://github.com/api-evangelist/paragon)
- [Pipedream](https://github.com/api-evangelist/pipedream)
- [Polytomic](https://github.com/api-evangelist/polytomic)
- [Prefect](https://github.com/api-evangelist/prefect)
- [Revert](https://github.com/api-evangelist/revert)
- [RudderStack](https://github.com/api-evangelist/rudderstack)
- [SnapLogic](https://github.com/api-evangelist/snaplogic)
- [StackOne](https://github.com/api-evangelist/stackone)
- [Stitch](https://github.com/api-evangelist/stitch)
- [Talend](https://github.com/api-evangelist/talend)
- [TIBCO](https://github.com/api-evangelist/tibco)
- [Tray.io](https://github.com/api-evangelist/tray-io)
- [Trigger.dev](https://github.com/api-evangelist/trigger-dev)
- [Truto](https://github.com/api-evangelist/truto)
- [Unified.to](https://github.com/api-evangelist/unified-to)
- [Vessel](https://github.com/api-evangelist/vessel)
- [Workato](https://github.com/api-evangelist/workato)
- [Zapier](https://github.com/api-evangelist/zapier)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
