# Migration (migration)
An index and topic collection covering data migration, cloud migration, database migration, and API migration platforms and services. Migration platforms help organizations move workloads, databases, files, accounts, and applications between environments, providers, or schemas while preserving integrity, minimizing downtime, and tracking cutover progress. This collection includes cloud migration services like AWS Application Migration Service, Azure Migrate, and Google Cloud Migration Center; database migration and replication tools like AWS DMS, Oracle GoldenGate, and Google Cloud Datastream; modern data movement platforms like Airbyte, Fivetran, and Hotglue; and code, content, and tenant migration tooling used during platform changeovers.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Migration, Data Migration, Database Migration, Cloud Migration, API Migration, Replication, Cutover

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Migration Project Schema](https://raw.githubusercontent.com/api-evangelist/migration/refs/heads/main/json-schema/migration-migration-project-schema.json)
- [JSONSchema - Cutover Plan Schema](https://raw.githubusercontent.com/api-evangelist/migration/refs/heads/main/json-schema/migration-cutover-plan-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/migration/refs/heads/main/json-ld/migration-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/migration/refs/heads/main/vocabulary/migration-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Cloud Workload Migration | Services like AWS Application Migration Service, Azure Migrate, and Google Cloud Migration Center lift and shift servers, VMs, and applications between data centers and cloud providers with assessment, replication, and cutover tooling. |
| Database Migration and Replication | Database migration services like AWS DMS, Oracle GoldenGate, and Google Cloud Datastream replicate transactional data between heterogeneous database engines with change data capture and minimal downtime cutover. |
| Schema Migration and Versioning | Tooling like dbt, Liquibase, and Flyway version, diff, and apply schema and transformation changes through migration files checked into source control alongside application code. |
| ETL and Data Movement | Platforms like Airbyte, Fivetran, Hotglue, and Stitch extract data from SaaS sources, APIs, and databases and load it into warehouses and lakes with managed connectors and incremental sync. |
| Change Data Capture | Tools like Debezium and Kafka Connect stream row-level database changes as events, enabling near-real-time replication, audit trails, and downstream system synchronization during long-running migrations. |
| Assessment and Discovery | Migration assessment tools inventory existing servers, applications, dependencies, and licenses to plan target architecture, sizing, and migration waves before cutover begins. |
| Cutover Planning and Rollback | Migration platforms coordinate rehearsals, dependency ordering, cutover windows, validation gates, and rollback procedures to reduce blast radius during go-live. |
| API and Code Migration | SDK and API migration tooling like Liblab and OpenRewrite regenerate client libraries and rewrite consumer code when APIs change versions, providers, or specification standards. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Center to Cloud Lift and Shift | Enterprises use AWS Application Migration Service, Azure Migrate, or Google Cloud Migration Center to inventory on-premise workloads and replicate them to the cloud with minimal application changes. |
| Heterogeneous Database Migration | Teams use AWS DMS or Oracle GoldenGate to migrate from legacy commercial databases like Oracle and SQL Server to open-source or cloud-native engines such as Postgres, Aurora, or BigQuery. |
| SaaS Data Onboarding | Data teams use Airbyte, Fivetran, or Stitch to backfill historical data from SaaS sources like Salesforce, HubSpot, and Stripe into a warehouse and keep it incrementally in sync. |
| Real-Time Replication and CDC | Engineering teams stand up Debezium and Kafka Connect to stream change data capture events from operational databases into analytical systems, search indexes, and microservices. |
| Cross-Tenant SaaS Migration | IT teams migrate mailboxes, files, and identities between Microsoft 365, Google Workspace, and Slack tenants during mergers, acquisitions, or restructurings using dedicated tenant migration tooling. |
| Schema Evolution at Deploy Time | Application teams version SQL migrations alongside code using tools like dbt, Liquibase, and Flyway so that schema changes deploy and roll back atomically with releases. |
| API Version Cutover | API providers use migration tooling and codegen platforms like Liblab to help consumers move between major versions of an API with regenerated SDKs and rewritten call sites. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Database Migration Service | Managed database migration and replication service supporting homogeneous and heterogeneous migrations between Oracle, SQL Server, MySQL, Postgres, Aurora, and analytics targets. |
| Azure Migrate | Unified hub for discovery, assessment, and migration of servers, databases, web apps, and virtual desktops to Microsoft Azure. |
| Google Cloud Datastream | Serverless change data capture and replication service streaming changes from Oracle, MySQL, and Postgres into BigQuery, Cloud SQL, and Cloud Storage. |
| Airbyte | Open-source data integration platform with 350+ connectors for moving data from SaaS and database sources into warehouses and lakes. |
| Fivetran | Managed ELT platform with automated schema migration, normalization, and incremental replication from operational sources to cloud data warehouses. |
| Oracle GoldenGate | Real-time data replication and integration platform for heterogeneous database migration, high availability, and zero-downtime cutover. |
| Debezium | Open-source distributed change data capture platform built on Kafka Connect for streaming row-level changes from MySQL, Postgres, MongoDB, and more. |
| dbt | Data transformation and modeling tool that versions schema and transformation migrations as SQL and YAML alongside warehouse pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Migration Project Schema](json-schema/migration-migration-project-schema.json)
- [Cutover Plan Schema](json-schema/migration-cutover-plan-schema.json)

### JSON Structure

- [Migration Project Structure](json-structure/migration-migration-project-structure.json)
- [Cutover Plan Structure](json-structure/migration-cutover-plan-structure.json)

### JSON-LD

- [Migration Context](json-ld/migration-context.jsonld)

## Vocabulary

- [Migration Vocabulary](vocabulary/migration-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across cloud migration, database migration, data movement, and code migration platforms

## Network

This index references the following migration platform repositories:

- [Airbyte](https://github.com/api-evangelist/airbyte)
- [Alteryx](https://github.com/api-evangelist/alteryx)
- [Amazon DataSync](https://github.com/api-evangelist/amazon-datasync)
- [Amazon DMS](https://github.com/api-evangelist/amazon-dms)
- [Amazon Mainframe Modernization](https://github.com/api-evangelist/amazon-mainframe-modernization)
- [Amazon Migration Hub](https://github.com/api-evangelist/amazon-migration-hub)
- [Azure Migrate](https://github.com/api-evangelist/microsoft-azure-migrate)
- [Azure Site Recovery](https://github.com/api-evangelist/microsoft-azure-site-recovery)
- [Boomi](https://github.com/api-evangelist/boomi)
- [Calypso Migration](https://github.com/api-evangelist/calypso-migration)
- [CData](https://github.com/api-evangelist/cdata)
- [dbt](https://github.com/api-evangelist/dbt)
- [Debezium](https://github.com/api-evangelist/debezium)
- [Fivetran](https://github.com/api-evangelist/fivetran)
- [Google Cloud Datastream](https://github.com/api-evangelist/google-cloud-datastream)
- [Google Cloud Migration Center](https://github.com/api-evangelist/google-cloud-migration-center)
- [Google Cloud Transfer Service](https://github.com/api-evangelist/google-cloud-transfer-service)
- [Google Cloud VMware Engine](https://github.com/api-evangelist/google-cloud-vmware-engine)
- [Hotglue](https://github.com/api-evangelist/hotglue)
- [Informatica](https://github.com/api-evangelist/informatica)
- [Kafka Connect](https://github.com/api-evangelist/kafka-connect)
- [Liblab](https://github.com/api-evangelist/liblab)
- [Oracle GoldenGate](https://github.com/api-evangelist/oracle-goldengate)
- [Qlik](https://github.com/api-evangelist/qlik)
- [Stitch](https://github.com/api-evangelist/stitch)
- [Talend](https://github.com/api-evangelist/talend)
- [Tray.io](https://github.com/api-evangelist/tray-io)
- [Workato](https://github.com/api-evangelist/workato)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
