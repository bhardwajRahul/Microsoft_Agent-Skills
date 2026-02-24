---
generated_at: '2026-02-24'
category_descriptions:
  decision-making: Guidance on selecting the right Azure Data Manager for Energy tier,
    comparing capabilities, scale, and cost trade-offs for different workloads and
    environments.
  configuration: 'Configuring ADME environment: data partitions, external data services/sources,
    enabling Reservoir DDMS, and setting up/using audit logging for governance and
    integration.'
  security: 'Securing Azure Data Manager for Energy: auth tokens, ACLs, legal tags,
    entitlements, CORS, API Management, private endpoints, managed identities, and
    Customer Lockbox.'
  deployment: Guides for deploying Azure Data Manager for Energy components, including
    the Geospatial Consumption Zone and OSDU Admin UI, with required configs and deployment
    steps.
  integrations: Patterns for integrating Energy Data Services with Azure Monitor and
    File APIs, including exporting OSDU logs, wiring Airflow/Elasticsearch logs, and
    uploading large files programmatically.
  architecture-patterns: Guidance on architecting resilient Azure Data Manager for
    Energy deployments, including high availability, fault tolerance, disaster recovery,
    and reliability best practices.
  troubleshooting: Diagnosing and fixing manifest ingestion failures in Azure Data
    Manager for Energy using Airflow logs, including log analysis, common error patterns,
    and remediation steps.
---
# Azure Energy Data Services Crawl Report

## Summary

- **Total Pages**: 51
- **Fetched**: 51
- **Fetch Failed**: 0
- **Classified**: 24
- **Unclassified**: 27

### Incremental Update
- **New Pages**: 3
- **Updated Pages**: 3
- **Unchanged**: 45
- **Deleted Pages**: 2
- **Compared With**: `/home/vsts/work/1/s/Agent-Skills/products/azure-energy-data-services/azure-energy-data-services.csv`

## Classification Statistics

| Type | Count | Percentage |
|------|-------|------------|
| architecture-patterns | 1 | 2.0% |
| configuration | 5 | 9.8% |
| decision-making | 1 | 2.0% |
| deployment | 2 | 3.9% |
| integrations | 4 | 7.8% |
| security | 10 | 19.6% |
| troubleshooting | 1 | 2.0% |
| *(Unclassified)* | 27 | 52.9% |

## Changes

### New Pages

- [Reliability overview](https://learn.microsoft.com/en-us/azure/energy-data-services/reliability-energy-data-services)
- [How to enable External Data Services (EDS)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-external-data-services)
- [How to register External Data Services (EDS)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-register-external-data-services)

### Updated Pages

- [Create a Microsoft Azure Data Manager for Energy instance](https://learn.microsoft.com/en-us/azure/energy-data-services/quickstart-create-microsoft-energy-data-services-instance)
  - Updated: 2024-08-29T22:04:00.000Z → 2026-02-11T18:17:00.000Z
- [How to enable Reservoir DDMS](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-reservoir-ddms)
  - Updated: 2025-11-26T12:09:00.000Z → 2026-02-19T06:12:00.000Z
- [FAQ](https://learn.microsoft.com/en-us/azure/energy-data-services/faq-energy-data-services)
  - Updated: 2025-04-08T11:16:00Z → 2026-02-11T18:17:00Z

### Deleted Pages

- ~~How to enable External Data Sources (EDS)~~ (https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-external-data-sources)
- ~~How to register External Data Sources (EDS)~~ (https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-register-external-data-sources)

## Classified Pages

| TOC Title | Type | Confidence | Reason |
|-----------|------|------------|--------|
| [Troubleshooting manifest ingestion](https://learn.microsoft.com/en-us/azure/energy-data-services/troubleshoot-manifest-ingestion) | troubleshooting | 0.85 | Explicitly a troubleshooting article for manifest ingestion using Airflow task logs; such content typically maps specific symptoms and log messages to causes and resolutions, and references product-specific diagnostic locations and procedures, fitting the troubleshooting criteria. |
| [Airflow task logs integration with Azure Monitor](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-airflow-logs-with-azure-monitor) | integrations | 0.80 | Describes collecting Airflow logs into Azure Monitor for ADME; likely includes diagnostic setting names, categories, and configuration parameters specific to this integration. |
| [Elastic logs integration with Azure Monitor](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-elastic-logs-with-azure-monitor) | integrations | 0.80 | How-to for exporting Elasticsearch logs from ADME into Azure Monitor; typically lists diagnostic categories, resource types, and parameter values unique to this product integration. |
| [Integrate OSDU Service Logs with Azure Monitor](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-osdu-service-logs-with-azure-monitor) | integrations | 0.80 | Shows how to integrate OSDU service logs with Azure Monitor via diagnostic settings; includes product-specific log categories and configuration parameters. |
| [Publish Microsoft Azure Data Manager for Energy APIs to a secured API gateway](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-secure-apis) | security | 0.80 | Describes publishing the service’s APIs through Azure API Management with Private Link and removing public access; this typically includes specific configuration steps, policy settings, and network/security parameters unique to this product integration, fitting product-specific security configuration. |
| [Set up Managed Identity](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-use-managed-identity) | security | 0.80 | Describes using managed identities to access ADME control and data planes; typically includes specific scopes, resource IDs, and role assignments that are product-specific security configuration details. |
| [Set up Private Links](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-set-up-private-links) | security | 0.80 | Private endpoint setup for ADME involves specific resource types, subresource names, and network configuration parameters; these are product-specific security/network configuration details. |
| [Generate auth token](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-generate-auth-token) | security | 0.75 | Token generation for this specific service will include concrete authentication parameters (scopes, resource URIs, client IDs, grant types) and possibly example requests unique to Azure Data Manager for Energy, which are product-specific security/auth configuration details. |
| [Deploy Geospatial Consumption Zone (GCZ)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-deploy-gcz) | deployment | 0.70 | Deployment guide for GCZ on top of ADME; likely includes product-specific deployment requirements, supported tiers, and configuration steps beyond generic deployment knowledge. |
| [Deploy OSDU Admin UI](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-deploy-osdu-admin-ui) | deployment | 0.70 | Shows how to deploy OSDU Admin UI on ADME; such content typically includes environment-specific deployment parameters and constraints unique to this integration. |
| [How to enable External Data Services (EDS)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-external-data-services) | configuration | 0.70 | Describes how to enable External Data Services, including use of managed identities and Azure Key Vault secrets for the EDS secret service. This is product-specific configuration guidance that likely includes concrete settings (system-assigned vs user-assigned identity, Key Vault access configuration) rather than just conceptual explanation. |
| [How to enable legal tags restricted COO (Country of Origin)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-legal-tags-restricted-country-of-origin) | security | 0.70 | Focuses on enabling legal tag creation for restricted country-of-origin data; likely includes specific compliance-related settings and conditions, which are product-specific security/compliance configurations. |
| [How to register External Data Services (EDS)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-register-external-data-services) | configuration | 0.70 | Explains how to register External Data Services with Azure Data Manager for Energy to fetch and ingest metadata and bulk data. This is a how-to configuration article that likely includes specific parameters/endpoints and registration settings unique to this product, which an LLM would not know from training alone. |
| [Manage ACLs](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-acls) | security | 0.70 | Managing ACLs on data records is security/authorization configuration; such pages typically list ACL fields, allowed values, and patterns unique to this product. |
| [Manage legal tags](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-legal-tags) | security | 0.70 | Legal tags govern data ingestion and access; how-to management article is likely to include specific tag properties, required fields, and constraints that are product-specific security/compliance settings. |
| [Manage users](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-users) | security | 0.70 | How-to for managing users and OSDU groups via Entitlements APIs; likely includes specific group names, API calls, and permission scopes that are product-specific security configuration details. |
| [Set up Lockbox](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-create-lockbox) | security | 0.70 | Explains how Lockbox requests are initiated and tracked for ADME; likely includes specific workflows, permissions, and settings unique to this service’s security model. |
| [Set up Resource sharing (CORS)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-cors) | security | 0.70 | A 'how to enable CORS' page for a specific service typically includes concrete configuration steps and parameter values (allowed origins, headers, methods) specific to Azure Data Manager for Energy endpoints, which are product-specific security configuration details beyond generic CORS concepts. |
| [Tier details](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-tier-details) | decision-making | 0.70 | Tier concepts for Developer vs Standard SKU typically include comparison criteria and guidance on when to use each tier; this is product- and SKU-specific decision guidance beyond generic knowledge. |
| [Upload large files using file service](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-upload-large-files-using-file-service) | integrations | 0.70 | Describes using a signed URL from the File API to upload ~5GB files to Blob Storage; such a page typically includes API parameters, request/response fields, and constraints specific to this product’s file service integration with Blob Storage, matching the integrations & coding patterns criteria. |
| [How to enable Reservoir DDMS](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-reservoir-ddms) | configuration | 0.65 | Covers enabling the Reservoir Domain Data Management Service, a product-specific capability with particular activation/availability behavior (now GA, available by default on all instances). Even though it notes that steps may no longer be required, the article is a configuration-focused guide for this specialized service and likely includes product-specific settings or prerequisites. |
| [Manage data partitions](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-add-more-data-partitions) | configuration | 0.65 | How-to for adding partitions usually includes partition identifiers, allowed formats, and configuration steps specific to Azure Data Manager for Energy, fitting configuration of isolation units. |
| [Reliability overview](https://learn.microsoft.com/en-us/azure/energy-data-services/reliability-energy-data-services) | architecture-patterns | 0.65 | Focuses on reliability patterns for Azure Data Manager for Energy using zone-redundant instances and cross-region disaster recovery. While the summary is high level, this type of article typically includes product-specific guidance on when to use regional vs cross-region resiliency options and how to structure active-passive DR for this service, which constitutes architecture and design pattern guidance beyond generic reliability concepts. |
| [Set up audit logs](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-audit-logs) | configuration | 0.65 | Managing audit logs for this service is likely to include product-specific settings such as log categories, destinations, and configuration parameters or examples for enabling and querying logs, which are detailed configuration behaviors not captured by generic logging knowledge. |

## Unclassified Pages

| TOC Title | Confidence | Reason |
|-----------|------------|--------|
| [Authentication](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-authentication) | 0.40 | Authentication concepts article; explains service principals and tokens conceptually, but summary does not indicate specific RBAC roles, scopes, or parameter tables. |
| [Set up Customer managed encryption keys (CMEK)](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-data-security-and-encryption) | 0.40 | Summary indicates a high-level overview of encryption and keys; without evidence of specific key vault configuration parameters or role mappings, it appears conceptual rather than detailed configuration. |
| [Use Rock and Fluid Samples DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-rock-and-fluid-samples-ddms) | 0.40 | RAFS DDMS API tutorial; step-by-step cURL workflow, but no explicit mention of configuration tables, limits, or error-code mappings. |
| [Use Seismic Store DDMS sdutil](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-seismic-ddms-sdutil) | 0.40 | Tutorial for using sdutil with Seismic Store; likely includes commands but summary does not show structured config tables, error mappings, or limits. |
| [CSV parser ingestion](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-csv-parser-ingestion) | 0.30 | Conceptual description of CSV parser ingestion workflow; focuses on ELT concept and custom schema, not on numeric limits or detailed configuration parameters. |
| [Convert SEG-Y to ZGY](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-convert-segy-to-zgy) | 0.30 | Described as a step-by-step tutorial for converting SEG-Y to ZGY; likely focuses on procedural steps rather than configuration tables, limits, or product-specific diagnostic mappings. It reads as a workflow guide rather than expert reference content per the defined categories. |
| [Convert SEG-Y to oVDS](https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-convert-segy-to-ovds) | 0.30 | Similar to index 3, this is a step-by-step tutorial for converting SEG-Y to oVDS; primarily a procedural guide without clear indication of configuration matrices, limits, or troubleshooting mappings that qualify as expert reference under the given sub-skill types. |
| [Entitlements](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-entitlements) | 0.30 | Conceptual description of entitlement service and access management; summary does not indicate concrete RBAC role names, permission scopes, or configuration parameters. |
| [Ingest CSV wellbore data](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-csv-ingestion) | 0.30 | Tutorial for CSV ingestion; appears to be procedural how-to without explicit configuration parameter tables or product-specific limits. |
| [Ingest manifests](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-manifest-ingestion) | 0.30 | Manifest ingestion tutorial; summary suggests step-by-step usage, not detailed configuration matrices or limits. |
| [Manifest ingestion](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-manifest-ingestion) | 0.30 | Manifest ingestion concepts article; conceptual explanation of metadata and search, without specific limits, configs, or troubleshooting mappings. |
| [Release notes](https://learn.microsoft.com/en-us/azure/energy-data-services/release-notes) | 0.30 | Release notes summary; while it may contain specific changes, the provided summary does not indicate structured limits, configs, or troubleshooting mappings. |
| [Use Petrel DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-petrel-ddms) | 0.30 | Petrel DDMS API tutorial; focuses on using APIs, not on limits, quotas, or detailed configuration matrices. |
| [Use Reservoir DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-reservoir-ddms-apis) | 0.30 | Reservoir DDMS REST API tutorial with curl; appears to be basic read operations, not configuration or troubleshooting reference. |
| [Use Reservoir DDMS websocket APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-reservoir-ddms-websocket) | 0.30 | Reservoir DDMS websocket tutorial; summary suggests usage steps, not detailed configuration parameters or limits. |
| [Use Seismic Store DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-seismic-ddms) | 0.30 | Seismic DDMS API tutorial using cURL; appears to be basic API usage rather than configuration references or troubleshooting content. |
| [Use Well Delivery DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-well-delivery-ddms) | 0.30 | Well Delivery DDMS API tutorial; procedural guidance with cURL/Postman, no evidence of structured expert configuration or troubleshooting data. |
| [Use Wellbore DDMS APIs](https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-wellbore-ddms) | 0.30 | Wellbore DDMS API tutorial; summary indicates generic how-to with cURL, not detailed configuration or limits. |
| [About Domain Data Management Services (DDMS)](https://learn.microsoft.com/en-us/azure/energy-data-services/overview-ddms) | 0.20 | Conceptual overview of domain data management services and data magnitude; lacks concrete configuration, limits, or troubleshooting details. |
| [About Microsoft Azure Data Manager for Energy](https://learn.microsoft.com/en-us/azure/energy-data-services/overview-microsoft-energy-data-services) | 0.20 | High-level product overview of Azure Data Manager for Energy; no detailed limits, configs, error codes, or decision matrices. |
| [Create a Microsoft Azure Data Manager for Energy instance](https://learn.microsoft.com/en-us/azure/energy-data-services/quickstart-create-microsoft-energy-data-services-instance) | 0.20 | Quickstart for creating an Azure Data Manager for Energy instance via the portal; primarily step-by-step setup and registration flow without detailed limits, configuration matrices, error-code mappings, or other expert-only reference data. |
| [Domain Data Management Services (DDMS)](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-ddms) | 0.20 | Domain Data Management Services concepts; conceptual platform extension description without concrete configuration, limits, or decision matrices. |
| [Indexing and search](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-index-and-search) | 0.20 | Index and search workflow concepts; high-level description of indexing and metadata accessibility, not detailed configuration or limits. |
| [OSDU® services available on Azure Data Manager for Energy](https://learn.microsoft.com/en-us/azure/energy-data-services/osdu-services-on-adme) | 0.20 | Content is an availability/overview list of OSDU services on Azure Data Manager for Energy tied to a milestone release; it does not describe limits, configuration parameters, error codes, or decision matrices with quantified trade-offs. |
| [Syncing Reference data values](https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-reference-data-values) | 0.20 | Overview of reference data values and synchronization; summary does not show specific configuration parameters, limits, or decision matrices. |
| [Partners](https://learn.microsoft.com/en-us/azure/energy-data-services/resources-partner-solutions) | 0.10 | Partner solutions listing is primarily ecosystem/marketing content; it does not suggest technical configuration, limits, or troubleshooting details, so it does not meet the expert knowledge criteria. |
| [FAQ](https://learn.microsoft.com/en-us/azure/energy-data-services/faq-energy-data-services) | - | FAQ content is primarily conceptual and informational (service description, availability, general usage). It does not focus on numeric limits, detailed configuration parameters, error-code-based troubleshooting, or decision matrices with quantified trade-offs as required by the sub-skill definitions. |
