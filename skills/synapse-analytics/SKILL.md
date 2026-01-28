---
name: synapse-analytics
description: Expert knowledge for Synapse Analytics development including deployment, security, configuration, comparing x vs. y, integrations & coding patterns, troubleshooting, best practices, architecture & design patterns, and limits & quotas. Use when building, debugging, or optimizing Synapse Analytics applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Synapse Analytics Skill

This skill provides expert guidance for Synapse Analytics development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design a modern Azure data warehouse after Netezza migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/7-beyond-data-warehouse-migration |
| Design a modern Azure data warehouse after Teradata migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/7-beyond-data-warehouse-migration |
| Design replicated tables in Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/design-guidance-for-replicated-tables |
| Design hash and round-robin distributed tables | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-distribute |
| Design workload isolation with workload groups | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-workload-isolation |
| Design workload management strategy in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-workload-management |
| Design Synapse SQL tables for dedicated and serverless pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-overview |
| Use Synapse Distribution Advisor for table distribution strategy | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/distribution-advisor |
| Design PolyBase ELT data loading strategy for Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/load-data-overview |

### Best Practices
| Topic | URL |
|-------|-----|
| Optimize design and performance migrating Netezza to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/1-design-performance-migration |
| Plan ETL and data load for Netezza to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/2-etl-load-migration-considerations |
| Implement BI visualization after Netezza to Synapse migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/4-visualization-reporting |
| Reduce SQL compatibility issues migrating Netezza to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/5-minimize-sql-issues |
| Optimize design and performance migrating Oracle to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/oracle/1-design-performance-migration |
| Plan ETL and data load for Oracle to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/oracle/2-etl-load-migration-considerations |
| Implement BI visualization after Oracle to Synapse migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/oracle/4-visualization-reporting |
| Reduce SQL compatibility issues migrating Oracle to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/oracle/5-minimize-sql-issues |
| Optimize design and performance migrating Teradata to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/1-design-performance-migration |
| Plan ETL and data load for Teradata to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/2-etl-load-migration-considerations |
| Implement BI visualization after Teradata to Synapse migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/4-visualization-reporting |
| Reduce SQL compatibility issues migrating Teradata to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/5-minimize-sql-issues |
| Use Apache Spark Advisor recommendations in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/monitoring/apache-spark-advisor |
| Optimize Azure Synapse Spark job performance | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-performance |
| Use Hyperspace indexes to accelerate Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-performance-hyperspace |
| Apply Low Shuffle Merge optimization on Synapse Delta tables | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/low-shuffle-merge-for-apache-spark |
| Use Optimize Write in Synapse Spark for efficient Delta tables | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/optimize-write-for-apache-spark |
| Analyze dedicated SQL pool workload behavior | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/analyze-your-workload |
| Optimize ordered clustered columnstore indexes in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/performance-tuning-ordered-cci |
| Improve Synapse performance with result set caching | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/performance-tuning-result-set-caching |
| Use resource classes for Synapse workload management | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/resource-classes-for-workload-management |
| Apply Azure Advisor recommendations to SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-concept-recommendations |
| Manage and monitor workload importance in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-how-to-manage-and-monitor-workload-importance |
| Optimize and troubleshoot Synapse Gen2 cache usage | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-how-to-monitor-cache |
| Use Azure Stream Analytics with Synapse dedicated SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-integrate-azure-stream-analytics |
| Monitor Synapse dedicated SQL pool with DMVs | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-manage-monitor |
| Use primary, foreign, and unique keys in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-table-constraints |
| Create surrogate keys with IDENTITY in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-identity |
| Indexing strategies for Synapse dedicated SQL tables | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-index |
| Partition tables effectively in Synapse dedicated SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition |
| Implement best practices for Synapse dedicated SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/best-practices-dedicated-sql-pool |
| Follow best practices for Synapse serverless SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/best-practices-serverless-sql-pool |
| Optimize columnstore compression and performance in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-load-columnstore-compression |
| Apply data loading best practices for Synapse dedicated SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-loading-best-practices |
| Apply dynamic SQL patterns in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-dynamic-sql |
| Use query labels effectively in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-label |
| Implement T-SQL loops and cursor alternatives in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-loops |
| Tune Synapse performance using materialized views | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-materialized-view-performance-tuning |
| Develop and optimize stored procedures in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-stored-procedures |
| Choose optimal table data types in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-data-types |
| Create and maintain statistics in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-statistics |
| Optimize transactional performance in Synapse dedicated SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-transaction-best-practices |
| Use transactions correctly in Synapse dedicated SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-transactions |
| Organize objects with user-defined schemas in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-user-defined-schemas |
| Assign and use T-SQL variables in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-variable-assignment |
| Design and use T-SQL views in Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-views |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Synapse data integration features with Azure Data Factory | https://learn.microsoft.com/en-us/azure/synapse-analytics/data-integration/concepts-data-factory-differences |
| Choose query history analysis options in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-history-storage-analysis |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Git source control for Synapse Studio | https://learn.microsoft.com/en-us/azure/synapse-analytics/cicd/source-control |
| Configure SQL pool stored procedure activities in Synapse pipelines | https://learn.microsoft.com/en-us/azure/synapse-analytics/data-integration/sql-pool-stored-procedure-activity |
| Configure SynapseML environment for Azure AI services | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/setup-environment-cognitive-services |
| Reference for Synapse monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/synapse-analytics/monitor-synapse-analytics-reference |
| Use Azure Synapse Runtime for Spark 3.3 components | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-33-runtime |
| Use Azure Synapse Runtime for Spark 3.4 components | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-34-runtime |
| Use Azure Synapse Runtime for Spark 3.5 components | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-35-runtime |
| Manage Apache Spark configuration profiles in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-azure-create-spark-configuration |
| Configure and manage Synapse Spark libraries | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-azure-portal-add-libraries |
| Create custom Conda channels in Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-custom-conda-channel |
| Configure external Hive Metastore for Synapse Spark pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-external-metastore |
| Configure and use GPU-accelerated Spark pools in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-gpu-concept |
| Configure Spark pool libraries in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-manage-pool-packages |
| Configure session-scoped libraries in Synapse notebooks | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-manage-session-packages |
| Manage workspace-level libraries in Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-manage-workspace-packages |
| Configure Apache Spark pool sizes and behaviors in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-pool-configurations |
| Select supported Synapse Spark runtimes and versions | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-version-support |
| Configure maintenance schedules for Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/maintenance-scheduling |
| Configure monitoring of query activity and utilization | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-concept-resource-utilization-query-activity |
| Configure workload importance in Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-how-to-configure-workload-importance |
| Convert resource classes to workload groups in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-how-to-convert-resource-classes-workload-groups |
| Configure Azure Monitor logs for Synapse SQL workloads | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-monitor-workload-portal |
| Configure workload classification in dedicated SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-workload-classification |
| Configure workload importance for Synapse queries | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-workload-importance |
| Monitor workload groups with portal metrics | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-workload-management-portal-monitor |
| Configure storage file access for serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-storage-files-overview |
| Synchronize Spark external tables to serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-storage-files-spark-tables |
| Configure initial Synapse Link connection for Azure SQL Database | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/connect-synapse-link-sql-database |
| Monitor Azure Synapse Link for Azure SQL Database via Studio and Azure Monitor | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/how-to-monitor-synapse-link-sql-database |
| Configure and run Synapse notebook activities in pipelines | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-notebook-activity |

### Deployment
| Topic | URL |
|-------|-----|
| Restore dedicated SQL pools via portal and PowerShell | https://learn.microsoft.com/en-us/azure/synapse-analytics/backuprestore/restore-sql-pool |
| Create user-defined restore points for SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/backuprestore/sqlpool-create-restore-point |
| Implement CI/CD deployment for Synapse workspaces | https://learn.microsoft.com/en-us/azure/synapse-analytics/cicd/continuous-integration-delivery |
| Move Azure Synapse workspaces between regions | https://learn.microsoft.com/en-us/azure/synapse-analytics/how-to-move-workspace-from-one-region-to-another |
| Set up CI/CD for Synapse dedicated SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-continuous-integration-and-deployment |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Ingest ADLS Gen2 data into Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/data-integration/data-integration-sql-pool |
| Analyze arrays and nested schemas with Synapse Spark and SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/how-to-analyze-complex-schema |
| Access Synapse ADLS Gen2 data from Azure Machine Learning | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/access-data-from-aml |
| Link Azure Synapse workspaces with Azure Machine Learning | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/quickstart-integrate-azure-machine-learning |
| Build SynapseML machine learning applications on Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-build-applications-use-mmlspark |
| Use Azure AI Anomaly Detector from Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-cognitive-services-anomaly |
| Integrate Azure AI Language sentiment analysis in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-cognitive-services-sentiment |
| Analyze images using Azure AI Vision in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-computer-vision-use-mmlspark |
| Process documents with Azure AI Document Intelligence in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-form-recognizer-use-mmlspark |
| Run distributed PyTorch training with Horovod on Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-horovod-pytorch |
| Run distributed TensorFlow training with Horovod on Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-horovod-tensorflow |
| Use PREDICT to score ML models in Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-score-model-predict-spark-pool |
| Apply Azure AI Text Analytics with SynapseML | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-text-analytics-use-mmlspark |
| Use Azure AI Translator with SynapseML pipelines | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-translator-use-mmlspark |
| Use Microsoft and third-party tools for Netezza to Synapse migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/6-microsoft-third-party-migration-tools |
| Use Microsoft and third-party tools for Teradata to Synapse migration | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/6-microsoft-third-party-migration-tools |
| Send Synapse Spark logs and metrics to Azure Log Analytics | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-azure-log-analytics |
| Use Delta Lake tables with Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-delta-lake-overview |
| Manage Synapse Spark packages via PowerShell and REST | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-manage-packages-outside-ui |
| Emit Synapse Spark logs and metrics to Event Hubs | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/azure-synapse-diagnostic-emitters-azure-eventhub |
| Emit Synapse Spark logs and metrics to Azure Storage | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/azure-synapse-diagnostic-emitters-azure-storage |
| Integrate Synapse Spark metrics with Prometheus APIs | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/connect-monitor-azure-synapse-spark-application-level-metrics |
| Use Spark CDM connector with Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/data-sources/apache-spark-cdm-connector |
| Move data between Synapse Spark and Azure Data Explorer | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/data-sources/apache-spark-kusto-connector |
| Use Apache Spark connector for Azure SQL and SQL Server | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/data-sources/apache-spark-sql-connector |
| Use MSSparkUtils utilities in Synapse notebooks | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/microsoft-spark-utilities |
| Mount external storage with Synapse file APIs | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/synapse-file-mount-api |
| Move data using Synapse Spark Dedicated SQL connector | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/synapse-spark-sql-pool-import-export |
| Monitor Synapse Spark metrics with Prometheus and Grafana | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/use-prometheus-grafana-to-monitor-apache-spark-application-level-metrics |
| Load Azure Blob data with COPY into Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/load-data-from-azure-blob-storage-using-copy |
| Load WideWorldImportersDW into Synapse via PolyBase | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/load-data-wideworldimportersdw |
| Create tables with CTAS in Synapse dedicated SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-develop-ctas |
| Load Contoso data via PolyBase into Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-load-from-azure-blob-storage-with-polybase |
| Load data from ADLS Gen2 using COPY in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-load-from-azure-data-lake-store |
| Score ONNX machine learning models with T-SQL PREDICT in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-predict |
| Use Synapse SQL connection strings for various client libraries | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/connection-strings |
| Store serverless Synapse SQL query results to storage | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/create-external-table-as-select |
| Create and use native external tables in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/create-use-external-tables |
| Create and use views in serverless Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/create-use-views |
| Query external files with OPENROWSET in serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-openrowset |
| Use CETAS to export data with Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-cetas |
| Configure and use external tables in Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-external-tables |
| Query Cosmos DB analytical store using Synapse serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-cosmos-db-analytical-store |
| Query Azure storage with serverless Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-data-storage |
| Query multiple files and folders with serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-folders-multiple-csv-files |
| Query JSON files using serverless Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-json-files |
| Query Parquet files using serverless Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-parquet-files |
| Query Parquet nested types with serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-parquet-nested-types |
| Query single CSV files using serverless SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-single-csv-file |
| Use file path and name metadata in Synapse SQL queries | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-specific-files |
| Copy Synapse Link Cosmos DB data to Dedicated SQL with Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/how-to-copy-to-sql-pool |
| Query Cosmos DB analytical store with Synapse Spark 2 | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/how-to-query-analytical-store-spark |
| Query Cosmos DB analytical store with Synapse Spark 3 | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/how-to-query-analytical-store-spark-3 |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use Synapse gateway IP addresses by region | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/gateway-ip-addresses |
| Configure autoscale node limits for Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-autoscale |
| Understand Synapse Spark runtime lifecycle and support | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/runtime-for-apache-spark-lifecycle-and-supportability |
| Use backup and restore limits for Synapse dedicated SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/backup-and-restore |
| Review memory and concurrency limits by performance level | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/memory-concurrency-limits |
| Review capacity limits for Synapse dedicated SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-service-capacity-limits |
| Use temporary tables and understand limits in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-tables-temporary |
| Query Delta Lake v1 with serverless Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-delta-lake-format |
| Supported features and limits for Synapse Link for Cosmos DB | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/concept-synapse-link-cosmos-db-support |
| FAQ for Azure Synapse Link for SQL behavior and limits | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/faq |
| Limitations and known issues for Azure Synapse Link for SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/synapse-link-for-sql-known-issues |

### Security
| Topic | URL |
|-------|-----|
| Securely access firewall-protected Purview from Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/catalog-and-governance/how-to-access-secured-purview-account |
| Secure Synapse linked services with private endpoints | https://learn.microsoft.com/en-us/azure/synapse-analytics/data-integration/linked-service |
| Configure access control and governance in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-access-control |
| Set up authentication for Azure Synapse Analytics | https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-authentication |
| Implement data protection controls in Azure Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-data-protection |
| Configure network security for Azure Synapse workspaces | https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-network-security |
| Enable threat detection and auditing in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-threat-protection |
| Access ADLS Gen2 folders with ACLs from Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/how-to-access-container-with-access-control-lists |
| Set up secure prerequisites for Azure AI services in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-configure-cognitive-services-synapse |
| Configure security and operations for Netezza to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/netezza/3-security-access-operations |
| Configure security and operations for Oracle to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/oracle/3-security-access-operations |
| Configure security and operations for Teradata to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/migration-guides/teradata/3-security-access-operations |
| Apply built-in Azure Policy definitions for Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/policy-reference |
| Apply regulatory compliance policies to Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/security-controls-policy |
| Connect Synapse workspace to secure storage accounts | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/connect-to-a-secure-storage-account |
| Manage connectivity settings for Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/connectivity-settings |
| Access Synapse Studio from restricted networks securely | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-connect-to-workspace-from-restricted-network |
| Connect to Synapse workspace via private links | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-connect-to-workspace-with-private-links |
| Create Synapse workspace with data exfiltration protection | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-create-a-workspace-with-data-exfiltration-protection |
| Create Synapse managed private endpoints securely | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-create-managed-private-endpoints |
| Grant Synapse workspace managed identity permissions | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-grant-workspace-managed-identity-permissions |
| Manage Synapse RBAC role assignments in Synapse Studio | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-manage-synapse-rbac-role-assignments |
| Review Synapse RBAC role assignments in Synapse Studio | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-review-synapse-rbac-role-assignments |
| Set up access control for a Synapse workspace | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/how-to-set-up-access-control |
| Secure Synapse Studio access with private link hubs | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-private-link-hubs |
| Configure IP firewall rules for Synapse workspaces | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-ip-firewall |
| Configure Synapse managed private endpoints securely | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-managed-private-endpoints |
| Configure Synapse managed virtual network isolation | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-managed-vnet |
| Understand Synapse workspace RBAC model and scopes | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-synapse-rbac |
| Use built-in Synapse RBAC roles and permissions | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-synapse-rbac-roles |
| Map Synapse tasks to required RBAC roles | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-understand-what-role-you-need |
| Apply conditional access policies to Synapse workspaces | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/workspace-conditional-access |
| Enable Synapse workspace data exfiltration protection | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/workspace-data-exfiltration-protection |
| Configure encryption and key management in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/security/workspaces-encryption |
| Secure Synapse Spark credentials with linked services | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-secure-credentials-with-tokenlibrary |
| Secure Synapse Spark log emission with certificate-based service principals | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/how-to-use-certificate-with-service-principalp-emit-log-event-hubs |
| Implement column-level security in dedicated SQL pool | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/column-level-security |
| Configure secure authentication for Synapse COPY bulk loads | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/quickstart-bulk-load-copy-tsql-examples |
| Configure Microsoft Entra authentication for Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/active-directory-authentication |
| Configure storage access control for serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/develop-storage-files-storage-access-control |
| Use multifactor Entra authentication with Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/mfa-authentication |
| Set access control on shared Spark databases | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/shared-databases-access-control |
| Configure SQL authentication options in Synapse Analytics | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/sql-authentication |
| Access external data with Synapse managed identity | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/tutorial-external-tables-using-managed-identity |
| Secure external data access using Entra ID passthrough | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/tutorial-load-data-using-entra-id |
| Secure Azure Synapse Link for Azure SQL Database with network controls | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/connect-synapse-link-sql-database-vnet |
| Configure secure networking for Synapse Link with SQL Server 2022 | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/connect-synapse-link-sql-server-2022-vnet |
| Use managed identities with Azure Synapse Analytics | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-service-identity |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Recover Synapse workspace after Microsoft Entra tenant move | https://learn.microsoft.com/en-us/azure/synapse-analytics/how-to-recover-workspace-after-tenant-move |
| Known issues and workarounds for Azure Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/known-issues |
| Resolve third-party compatibility issues with Synapse SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/partner/compatibility-issues |
| Interpret and handle Livy job errors in Synapse Spark | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-handle-livy-error |
| Debug Synapse Spark apps with extended history server | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-history-server |
| Troubleshoot Synapse Spark library installation issues | https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-troubleshoot-library-errors |
| Troubleshoot misclassified workloads in Synapse SQL pools | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-how-to-troubleshoot-missed-classification |
| Troubleshoot common serverless SQL pool issues in Synapse | https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/resources-self-help-sql-on-demand |
| Troubleshoot Synapse Link Entra user impersonation issues | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/troubleshoot/troubleshoot-sql-azure-active-directory |
| Troubleshoot Synapse Link for Azure SQL Database after failover | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/troubleshoot/troubleshoot-sql-database-failover |
| Diagnose and fix Azure Synapse Link creation errors for Azure SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/troubleshoot/troubleshoot-sql-link-creation |
| Troubleshoot initial snapshot issues in Synapse Link for SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/synapse-link/troubleshoot/troubleshoot-sql-snapshot-issues |
| Fix UTF-8 text issues in Synapse serverless SQL | https://learn.microsoft.com/en-us/azure/synapse-analytics/troubleshoot/reading-utf8-text |
| Troubleshoot Azure Synapse Studio connectivity issues | https://learn.microsoft.com/en-us/azure/synapse-analytics/troubleshoot/troubleshoot-synapse-studio |
| Fix connectivity between Synapse Studio and storage | https://learn.microsoft.com/en-us/azure/synapse-analytics/troubleshoot/troubleshoot-synapse-studio-and-storage-connectivity |
| Troubleshoot Synapse Studio connectivity using PowerShell | https://learn.microsoft.com/en-us/azure/synapse-analytics/troubleshoot/troubleshoot-synapse-studio-powershell |
| Resolve SDK-created Synapse workspaces that can’t open Studio | https://learn.microsoft.com/en-us/azure/synapse-analytics/troubleshoot/workspaces-created-by-sdk |

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
