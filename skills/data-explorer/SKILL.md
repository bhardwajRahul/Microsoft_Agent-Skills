---
name: data-explorer
description: Expert knowledge for Data Explorer development including configuration, integrations & coding patterns, limits & quotas, deployment, best practices, architecture & design patterns, security, troubleshooting, and comparing x vs. y. Use when building, debugging, or optimizing Data Explorer applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Data Explorer Skill

This skill provides expert guidance for Data Explorer development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design and implement DR solutions for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/business-continuity-create-solution |
| Plan Azure Data Explorer business continuity and DR | https://learn.microsoft.com/en-us/azure/data-explorer/business-continuity-overview |
| Use follower databases for cross-cluster querying in Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/follower |
| Choose and configure streaming ingestion for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-streaming |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply Azure Advisor recommendations to optimize ADX clusters | https://learn.microsoft.com/en-us/azure/data-explorer/azure-advisor |
| Monitor Azure Data Explorer cluster health metrics | https://learn.microsoft.com/en-us/azure/data-explorer/check-cluster-health |
| Purge and delete personal data in Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/data-purge-portal |
| Handle duplicate ingestion in Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/dealing-with-duplicates |
| Optimize Azure Data Explorer clusters for high concurrency | https://learn.microsoft.com/en-us/azure/data-explorer/high-concurrency |
| Use hot windows to query cold data efficiently | https://learn.microsoft.com/en-us/azure/data-explorer/hot-windows |
| Handle invalid data during Azure Data Explorer ingestion | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-invalid-data |
| Ingest JSON into Azure Data Explorer with KQL, C#, and Python | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-json-formats |
| Monitor queued ingestion metrics in Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/monitor-queued-ingestion |
| Apply Power BI best practices for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/power-bi-best-practices |
| Configure Azure Data Explorer pricing with the cost calculator | https://learn.microsoft.com/en-us/azure/data-explorer/pricing-calculator |
| Optimize Azure Data Explorer cost per GB ingested | https://learn.microsoft.com/en-us/azure/data-explorer/pricing-cost-drivers |
| Optimize Azure Data Explorer table schema for performance | https://learn.microsoft.com/en-us/azure/data-explorer/schema-best-practice |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure Data Explorer multi-tenant architectures | https://learn.microsoft.com/en-us/azure/data-explorer/multi-tenant |
| Understand how Azure Data Explorer reservation discounts are applied | https://learn.microsoft.com/en-us/azure/data-explorer/pricing-reservation-discount |
| Purchase Azure Data Explorer reserved capacity for markup savings | https://learn.microsoft.com/en-us/azure/data-explorer/pricing-reserved-capacity |

### Configuration
| Topic | URL |
|-------|-----|
| Configure multiple cluster connections in Azure Data Explorer web UI | https://learn.microsoft.com/en-us/azure/data-explorer/add-cluster-connection |
| Clone Azure Data Explorer database schemas with commands | https://learn.microsoft.com/en-us/azure/data-explorer/clone-database-schema |
| Configure ADX databases using KQL scripts in ARM | https://learn.microsoft.com/en-us/azure/data-explorer/database-script |
| Install and run Azure Data Explorer Kusto emulator | https://learn.microsoft.com/en-us/azure/data-explorer/kusto-emulator-install |
| Configure language extension plugins in ADX clusters | https://learn.microsoft.com/en-us/azure/data-explorer/language-extensions |
| Reference monitoring metrics and logs for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/monitor-data-explorer-reference |
| Customize Azure Data Explorer web UI environment settings | https://learn.microsoft.com/en-us/azure/data-explorer/web-customize-settings |
| Sync Azure Data Explorer web UI profile across devices | https://learn.microsoft.com/en-us/azure/data-explorer/web-sync |

### Deployment
| Topic | URL |
|-------|-----|
| Automate provisioning of Azure Data Explorer environments | https://learn.microsoft.com/en-us/azure/data-explorer/automated-deploy-overview |
| Deploy Azure Data Explorer with confidential compute SKUs | https://learn.microsoft.com/en-us/azure/data-explorer/confidential-compute |
| Select isolated compute SKUs for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/isolated-compute |
| Migrate VNet-injected Azure Data Explorer clusters to private endpoints | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-migrate-vnet-to-private-endpoint |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Add Azure Data Explorer cluster principals via SDKs | https://learn.microsoft.com/en-us/azure/data-explorer/add-cluster-principal |
| Add Azure Data Explorer database principals via SDKs | https://learn.microsoft.com/en-us/azure/data-explorer/add-database-principal |
| Send logs to Data Explorer using Apache Log4J 2 sink | https://learn.microsoft.com/en-us/azure/data-explorer/apache-log4j2-connector |
| Run Azure Data Explorer management with Az.Kusto PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/data-explorer/azure-powershell |
| Connect common SQL tools to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/connect-common-apps |
| Configure JDBC connectivity to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/connect-jdbc |
| Configure ODBC connections to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/connect-odbc |
| Create Azure Data Explorer clusters via SDKs and CLI | https://learn.microsoft.com/en-us/azure/data-explorer/create-cluster-database |
| Configure Azure Data Explorer IoT Hub data connection | https://learn.microsoft.com/en-us/azure/data-explorer/create-iot-hub-connection |
| Create IoT Hub data connection using Kusto SDKs | https://learn.microsoft.com/en-us/azure/data-explorer/create-iot-hub-connection-sdk |
| Run Azure Data Explorer commands from Data Factory pipelines | https://learn.microsoft.com/en-us/azure/data-explorer/data-factory-command-activity |
| Integrate Azure Data Explorer with Azure Data Factory | https://learn.microsoft.com/en-us/azure/data-explorer/data-factory-integration |
| Copy data from Data Factory into Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/data-factory-load-data |
| Bulk copy from databases to Data Explorer using ADF template | https://learn.microsoft.com/en-us/azure/data-explorer/data-factory-template |
| Query Azure Data Lake Storage from Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/data-lake-query-data |
| Integrate Azure Data Share with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/data-share |
| Create ADX database and table policies programmatically | https://learn.microsoft.com/en-us/azure/data-explorer/database-table-policies |
| Query Azure Storage external tables with KQL | https://learn.microsoft.com/en-us/azure/data-explorer/external-azure-storage-tables-query |
| Use Azure Data Explorer connector in Power Automate | https://learn.microsoft.com/en-us/azure/data-explorer/flow |
| Automate Kusto queries with Power Automate examples | https://learn.microsoft.com/en-us/azure/data-explorer/flow-usage |
| Configure Fluent Bit output to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/fluent-bit |
| Configure Grafana integration for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/grafana |
| Set up Cosmos DB change feed ingestion to Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-cosmos-db-connection |
| Ingest machine data from Cribl Stream into Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-cribl |
| Use Apache Flink connector to ingest into Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-flink |
| Send logs from Fluentd to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-fluentd |
| Configure Kafka Connect sink to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-kafka |
| Ingest data from Logstash into Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-logstash |
| Connect Splunk Enterprise to Azure Data Explorer for ingestion | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-splunk |
| Ingest data from Splunk Universal Forwarder into Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-splunk-uf |
| Configure Telegraf output plugin for Azure Data Explorer ingestion | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-telegraf |
| Integrate Azure Functions bindings with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/integrate-azure-functions |
| Connect MCP servers to Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/integrate-mcp-servers |
| Configure K2Bridge to use Kibana with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/k2bridge |
| Use Kqlmagic in Jupyter Notebooks with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/kqlmagic |
| Configure Azure Data Explorer as a SQL Server linked server | https://learn.microsoft.com/en-us/azure/data-explorer/linked-server |
| Integrate Azure Data Explorer with Logic Apps | https://learn.microsoft.com/en-us/azure/data-explorer/logic-apps |
| Migrate Elasticsearch data to Azure Data Explorer with Logstash | https://learn.microsoft.com/en-us/azure/data-explorer/migrate-elasticsearch-to-azure-data-explorer |
| Use NLog sink to send .NET logs to Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/nlog-sink |
| Configure OpenTelemetry Collector sink to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/open-telemetry-connector |
| Use Power Apps connector with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/power-apps-connector |
| Integrate Azure Data Explorer with Microsoft Purview governance | https://learn.microsoft.com/en-us/azure/data-explorer/purview |
| Query Azure Data Explorer using Python client library | https://learn.microsoft.com/en-us/azure/data-explorer/python-query-data |
| Query Azure Data Explorer clusters from MATLAB | https://learn.microsoft.com/en-us/azure/data-explorer/query-matlab |
| Run cross-service queries with Azure Monitor data | https://learn.microsoft.com/en-us/azure/data-explorer/query-monitor-data |
| Use Redash native connector with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/redash |
| Generate sample ingestion and query apps for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/sample-app-generator-wizard |
| Use Serilog sink to ingest logs into Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/serilog-sink |
| Set up Sisense integration with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/sisense |
| Use Azure Data Explorer Spark connector for data movement | https://learn.microsoft.com/en-us/azure/data-explorer/spark-connector |
| Run KQL and stored functions over TDS clients | https://learn.microsoft.com/en-us/azure/data-explorer/sql-kql-queries-and-stored-functions |
| Connect to Azure Data Explorer via SQL Server emulation | https://learn.microsoft.com/en-us/azure/data-explorer/sql-server-emulation-overview |
| Ingest streaming data from Azure Stream Analytics to Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/stream-analytics-connector |
| Connect Azure Data Explorer to Tableau via ODBC | https://learn.microsoft.com/en-us/azure/data-explorer/tableau |
| Debug KQL inline Python code with VS Code | https://learn.microsoft.com/en-us/kusto/debug-inline-python?view=microsoft-fabric |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use automatic stop limits for inactive ADX clusters | https://learn.microsoft.com/en-us/azure/data-explorer/auto-stop-clusters |
| Configure Event Grid data connections and file size limits | https://learn.microsoft.com/en-us/azure/data-explorer/create-event-grid-connection |
| Delete and recover Azure Data Explorer clusters safely | https://learn.microsoft.com/en-us/azure/data-explorer/delete-cluster |
| Supported data and compression formats for Azure Data Explorer ingestion | https://learn.microsoft.com/en-us/azure/data-explorer/ingestion-supported-formats |
| Migrate ADX clusters to multi-zone availability | https://learn.microsoft.com/en-us/azure/data-explorer/migrate-cluster-to-multiple-availability-zone |
| Use Azure Data Explorer free cluster limits effectively | https://learn.microsoft.com/en-us/azure/data-explorer/start-for-free |
| Upgrade free Azure Data Explorer clusters to full | https://learn.microsoft.com/en-us/azure/data-explorer/start-for-free-upgrade |

### Security
| Topic | URL |
|-------|-----|
| Enable disk encryption for Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/cluster-encryption-disk |
| Enable double encryption for Azure Data Explorer storage | https://learn.microsoft.com/en-us/azure/data-explorer/cluster-encryption-double |
| Configure encryption options for Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/cluster-encryption-overview |
| Configure managed identities on Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/configure-managed-identities-cluster |
| Configure cross-tenant access for Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/cross-tenant-query-and-commands |
| Configure customer-managed keys for Azure Data Explorer encryption | https://learn.microsoft.com/en-us/azure/data-explorer/customer-managed-keys |
| Authenticate Azure Data Explorer external tables with managed identities | https://learn.microsoft.com/en-us/azure/data-explorer/external-tables-managed-identities |
| Create secure cross-tenant Event Hubs data connections for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-cross-tenant |
| Ingest data to Azure Data Explorer using managed identity | https://learn.microsoft.com/en-us/azure/data-explorer/ingest-data-managed-identity |
| Apply Azure Data Explorer cluster delete locks | https://learn.microsoft.com/en-us/azure/data-explorer/manage-cluster-locks |
| Configure Azure Data Explorer cluster RBAC roles | https://learn.microsoft.com/en-us/azure/data-explorer/manage-cluster-permissions |
| Manage Azure Data Explorer database and table RBAC | https://learn.microsoft.com/en-us/azure/data-explorer/manage-database-permissions |
| Use managed identities with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/managed-identities-overview |
| Apply built-in Azure Policy definitions to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/policy-reference |
| Securely connect private-endpoint clusters to Power BI | https://learn.microsoft.com/en-us/azure/data-explorer/power-bi-private-endpoint |
| Create and authorize a Microsoft Entra application for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/provision-entra-id-app |
| Secure Azure Data Explorer clusters with Azure features | https://learn.microsoft.com/en-us/azure/data-explorer/security |
| Enable Conditional Access policies for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/security-conditional-access |
| Apply Azure Policy compliance controls to Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/security-controls-policy |
| Configure managed private endpoints for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-managed-private-endpoint-create |
| Configure network security options for Azure Data Explorer | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-overview |
| Secure Azure Data Explorer with private endpoints | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-private-endpoint |
| Create private endpoints for Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-private-endpoint-create |
| Restrict outbound access from Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-restrict-outbound-access |
| Manage public network access to Azure Data Explorer clusters | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-restrict-public-access |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Diagnose Azure Data Explorer ingestion errors by error code | https://learn.microsoft.com/en-us/azure/data-explorer/error-codes |
| Resolve common Azure Data Explorer ingestion issues (FAQ) | https://learn.microsoft.com/en-us/azure/data-explorer/ingestion-faq |
| Use Resource Health to diagnose Azure Data Explorer issues | https://learn.microsoft.com/en-us/azure/data-explorer/monitor-with-resource-health |
| Troubleshoot Azure Data Explorer private endpoint connectivity | https://learn.microsoft.com/en-us/azure/data-explorer/security-network-private-endpoint-troubleshoot |
| Fix Azure Data Explorer cluster connection issues | https://learn.microsoft.com/en-us/azure/data-explorer/troubleshoot-connect-cluster |
| Troubleshoot Azure Data Explorer cluster creation failures | https://learn.microsoft.com/en-us/azure/data-explorer/troubleshoot-create-cluster |
| Resolve Azure Data Explorer DB and table operation failures | https://learn.microsoft.com/en-us/azure/data-explorer/troubleshoot-database-table |

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
