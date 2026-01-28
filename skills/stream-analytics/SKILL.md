---
name: stream-analytics
description: Expert knowledge for Stream Analytics development including configuration, security, integrations & coding patterns, deployment, troubleshooting, comparing x vs. y, architecture & design patterns, best practices, and limits & quotas. Use when building, debugging, or optimizing Stream Analytics applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Stream Analytics Skill

This skill provides expert guidance for Stream Analytics development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design geo-redundant Azure Stream Analytics architectures | https://learn.microsoft.com/en-us/azure/stream-analytics/geo-redundancy |
| Apply Azure Stream Analytics solution patterns | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-solution-patterns |

### Best Practices
| Topic | URL |
|-------|-----|
| Implement geofencing and geospatial aggregation in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/geospatial-scenarios |
| Implement input validation in Stream Analytics queries | https://learn.microsoft.com/en-us/azure/stream-analytics/input-validation |
| Optimize Stream Analytics query performance with Job Simulation | https://learn.microsoft.com/en-us/azure/stream-analytics/optimize-query-using-job-diagram-simulator |
| Optimize non-parallelizable Stream Analytics jobs with repartitioning | https://learn.microsoft.com/en-us/azure/stream-analytics/repartition |
| Understand checkpoint and replay recovery in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-concepts-checkpoint-replay |
| Apply best practices for Stream Analytics to Cosmos DB output | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-documentdb-output |
| Improve reliability of Azure Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-job-reliability |
| Use query parallelization to scale Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-parallelization |
| Scale Stream Analytics jobs up and out for higher throughput | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-scale-jobs |
| Scale ML Studio functions in Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-scale-with-machine-learning-functions |
| Optimize Azure SQL output performance in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-sql-output-perf |
| Apply common Azure Stream Analytics query patterns | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-stream-analytics-query-patterns |
| Design configurable threshold-based alerting with Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-threshold-based-rules |
| Design time handling strategies in Azure Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-time-handling |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare tools for building Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/feature-comparison |
| Choose Azure real-time and stream processing services | https://learn.microsoft.com/en-us/azure/stream-analytics/streaming-technologies |

### Configuration
| Topic | URL |
|-------|-----|
| Schedule automatic pause and resume for Stream Analytics jobs with PowerShell | https://learn.microsoft.com/en-us/azure/stream-analytics/automation-powershell |
| Configure Azure Cosmos DB as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/azure-cosmos-db-output |
| Configure Azure Data Explorer as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/azure-database-explorer-output |
| Connect Azure Stream Analytics outputs to Azure Functions | https://learn.microsoft.com/en-us/azure/stream-analytics/azure-functions-output |
| Configure autoscale rules for Stream Analytics jobs via CI/CD tool | https://learn.microsoft.com/en-us/azure/stream-analytics/cicd-autoscale |
| Configure late arrival and out-of-order policies in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/event-ordering |
| Configure Stream Analytics jobs using JobConfig.json fields | https://learn.microsoft.com/en-us/azure/stream-analytics/job-config-json |
| Configure Kafka as an output target for Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/kafka-output |
| Configure monitoring for Azure Stream Analytics with Azure Monitor | https://learn.microsoft.com/en-us/azure/stream-analytics/monitor-azure-stream-analytics |
| Reference for Stream Analytics monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/stream-analytics/monitor-azure-stream-analytics-reference |
| Configure Stream Analytics as IoT Edge module on Azure Stack Hub | https://learn.microsoft.com/en-us/azure/stream-analytics/on-azure-stack |
| Configure Azure Database for PostgreSQL as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/postgresql-database-output |
| Configure Service Bus queues as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/service-bus-queues-output |
| Configure Service Bus topics as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/service-bus-topics-output |
| Configure autoscale streaming units in Azure Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-autoscale |
| Configure custom blob output partitioning in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-custom-path-patterns-blob-storage-output |
| Configure streaming inputs for Azure Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-define-inputs |
| Configure outputs for Azure Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-define-outputs |
| Rotate input and output credentials in Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-login-credentials-inputs-outputs |
| Monitor and manage Stream Analytics jobs with PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-monitor-and-manage-jobs-use-powershell |
| Programmatically enable and configure monitoring for Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-monitor-jobs |
| Monitor Stream Analytics jobs using Azure portal metrics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-monitoring |
| Configure output error handling policies in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-output-error-policy |
| Set up Azure Monitor alerts for Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-set-up-alerts |
| Use and configure reference data in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-use-reference-data |
| Set up Azure Table storage as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/table-storage-output |
| Export and manage Stream Analytics jobs with VS Code extension | https://learn.microsoft.com/en-us/azure/stream-analytics/visual-studio-code-explore-jobs |
| Test Stream Analytics jobs locally with sample data in VS Code | https://learn.microsoft.com/en-us/azure/stream-analytics/visual-studio-code-local-run |
| Run and validate Stream Analytics queries locally with VS Code | https://learn.microsoft.com/en-us/azure/stream-analytics/visual-studio-code-local-run-all |
| Test Stream Analytics queries locally against live input in VS Code | https://learn.microsoft.com/en-us/azure/stream-analytics/visual-studio-code-local-run-live-input |
| Use IntelliSense for Stream Analytics query language in VS Code | https://learn.microsoft.com/en-us/azure/stream-analytics/vs-code-intellisense |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Azure Stream Analytics jobs with Bicep in CI/CD | https://learn.microsoft.com/en-us/azure/stream-analytics/cicd-deploy-with-bicep |
| Deploy Stream Analytics jobs using GitHub Actions workflows | https://learn.microsoft.com/en-us/azure/stream-analytics/cicd-github-actions |
| Automate Stream Analytics build, test, and deployment with ASA CI/CD npm tools | https://learn.microsoft.com/en-us/azure/stream-analytics/cicd-tools |
| Export Stream Analytics jobs as ARM templates for redeployment | https://learn.microsoft.com/en-us/azure/stream-analytics/resource-manager-export |
| Create Azure DevOps CI/CD pipelines for Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/set-up-cicd-pipeline |
| Implement CI/CD for Stream Analytics on IoT Edge with REST APIs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-cicd-api |
| Set up CI/CD for Stream Analytics with NuGet package | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-tools-for-visual-studio-cicd |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Synapse dedicated SQL pool as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/azure-synapse-analytics-output |
| Write Stream Analytics output to Blob and Data Lake Gen2 | https://learn.microsoft.com/en-us/azure/stream-analytics/blob-storage-azure-data-lake-gen2-output |
| Use Confluent Cloud Kafka as Stream Analytics input | https://learn.microsoft.com/en-us/azure/stream-analytics/confluent-kafka-input |
| Send Stream Analytics output to Confluent Cloud Kafka | https://learn.microsoft.com/en-us/azure/stream-analytics/confluent-kafka-output |
| Develop and debug Azure Stream Analytics jobs locally | https://learn.microsoft.com/en-us/azure/stream-analytics/develop-locally |
| Send Azure Stream Analytics output to Event Hubs | https://learn.microsoft.com/en-us/azure/stream-analytics/event-hubs-output |
| Integrate Azure Machine Learning models as Stream Analytics UDFs | https://learn.microsoft.com/en-us/azure/stream-analytics/machine-learning-udf |
| Output Azure Stream Analytics data to Power BI | https://learn.microsoft.com/en-us/azure/stream-analytics/power-bi-output |
| Use Azure SQL Database as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/sql-database-output |
| Use Azure Functions to enable SQL upsert/merge from Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/sql-database-upsert |
| Configure Azure SQL Database as Stream Analytics output | https://learn.microsoft.com/en-us/azure/stream-analytics/sql-db-table |
| Use Azure SQL Database as reference data input | https://learn.microsoft.com/en-us/azure/stream-analytics/sql-reference-data |
| Connect Azure Stream Analytics to Kafka inputs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-define-kafka-input |
| Manage Azure Stream Analytics jobs using .NET Management SDK | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-dotnet-management-sdk |
| Develop .NET Standard user-defined functions for Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-edge-csharp-udf-methods |
| Use Azure Stream Analytics geospatial query functions | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-geospatial-functions |
| Implement linear regression with UDFs in Stream Analytics for trading | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-high-frequency-trading |
| Configure ML Studio (classic) UDFs in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-how-to-configure-azure-machine-learning-endpoints-in-stream-analytics |
| Create JavaScript user-defined aggregates in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-javascript-user-defined-aggregates |
| Implement JavaScript user-defined functions in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-javascript-user-defined-functions |
| Use built-in anomaly detection in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-machine-learning-anomaly-detection |
| Integrate Stream Analytics with Machine Learning Studio classic | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-machine-learning-integration-tutorial |
| Parse JSON, Avro, and CSV in Azure Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-parsing-json |
| Configure Protobuf input deserialization in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-parsing-protobuf |
| Integrate Stream Analytics with Event Hubs Schema Registry | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-schema-registry-integration |
| Write Azure Stream Analytics data to Delta Lake tables | https://learn.microsoft.com/en-us/azure/stream-analytics/write-to-delta-lake |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand streaming unit limits and performance in Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-streaming-unit-consumption |

### Security
| Topic | URL |
|-------|-----|
| Access Azure Data Explorer from Stream Analytics using managed identity | https://learn.microsoft.com/en-us/azure/stream-analytics/azure-data-explorer-managed-identity |
| Secure Stream Analytics blob outputs with managed identity | https://learn.microsoft.com/en-us/azure/stream-analytics/blob-output-managed-identity |
| Securely connect Stream Analytics jobs to VNets | https://learn.microsoft.com/en-us/azure/stream-analytics/connect-job-to-vnet |
| Access Azure Cosmos DB from Stream Analytics using managed identity | https://learn.microsoft.com/en-us/azure/stream-analytics/cosmos-db-managed-identity |
| Configure data protection for Azure Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/data-protection |
| Configure managed identity auth to Event Hubs from Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/event-hubs-managed-identity |
| Apply built-in Azure Policy definitions to Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/policy-reference |
| Use managed identity for Stream Analytics Power BI output | https://learn.microsoft.com/en-us/azure/stream-analytics/powerbi-output-managed-identity |
| Configure managed private endpoints for Stream Analytics clusters | https://learn.microsoft.com/en-us/azure/stream-analytics/private-endpoints |
| Run Stream Analytics jobs inside Azure virtual networks | https://learn.microsoft.com/en-us/azure/stream-analytics/run-job-in-virtual-network |
| Apply regulatory compliance policies to Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/security-controls-policy |
| Set up managed identity auth to Service Bus from Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/service-bus-managed-identity |
| Configure managed identity access to SQL/Synapse from Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/sql-database-output-managed-identity |
| Use managed identities with Azure Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-managed-identities-overview |
| Configure user-assigned managed identities for Stream Analytics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-user-assigned-managed-identity-overview |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve Azure Stream Analytics configuration error codes | https://learn.microsoft.com/en-us/azure/stream-analytics/configuration-error-codes |
| Resolve Azure Stream Analytics data error codes | https://learn.microsoft.com/en-us/azure/stream-analytics/data-error-codes |
| Diagnose Azure Stream Analytics resource log data errors | https://learn.microsoft.com/en-us/azure/stream-analytics/data-errors |
| Debug Stream Analytics queries using Visual Studio job diagram | https://learn.microsoft.com/en-us/azure/stream-analytics/debug-locally-using-job-diagram |
| Debug Stream Analytics queries locally using job diagram in VS Code | https://learn.microsoft.com/en-us/azure/stream-analytics/debug-locally-using-job-diagram-vs-code |
| Debug user-defined functions in Azure Stream Analytics jobs | https://learn.microsoft.com/en-us/azure/stream-analytics/debug-user-defined-functions |
| Resolve Azure Stream Analytics external availability error codes | https://learn.microsoft.com/en-us/azure/stream-analytics/external-availability-error-codes |
| Resolve Azure Stream Analytics external error codes | https://learn.microsoft.com/en-us/azure/stream-analytics/external-error-codes |
| Troubleshoot Azure Stream Analytics internal error codes | https://learn.microsoft.com/en-us/azure/stream-analytics/internal-error-codes |
| Use Stream Analytics job diagram metrics for troubleshooting | https://learn.microsoft.com/en-us/azure/stream-analytics/job-diagram-with-metrics |
| Troubleshoot Stream Analytics jobs using resource logs | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-job-diagnostic-logs |
| Debug Stream Analytics jobs using logical job diagram | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-job-logical-diagram-with-metrics |
| Troubleshoot Stream Analytics jobs with physical diagram metrics | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-job-physical-diagram-with-metrics |
| Troubleshoot Azure Stream Analytics input connection issues | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-troubleshoot-input |
| Troubleshoot Azure Stream Analytics output connection issues | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-troubleshoot-output |
| Troubleshoot Azure Stream Analytics query problems | https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-troubleshoot-query |

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
