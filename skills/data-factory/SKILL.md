---
name: data-factory
description: Expert knowledge for Data Factory development including configuration, limits & quotas, integrations & coding patterns, best practices, security, comparing x vs. y, troubleshooting, architecture & design patterns, and deployment. Use when building, debugging, or optimizing Data Factory applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Data Factory Skill

This skill provides expert guidance for Data Factory development. It combines local quick-reference content with remote documentation fetching capabilities.

## Prerequisites

This skill requires **network access** to fetch remote documentation.

**Option 1: Microsoft Learn MCP Server (Recommended)**
- `mcp_microsoftdocs:microsoft_docs_fetch` - Fetch full page content from URLs

**Option 2: Web Fetch Tool**
- `fetch_webpage` - Fetch content from documentation URLs listed below

If neither option is available, you can still use the URLs in the tables below as references for the user to manually access.

---

## Remote Content Sources (MCP Tools)

When you need the latest official documentation, use `mcp_microsoftdocs:microsoft_docs_fetch` to fetch complete documentation pages:

- **Usage**: `microsoft_docs_fetch({ url: "https://learn.microsoft.com/..." })`

---

## Documentation Links by Category

### Architecture & Design Patterns
| Topic | URL |
|-------|-----|
| Choose the right Integration Runtime architecture | https://learn.microsoft.com/en-us/azure/data-factory/choose-the-right-integration-runtime-configuration |
| Design efficient pipelines using mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance-pipelines |
| Configure BCDR for Azure-SSIS IR with SQL failover groups | https://learn.microsoft.com/en-us/azure/data-factory/configure-bcdr-azure-ssis-integration-runtime |
| Design metadata-driven large-scale copy pipelines | https://learn.microsoft.com/en-us/azure/data-factory/copy-data-tool-metadata-driven |
| Design ADF pipelines to migrate SQL schemas to Cosmos DB | https://learn.microsoft.com/en-us/azure/data-factory/how-to-sqldb-to-cosmosdb |
| Use Azure SQL Managed Instance with Azure-SSIS in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/how-to-use-sql-managed-instance-with-ir |
| Understand architecture of SAP CDC in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-introduction-architecture |
| Plan migration of SSIS workloads to Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/scenario-ssis-migration-overview |
| Bulk copy from Data Lake to Synapse or SQL Database | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-bulk-copy-from-files-to-database |
| Bulk copy from databases to Synapse using control tables | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-bulk-copy-with-control-table |
| Implement delta copy from databases using control tables | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-delta-copy-with-control-table |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply DataOps practices to Azure Data Factory projects | https://learn.microsoft.com/en-us/azure/data-factory/apply-dataops |
| Apply FinOps practices to Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/apply-finops |
| Use automatic connector upgrades in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/automatic-connector-upgrade |
| Use column patterns in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-column-pattern |
| Tune mapping data flow performance in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance |
| Improve sink performance in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance-sinks |
| Optimize source performance in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance-sources |
| Optimize transformation performance in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance-transformations |
| Handle schema drift in Data Factory data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-schema-drift |
| Optimize Azure Data Factory integration runtime performance | https://learn.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime-performance |
| Apply nested activity limitations and best practices | https://learn.microsoft.com/en-us/azure/data-factory/concepts-nested-activities |
| Tune Azure-SSIS Integration Runtime for performance | https://learn.microsoft.com/en-us/azure/data-factory/configure-azure-ssis-integration-runtime-performance |
| Use Connector Upgrade Advisor for Data Factory and Synapse | https://learn.microsoft.com/en-us/azure/data-factory/connector-upgrade-advisor |
| Apply upgrade guidance for Azure Data Factory connectors | https://learn.microsoft.com/en-us/azure/data-factory/connector-upgrade-guidance |
| Optimize Azure Data Factory copy activity performance | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-performance |
| Use ADF copy performance optimization features effectively | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-performance-features |
| Migrate on-premises HDFS data to Azure Storage | https://learn.microsoft.com/en-us/azure/data-factory/data-migration-guidance-hdfs-azure-storage |
| Migrate Netezza data to Azure with Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/data-migration-guidance-netezza-azure-sqldw |
| Migrate Amazon S3 data to Azure Storage with ADF | https://learn.microsoft.com/en-us/azure/data-factory/data-migration-guidance-s3-azure-storage |
| Use data flow snippets to dedupe rows and find nulls | https://learn.microsoft.com/en-us/azure/data-factory/how-to-data-flow-dedupe-nulls-snippets |
| Plan and manage Azure Data Factory costs | https://learn.microsoft.com/en-us/azure/data-factory/plan-manage-costs |
| Apply advanced SAP CDC features and best practices | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-advanced-topics |
| Manage and operate SAP CDC ETL processes in ADF | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-management |
| Apply SSIS-to-ADF migration assessment rules | https://learn.microsoft.com/en-us/azure/data-factory/scenario-ssis-migration-rules |
| Apply data flow best practices for writing to data lake | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-data-flow-write-to-lake |
| Operationalize Azure Data Factory data pipelines | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-operationalize-pipelines |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare ADF pricing across integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/better-understand-different-integration-runtime-charges |
| Evaluate ADF data flow reserved capacity savings | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-reserved-capacity-overview |
| Understand ADF data flow reservation discount application | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-understand-reservation-charges |
| Interpret Azure Data Factory pricing with scenarios | https://learn.microsoft.com/en-us/azure/data-factory/pricing-concepts |
| Price ADF copy plus Databricks transformations | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-copy-transform-azure-databricks |
| Estimate ADF cost for dynamic-parameter transformations | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-copy-transform-dynamic-parameters |
| Estimate ADF Managed VNET data integration costs | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-data-integration-managed-vnet |
| Price SAP ECC delta ingestion via ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-get-delta-data-from-sap-ecc |
| Estimate mapping data flow debug costs in ADF | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-mapping-data-flow-debug-workday |
| Estimate ADF cost for hourly S3-to-Blob copies | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-s3-to-blob |
| Calculate cost to run SSIS on Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-ssis-on-azure-ssis-integration-runtime |
| Price blob transformations using ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/pricing-examples-transform-mapping-data-flows |

### Configuration
| Topic | URL |
|-------|-----|
| Supported Apache Airflow configuration options in ADF | https://learn.microsoft.com/en-us/azure/data-factory/airflow-configurations |
| Define and use global parameters in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/author-global-parameters |
| Configure express VNet injection for Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/azure-ssis-integration-runtime-express-virtual-network-injection |
| Manage SSIS packages with Azure-SSIS IR package store | https://learn.microsoft.com/en-us/azure/data-factory/azure-ssis-integration-runtime-package-store |
| Configure standard VNet injection for Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/azure-ssis-integration-runtime-standard-virtual-network-injection |
| Configure VNet for injected Azure-SSIS integration runtime | https://learn.microsoft.com/en-us/azure/data-factory/azure-ssis-integration-runtime-virtual-network-configuration |
| Built-in and preinstalled components on Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/built-in-preinstalled-components-ssis-integration-runtime |
| Configure compute linked services for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/compute-linked-services |
| Define and use datasets in Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/concepts-datasets-linked-services |
| Configure linked services JSON for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/concepts-linked-services |
| Customize ARM template parameters for Data Factory CI/CD | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-resource-manager-custom-parameters |
| Use Append Variable activity in Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-append-variable-activity |
| Configure Data Flow activity execution in ADF pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-execute-data-flow-activity |
| Configure Execute Pipeline activity for nested pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-execute-pipeline-activity |
| Configure Fail activity to throw custom pipeline errors | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-fail-activity |
| Filter arrays with Filter activity in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-filter-activity |
| Configure ForEach activity for iterative pipeline execution | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-for-each-activity |
| Retrieve dataset metadata with Get Metadata activity | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-get-metadata-activity |
| Control pipeline flow using If Condition activity | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-if-condition-activity |
| Configure Lookup activity in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-lookup-activity |
| Configure and run Power Query activity in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-power-query-activity |
| Configure Set Variable activity in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-set-variable-activity |
| Configure Switch activity for Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-switch-activity |
| Use system variables in ADF and Synapse pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-system-variables |
| Configure Validation activity for Data Factory datasets | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-validation-activity |
| Enable data consistency verification in ADF copy | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-data-consistency |
| Configure fault tolerance and skip rules in ADF copy | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-fault-tolerance |
| Configure session logging for Azure Data Factory copy | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-log |
| Configure Copy activity in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-overview |
| Configure metadata and ACL preservation in ADF copy | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-preserve-metadata |
| Configure schema and data type mapping in ADF copy | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-schema-and-type-mapping |
| Create and configure Airflow environments in ADF | https://learn.microsoft.com/en-us/azure/data-factory/create-airflow-environment |
| Create and configure Azure integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-integration-runtime |
| Provision an Azure-SSIS integration runtime in ADF | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-ssis-integration-runtime |
| Create and configure self-hosted integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/create-self-hosted-integration-runtime |
| Create shared self-hosted integration runtimes via PowerShell | https://learn.microsoft.com/en-us/azure/data-factory/create-shared-self-hosted-integration-runtime-powershell |
| Configure cross-tenant Azure DevOps connections for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/cross-tenant-connections-to-azure-devops |
| Configure Aggregate transformation in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-aggregate |
| Configure Alter row transformation for database updates | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-alter-row |
| Configure Assert transformation for data quality checks | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-assert |
| Configure Cast transformation for column data types | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-cast |
| Configure Conditional split transformation in data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-conditional-split |
| Configure Derived column transformation in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-derived-column |
| Configure Exists transformation for row matching | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-exists |
| Configure Filter transformation to remove rows in data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-filter |
| Configure Flatten transformation for hierarchical data | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-flatten |
| Configure Delete activity in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/delete-activity |
| Configure diagnostic logs and metrics for Workflow Orchestration Manager | https://learn.microsoft.com/en-us/azure/data-factory/diagnostic-logs-and-metrics-for-workflow-orchestration-manager |
| Configure Avro format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-avro |
| Configure binary file format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-binary |
| Use Common Data Model format in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-common-data-model |
| Configure delimited text format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-delimited-text |
| Use Delta Lake format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-delta |
| Configure Excel file format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-excel |
| Configure Iceberg format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-iceberg |
| Configure JSON format in Azure Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/format-json |
| Configure ORC format in Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/format-orc |
| Configure Parquet format in Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/format-parquet |
| Configure XML format in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/format-xml |
| Customize Azure-SSIS Integration Runtime setup | https://learn.microsoft.com/en-us/azure/data-factory/how-to-configure-azure-ssis-ir-custom-setup |
| Configure Enterprise Edition for Azure-SSIS Integration Runtime | https://learn.microsoft.com/en-us/azure/data-factory/how-to-configure-azure-ssis-ir-enterprise-edition |
| Configure SHIR for Azure Log Analytics collection | https://learn.microsoft.com/en-us/azure/data-factory/how-to-configure-shir-for-log-analytics-collection |
| Create storage event-based triggers in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/how-to-create-event-trigger |
| Configure schedule triggers for Azure Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/how-to-create-schedule-trigger |
| Create and configure tumbling window triggers in ADF | https://learn.microsoft.com/en-us/azure/data-factory/how-to-create-tumbling-window-trigger |
| Configure mapping data flows for fixed-width files | https://learn.microsoft.com/en-us/azure/data-factory/how-to-fixed-width |
| Manage Azure Data Factory studio settings | https://learn.microsoft.com/en-us/azure/data-factory/how-to-manage-settings |
| Control ADF studio preview feature settings | https://learn.microsoft.com/en-us/azure/data-factory/how-to-manage-studio-preview-exp |
| Use trigger metadata parameters inside ADF pipelines | https://learn.microsoft.com/en-us/azure/data-factory/how-to-use-trigger-parameterization |
| Plan VNet connectivity for Azure-SSIS integration runtime | https://learn.microsoft.com/en-us/azure/data-factory/join-azure-ssis-integration-runtime-virtual-network |
| Join Azure-SSIS integration runtime to VNet with PowerShell | https://learn.microsoft.com/en-us/azure/data-factory/join-azure-ssis-integration-runtime-virtual-network-powershell |
| Join Azure-SSIS integration runtime to VNet in portal | https://learn.microsoft.com/en-us/azure/data-factory/join-azure-ssis-integration-runtime-virtual-network-ui |
| Reconfigure Azure-SSIS integration runtimes in ADF | https://learn.microsoft.com/en-us/azure/data-factory/manage-azure-ssis-integration-runtime |
| Set up ADF diagnostics and Log Analytics workspace | https://learn.microsoft.com/en-us/azure/data-factory/monitor-configure-diagnostics |
| Configure monitoring and alerts for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/monitor-data-factory |
| Reference monitoring metrics and logs for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/monitor-data-factory-reference |
| Monitor Azure Data Factory integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/monitor-integration-runtime |
| Monitor Azure Data Factory integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/monitor-integration-runtime |
| Configure ADF diagnostic logs via Azure Monitor REST | https://learn.microsoft.com/en-us/azure/data-factory/monitor-logs-rest |
| Monitor managed virtual network integration runtimes | https://learn.microsoft.com/en-us/azure/data-factory/monitor-managed-virtual-network-integration-runtime |
| Monitor SHIR virtual machines with Azure telemetry | https://learn.microsoft.com/en-us/azure/data-factory/monitor-shir-in-azure |
| Visually monitor pipelines in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/monitor-visually |
| Apply Azure Data Factory naming rules for artifacts | https://learn.microsoft.com/en-us/azure/data-factory/naming-rules |
| Parameterize linked services in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/parameterize-linked-services |
| Configure linked service and dataset for SAP CDC | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-prepare-linked-service-source-dataset |
| Configure prerequisites for the SAP CDC connector | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-prerequisites-configuration |
| Set up self-hosted IR for SAP CDC workloads | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-shir-preparation |
| Manage self-hosted IR autoupdate and version lifecycle | https://learn.microsoft.com/en-us/azure/data-factory/self-hosted-integration-runtime-auto-update |
| Configure self-hosted IR as proxy for Azure-SSIS | https://learn.microsoft.com/en-us/azure/data-factory/self-hosted-integration-runtime-proxy-ssis |
| Use ADF template to copy files from multiple containers | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-copy-files-multiple-containers |
| Configure LastModifiedDate-based incremental file copy in ADF | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-copy-new-files-last-modified-date |
| Configure Azure Data Factory file move behavior | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-move-files |
| Configure source control integration for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/source-control |
| Configure supported file formats and compression in ADF copy | https://learn.microsoft.com/en-us/azure/data-factory/supported-file-formats-and-compression-codecs |
| Use legacy supported file formats and compression in ADF | https://learn.microsoft.com/en-us/azure/data-factory/supported-file-formats-and-compression-codecs-legacy |
| Configure dependencies between tumbling window triggers | https://learn.microsoft.com/en-us/azure/data-factory/tumbling-window-trigger-dependency |

### Deployment
| Topic | URL |
|-------|-----|
| Apply CI/CD deployment patterns for Workflow Orchestration Manager | https://learn.microsoft.com/en-us/azure/data-factory/ci-cd-pattern-with-airflow |
| Implement CI/CD for Azure Data Factory across environments | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery |
| Automate Azure Data Factory deployments with Azure Pipelines | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-automate-azure-pipelines |
| Deploy hotfix environments for Azure Data Factory CI/CD | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-hotfix-environment |
| Configure automated publishing for Data Factory CI/CD | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-improvements |
| Use linked ARM templates for large Data Factory deployments | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-linked-templates |
| Manually promote ARM templates across Data Factory environments | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-manual-promotion |
| Run pre- and post-deployment scripts for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/continuous-integration-delivery-sample-script |
| Copy or clone an Azure Data Factory instance | https://learn.microsoft.com/en-us/azure/data-factory/copy-clone-data-factory |
| Deploy and run SSIS packages on Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-ssis-integration-runtime-deploy-packages |
| Create Azure-SSIS integration runtime in portal | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-ssis-integration-runtime-portal |
| Create Azure-SSIS integration runtime with PowerShell | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-ssis-integration-runtime-powershell |
| Deploy Azure-SSIS integration runtime via ARM template | https://learn.microsoft.com/en-us/azure/data-factory/create-azure-ssis-integration-runtime-resource-manager-template |
| Deploy linked ARM templates via Azure DevOps for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/deploy-linked-arm-templates-with-vsts |
| Migrate on-premises SSIS Agent jobs to Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/how-to-migrate-ssis-job-ssms |
| Run self-hosted integration runtime in Windows containers | https://learn.microsoft.com/en-us/azure/data-factory/how-to-run-self-hosted-integration-runtime-in-windows-container |
| Schedule start and stop of Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/how-to-schedule-azure-ssis-integration-runtime |
| Implement BCDR for Azure Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/pipelines-disaster-recovery |
| Automate self-hosted integration runtime installation | https://learn.microsoft.com/en-us/azure/data-factory/self-hosted-integration-runtime-automation-scripts |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Sync GitHub repositories with Workflow Orchestration Manager | https://learn.microsoft.com/en-us/azure/data-factory/airflow-sync-github-repository |
| Use expression builder in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-expression-builder |
| Create and use user-defined functions in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-udf |
| Connect Azure Data Factory to Microsoft Purview | https://learn.microsoft.com/en-us/azure/data-factory/connect-data-factory-to-azure-purview |
| Copy data from AWS Marketplace Web Service using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-marketplace-web-service |
| Copy data from Amazon RDS for Oracle with Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-rds-for-oracle |
| Copy data from Amazon RDS for SQL Server using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-rds-for-sql-server |
| Copy data from Amazon Redshift with Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-redshift |
| Configure Azure Data Factory with S3-compatible storage | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-s3-compatible-storage |
| Copy and transform data in Amazon S3 using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-amazon-simple-storage-service |
| Use Data Flows to transform AppFigures data | https://learn.microsoft.com/en-us/azure/data-factory/connector-appfigures |
| Use Data Flows to transform Asana data | https://learn.microsoft.com/en-us/azure/data-factory/connector-asana |
| Connect Azure Data Factory to Azure Blob Storage | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-blob-storage |
| Transform data in Azure Cosmos DB analytical store | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-cosmos-analytical-store |
| Copy and transform data in Azure Cosmos DB for NoSQL | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-cosmos-db |
| Copy data with Azure Cosmos DB for MongoDB connector | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-cosmos-db-mongodb-api |
| Copy and transform data in Azure Data Explorer with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-data-explorer |
| Copy and transform data in Azure Data Lake Storage Gen2 | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-data-lake-storage |
| Copy data to and from Azure Data Lake Storage Gen1 | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-data-lake-store |
| Copy data from Azure Database for MariaDB with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-database-for-mariadb |
| Copy and transform data in Azure Database for MySQL | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-database-for-mysql |
| Copy and transform data in Azure Database for PostgreSQL | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-database-for-postgresql |
| Copy data to and from Azure Databricks Delta Lake | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-databricks-delta-lake |
| Copy data to and from Azure Files with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-file-storage |
| Copy data into Azure AI Search indexes with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-search |
| Copy and transform data in Azure Synapse Analytics with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-sql-data-warehouse |
| Copy and transform data in Azure SQL Database with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-sql-database |
| Copy and transform data in Azure SQL Managed Instance | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-sql-managed-instance |
| Configure Azure Table Storage connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-azure-table-storage |
| Set up Cassandra connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-cassandra |
| Configure Concur connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-concur |
| Configure Couchbase connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-couchbase |
| Transform data in data.world using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-dataworld |
| Set up DB2 connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-db2 |
| Configure Drill connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-drill |
| Set up Dynamics AX connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-dynamics-ax |
| Copy and transform Dynamics 365/Dataverse data in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-dynamics-crm-office-365 |
| Copy data to and from file systems in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-file-system |
| Copy data from FTP servers using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-ftp |
| Use GitHub connector for Common Data Model in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-github |
| Configure Google Ads connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-google-adwords |
| Set up Google BigQuery V2 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-google-bigquery |
| Use legacy Google BigQuery V1 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-google-bigquery-legacy |
| Configure Azure Data Factory Google Cloud Storage connector | https://learn.microsoft.com/en-us/azure/data-factory/connector-google-cloud-storage |
| Use Azure Data Factory to transform data in Google Sheets | https://learn.microsoft.com/en-us/azure/data-factory/connector-google-sheets |
| Connect Azure Data Factory to Greenplum for copy | https://learn.microsoft.com/en-us/azure/data-factory/connector-greenplum |
| Configure Azure Data Factory HBase connector | https://learn.microsoft.com/en-us/azure/data-factory/connector-hbase |
| Copy data from HDFS using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-hdfs |
| Connect Azure Data Factory to Hive for copy | https://learn.microsoft.com/en-us/azure/data-factory/connector-hive |
| Configure HTTP connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-http |
| Copy data from HubSpot with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-hubspot |
| Connect Azure Data Factory to Impala for copy | https://learn.microsoft.com/en-us/azure/data-factory/connector-impala |
| Copy data to and from IBM Informix in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-informix |
| Copy data from Jira using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-jira |
| Copy data from Magento with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-magento |
| Connect Azure Data Factory to MariaDB for copy | https://learn.microsoft.com/en-us/azure/data-factory/connector-mariadb |
| Copy data from Marketo using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-marketo |
| Copy data to and from Microsoft Access in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-microsoft-access |
| Copy and transform data in Microsoft Fabric Lakehouse via ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-microsoft-fabric-lakehouse |
| Copy and transform data in Microsoft Fabric Warehouse via ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-microsoft-fabric-warehouse |
| Configure Azure Data Factory MongoDB connector | https://learn.microsoft.com/en-us/azure/data-factory/connector-mongodb |
| Configure MongoDB Atlas connector for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-mongodb-atlas |
| Use legacy MongoDB connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-mongodb-legacy |
| Set up MySQL connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-mysql |
| Configure Netezza connector for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-netezza |
| Use OData connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-odata |
| Connect ODBC data stores with Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-odbc |
| Integrate Microsoft 365 data with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-office-365 |
| Configure Oracle connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-oracle |
| Copy from Oracle Cloud Storage using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-oracle-cloud-storage |
| Use Oracle Eloqua connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-oracle-eloqua |
| Use Oracle Responsys connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-oracle-responsys |
| Use Oracle Service Cloud connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-oracle-service-cloud |
| Use PayPal connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-paypal |
| Copy data from Phoenix using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-phoenix |
| Configure PostgreSQL V2 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-postgresql |
| Use PostgreSQL V1 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-postgresql-legacy |
| Copy data from Presto with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-presto |
| Transform Quickbase data using Data Factory data flows | https://learn.microsoft.com/en-us/azure/data-factory/connector-quickbase |
| Configure Azure Data Factory QuickBooks Online connector | https://learn.microsoft.com/en-us/azure/data-factory/connector-quickbooks |
| Configure REST connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-rest |
| Use Salesforce V2 connector with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-salesforce |
| Use Salesforce V1 connector with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-salesforce-legacy |
| Use Salesforce Marketing Cloud connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-salesforce-marketing-cloud |
| Configure Salesforce Service Cloud V2 connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-salesforce-service-cloud |
| Configure Salesforce Service Cloud V1 connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-salesforce-service-cloud-legacy |
| Copy from SAP BW using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-business-warehouse |
| Copy from SAP BW via Open Hub using ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-business-warehouse-open-hub |
| Transform SAP ODP data via SAP CDC connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-change-data-capture |
| Configure SAP Cloud for Customer connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-cloud-for-customer |
| Copy from SAP ECC using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-ecc |
| Copy from SAP HANA using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-hana |
| Copy from SAP table using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sap-table |
| Copy from ServiceNow V2 using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-servicenow |
| Copy from ServiceNow V1 using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-servicenow-legacy |
| Use SFTP connector for copy and transform in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-sftp |
| Copy from SharePoint Online List using ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-sharepoint-online-list |
| Copy from Shopify using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-shopify |
| Transform Smartsheet data with ADF data flows | https://learn.microsoft.com/en-us/azure/data-factory/connector-smartsheet |
| Configure Snowflake V2 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-snowflake |
| Configure Snowflake V1 connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-snowflake-legacy |
| Use Spark connector with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-spark |
| Connect SQL Server to Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sql-server |
| Configure Square connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-square |
| Copy data from Sybase using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-sybase |
| Transform TeamDesk data with ADF Data Flows | https://learn.microsoft.com/en-us/azure/data-factory/connector-teamdesk |
| Copy data from Teradata Vantage with ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-teradata |
| Transform Twilio data using ADF Data Flows | https://learn.microsoft.com/en-us/azure/data-factory/connector-twilio |
| Copy data from Vertica with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-vertica |
| Use Web Table connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-web-table |
| Copy data from Xero using Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-xero |
| Transform Zendesk data with ADF Data Flows | https://learn.microsoft.com/en-us/azure/data-factory/connector-zendesk |
| Copy data from Zoho using Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-zoho |
| Integrate Azure Functions with ADF pipelines via activity | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-azure-function-activity |
| Use expressions and functions in ADF and Synapse pipelines | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-expression-language-functions |
| Invoke REST endpoints with Web activity in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-web-activity |
| Control pipelines using Webhook activity callbacks | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-webhook-activity |
| Use aggregate functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-aggregate-functions |
| Use array functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-array-functions |
| Use cached lookup functions in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-cached-lookup-functions |
| Use conversion functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-conversion-functions |
| Use date and time functions in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-date-time-functions |
| Use expression functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-expression-functions |
| Reference for all mapping data flow expression functions | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-expressions-usage |
| Call external endpoints with External call transformation | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-external-call |
| Use flowlet transformations in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-flowlet |
| Configure join transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-join |
| Configure lookup transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-lookup |
| Use map functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-map-functions |
| Use metafunctions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-metafunctions |
| Use multiple branches in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-new-branch |
| Configure parse transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-parse |
| Configure pivot transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-pivot |
| Use rank transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-rank |
| Author and interpret Azure Data Factory data flow script | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-script |
| Configure select transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-select |
| Configure sink transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-sink |
| Configure sort transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-sort |
| Configure source transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-source |
| Use stringify transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-stringify |
| Configure surrogate key transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-surrogate-key |
| Configure union transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-union |
| Configure unpivot transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-unpivot |
| Configure window transformations in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-window |
| Use window functions in Azure mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-window-functions |
| Apply data transformation functions in mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-transformation-functions |
| Implement Bring Your Own Driver connectors in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/guidance-for-byod-approach |
| Capture changed data from ADLS Gen2 to Azure SQL with CDC | https://learn.microsoft.com/en-us/azure/data-factory/how-to-change-data-capture-resource |
| Capture changed data with schema evolution to Delta using CDC | https://learn.microsoft.com/en-us/azure/data-factory/how-to-change-data-capture-resource-with-schema-evolution |
| Automate SSISDB log cleanup using ADF and Elastic Jobs | https://learn.microsoft.com/en-us/azure/data-factory/how-to-clean-up-ssisdb-logs-with-elastic-jobs |
| Trigger ADF pipelines from custom Event Grid events | https://learn.microsoft.com/en-us/azure/data-factory/how-to-create-custom-event-trigger |
| Develop and install licensed SSIS components on Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/how-to-develop-azure-ssis-ir-licensed-components |
| Discover and explore Purview-governed data in ADF | https://learn.microsoft.com/en-us/azure/data-factory/how-to-discover-explore-purview-data |
| Use ADF expression language for parameters | https://learn.microsoft.com/en-us/azure/data-factory/how-to-expression-language-functions |
| Configure ADF Fabric Lakehouse connector for data ingest | https://learn.microsoft.com/en-us/azure/data-factory/how-to-ingest-data-into-fabric-from-azure-data-factory |
| Run SSIS packages with Azure-enabled dtexec | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-azure-enabled-dtexec |
| Run SSIS packages via Azure SQL MI Agent | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-managed-instance-agent |
| Execute Azure-enabled SSIS packages from SSDT | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-ssdt |
| Use Execute SSIS Package activity in portal | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-ssis-activity |
| Run Execute SSIS Package activity with PowerShell | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-ssis-activity-powershell |
| Run SSIS packages via Stored Procedure activity | https://learn.microsoft.com/en-us/azure/data-factory/how-to-invoke-ssis-package-stored-procedure-activity |
| Send email notifications from ADF and Synapse pipelines | https://learn.microsoft.com/en-us/azure/data-factory/how-to-send-email |
| Configure ADF copy into Azure Data Lake Storage Gen2 | https://learn.microsoft.com/en-us/azure/data-factory/load-azure-data-lake-storage-gen2 |
| Copy data between ADLS Gen1 and Gen2 using ADF | https://learn.microsoft.com/en-us/azure/data-factory/load-azure-data-lake-storage-gen2-from-gen1 |
| Configure ADF copy into Azure Data Lake Storage Gen1 | https://learn.microsoft.com/en-us/azure/data-factory/load-azure-data-lake-store |
| Programmatically monitor Azure Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/monitor-programmatically |
| Create Azure Data Factory pipelines using .NET SDK | https://learn.microsoft.com/en-us/azure/data-factory/quickstart-create-data-factory-dot-net |
| Create Azure Data Factory with Python SDK | https://learn.microsoft.com/en-us/azure/data-factory/quickstart-create-data-factory-python |
| Use Azure Data Factory REST API to build pipelines | https://learn.microsoft.com/en-us/azure/data-factory/quickstart-create-data-factory-rest-api |
| Use REST APIs for Workflow Orchestration Manager runtime | https://learn.microsoft.com/en-us/azure/data-factory/rest-apis-for-airflow-integrated-runtime |
| Use Azure PowerShell scripts to manage Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/samples-powershell |
| Process Azure AutoML model outputs with ADF data flows | https://learn.microsoft.com/en-us/azure/data-factory/scenario-dataflow-process-data-aml-models |
| Extract structured data from PDFs with ADF and Document Intelligence | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-extract-data-from-pdf |
| Replicate multiple SAP ODP objects via SAP CDC in ADF | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-replicate-multiple-objects-sap-cdc |
| Access on-premises and Azure files from SSIS in ADF | https://learn.microsoft.com/en-us/azure/data-factory/ssis-azure-files-file-shares |
| Run Databricks JAR jobs from Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-databricks-jar |
| Run Databricks jobs via Azure Data Factory activity | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-databricks-job |
| Execute Databricks notebooks from Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-databricks-notebook |
| Run Databricks Python scripts using ADF pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-databricks-python |
| Execute Azure Machine Learning pipelines from Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-machine-learning-service |
| Run Synapse notebooks from Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-synapse-notebook |
| Execute Synapse Spark job definitions via Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-synapse-spark-job-definition |
| Implement custom .NET activities in Azure Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-custom-activity |
| Run U-SQL scripts on Data Lake Analytics via ADF | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-data-lake-analytics |
| Run Hive queries via Data Factory HDInsight activity | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-hadoop-hive |
| Invoke Hadoop MapReduce from Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-hadoop-map-reduce |
| Execute Pig scripts using Data Factory HDInsight activity | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-hadoop-pig |
| Use Hadoop Streaming activity in Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-hadoop-streaming |
| Create predictive pipelines with ML Studio (classic) activity | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-machine-learning |
| Transform data using Script activity in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-script |
| Run Spark programs on HDInsight from Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-spark |
| Call SQL stored procedures from Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-factory/transform-data-using-stored-procedure |
| Implement ADF .NET pipeline from Blob to Azure SQL | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-copy-data-dot-net |
| Use PowerShell to configure ADF hybrid copy | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-hybrid-copy-powershell |
| Update ML Studio (classic) models via Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/update-machine-learning-models |
| Use data wrangling functions in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/wrangling-functions |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand Workflow Orchestration Manager pricing and units | https://learn.microsoft.com/en-us/azure/data-factory/airflow-pricing |
| Understand connector release stages and timelines in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-release-stages-and-timelines |
| Configure and limit Until activity loops in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-until-activity |
| Configure Wait activity duration and limits in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/control-flow-wait-activity |

### Security
| Topic | URL |
|-------|-----|
| Allow ADF Azure IR IP ranges in firewalls | https://learn.microsoft.com/en-us/azure/data-factory/azure-integration-runtime-ip-addresses |
| Configure roles and permissions for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/concepts-roles-permissions |
| Control ADF outbound FQDNs with Azure Policy | https://learn.microsoft.com/en-us/azure/data-factory/configure-outbound-allow-list-azure-policy |
| Use Azure credentials securely in ADF | https://learn.microsoft.com/en-us/azure/data-factory/credentials |
| Choose secure data access strategies in ADF | https://learn.microsoft.com/en-us/azure/data-factory/data-access-strategies |
| Configure Azure Private Link for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/data-factory-private-link |
| Configure managed identities for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/data-factory-service-identity |
| Enable Microsoft Entra auth for Azure-SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/enable-aad-authentication-azure-ssis-ir |
| Enable Azure Key Vault secrets for ADF Airflow | https://learn.microsoft.com/en-us/azure/data-factory/enable-azure-key-vault |
| Enable customer-managed keys for ADF encryption | https://learn.microsoft.com/en-us/azure/data-factory/enable-customer-managed-key |
| Encrypt on-premises credentials for ADF SHIR | https://learn.microsoft.com/en-us/azure/data-factory/encrypt-credentials-self-hosted-integration-runtime |
| Access firewall-protected Microsoft Purview from Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/how-to-access-secured-purview-account |
| Use Key Vault secrets in ADF activities | https://learn.microsoft.com/en-us/azure/data-factory/how-to-use-azure-key-vault-secrets-pipeline-activities |
| Configure Kubernetes secret for private registry images | https://learn.microsoft.com/en-us/azure/data-factory/kubernetes-secret-pull-image-from-private-container-registry |
| Use managed VNet and private endpoints in ADF | https://learn.microsoft.com/en-us/azure/data-factory/managed-virtual-network-private-endpoint |
| Use built-in Azure Policy definitions for Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/policy-reference |
| Secure Azure Data Factory with network and identity controls | https://learn.microsoft.com/en-us/azure/data-factory/secure-your-azure-data-factory |
| Detect and mask PII data in ADF using Azure AI | https://learn.microsoft.com/en-us/azure/data-factory/solution-template-pii-detection-and-masking |
| Use Windows authentication from Azure-SSIS packages | https://learn.microsoft.com/en-us/azure/data-factory/ssis-azure-connect-with-windows-auth |
| Store ADF linked service secrets in Key Vault | https://learn.microsoft.com/en-us/azure/data-factory/store-credentials-in-key-vault |
| Secure self-hosted integration runtime with TLS/SSL for intranet access | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-enable-remote-access-intranet-tls-ssl-certificate |
| Secure on-premises SQL access via Data Factory managed VNet | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-managed-virtual-network-on-premise-sql-server |
| Configure private endpoint access to SQL Managed Instance from Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-managed-virtual-network-sql-managed-instance |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Diagnose Azure Data Factory CDC resource issues | https://learn.microsoft.com/en-us/azure/data-factory/change-data-capture-troubleshoot |
| Resolve CI/CD, Azure DevOps, and GitHub issues for Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/ci-cd-github-troubleshoot-guide |
| Resolve common issues in Data Factory connector upgrades | https://learn.microsoft.com/en-us/azure/data-factory/connector-deprecation-frequently-asked-questions |
| Fix Azure Data Factory Amazon S3 connector errors | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-amazon-simple-storage-service |
| Resolve Azure Blob Storage connector issues in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-blob-storage |
| Troubleshoot Azure Cosmos DB connectors in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-cosmos-db |
| Diagnose Azure Data Explorer connector problems | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-data-explorer |
| Resolve Azure Data Lake Storage connector errors | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-data-lake |
| Troubleshoot Azure Files connector in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-files |
| Fix Azure Table Storage connector failures | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-azure-table-storage |
| Troubleshoot DB2 connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-db2 |
| Resolve delimited text format connector issues | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-delimited-text |
| Fix Dynamics 365 and Dataverse connector problems | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-dynamics-dataverse |
| Troubleshoot file system connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-file-system |
| Resolve FTP, SFTP, and HTTP connector errors | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-ftp-sftp-http |
| Fix Google Ads connector issues in Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-google-ads |
| Troubleshoot Azure Data Factory connector failures | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-guide |
| Troubleshoot Hive connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-hive |
| Resolve Microsoft Fabric Lakehouse connector errors | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-microsoft-fabric-lakehouse |
| Troubleshoot Microsoft Fabric Warehouse connector in ADF | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-microsoft-fabric-warehouse |
| Diagnose and fix Azure Data Factory MongoDB connector issues | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-mongodb |
| Resolve Azure Data Factory Oracle connector problems | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-oracle |
| Fix ORC format connector errors in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-orc |
| Troubleshoot Parquet format connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-parquet |
| Fix Azure Database for PostgreSQL connector issues | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-postgresql |
| Diagnose REST connector failures in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-rest |
| Troubleshoot Salesforce connectors in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-salesforce |
| Resolve SAP connector issues in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-sap |
| Fix ServiceNow connector problems in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-servicenow |
| Troubleshoot SharePoint Online list connector in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-sharepoint-online-list |
| Resolve Snowflake connector issues in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-snowflake |
| Resolve SQL-based connectors issues in ADF and Synapse | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-synapse-sql |
| Troubleshoot Teradata connector failures in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-teradata |
| Fix XML format connector issues in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/connector-troubleshoot-xml |
| Troubleshoot Azure Data Factory copy performance issues | https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-performance-troubleshooting |
| Troubleshoot ADF and Synapse external control activities | https://learn.microsoft.com/en-us/azure/data-factory/data-factory-troubleshoot-guide |
| Troubleshoot Azure Data Factory Studio issues | https://learn.microsoft.com/en-us/azure/data-factory/data-factory-ux-troubleshoot-guide |
| Troubleshoot connector and format problems in ADF mapping data flows | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-troubleshoot-connector-format |
| Diagnose mapping data flow issues in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/data-flow-troubleshoot-guide |
| Handle SQL truncation and error rows in ADF data flows | https://learn.microsoft.com/en-us/azure/data-factory/how-to-data-flow-error-rows |
| Resolve known Azure Data Factory issues and workarounds | https://learn.microsoft.com/en-us/azure/data-factory/known-issues-troubleshoot-guide |
| Monitor Azure-SSIS operations with Azure Monitor | https://learn.microsoft.com/en-us/azure/data-factory/monitor-ssis |
| Troubleshoot pipeline runs and triggers in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/pipeline-trigger-troubleshoot-guide |
| Debug SAP CDC connector issues using SHIR logs | https://learn.microsoft.com/en-us/azure/data-factory/sap-change-data-capture-debug-shir-logs |
| Troubleshoot security and access control in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/security-and-access-control-troubleshoot-guide |
| Use the self-hosted IR diagnostic tool for issues | https://learn.microsoft.com/en-us/azure/data-factory/self-hosted-integration-runtime-diagnostic-tool |
| Fix self-hosted integration runtime issues in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/self-hosted-integration-runtime-troubleshoot-guide |
| Diagnose SSIS integration runtime connectivity issues | https://learn.microsoft.com/en-us/azure/data-factory/ssis-integration-runtime-diagnose-connectivity-faq |
| Troubleshoot SSIS Integration Runtime management in Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-factory/ssis-integration-runtime-management-troubleshoot |
| Resolve SSIS package execution errors in Azure SSIS IR | https://learn.microsoft.com/en-us/azure/data-factory/ssis-integration-runtime-ssis-activity-faq |
| Understand pipeline failure status and error messages | https://learn.microsoft.com/en-us/azure/data-factory/tutorial-pipeline-failure-error-handling |

---

## How to Use This Skill

### Option 1: Using MCP Tool (Recommended)

Use `mcp_microsoftdocs:microsoft_docs_fetch` to retrieve full documentation:
```
microsoft_docs_fetch({ url: "https://learn.microsoft.com/en-us/azure/azure-functions/functions-deployment-technologies" })
```

### Option 2: Using fetch_webpage Tool

If MCP tools are not available, use `fetch_webpage` to retrieve documentation:
```
fetch_webpage({ 
  urls: ["https://learn.microsoft.com/en-us/azure/azure-functions/functions-deployment-technologies"],
  query: "deployment options"
})
```

### Option 3: Manual Reference

If no network tools are available, provide the URLs from the tables above for the user to access directly.
