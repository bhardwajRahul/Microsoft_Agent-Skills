---
name: partner-solutions
description: Expert knowledge for Partner Solutions development including integrations & coding patterns, configuration, security, troubleshooting, and architecture & design patterns. Use when building, debugging, or optimizing Partner Solutions applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Partner Solutions Skill

This skill provides expert guidance for Partner Solutions development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design Cloud NGFW behind Azure Application Gateway | https://learn.microsoft.com/en-us/azure/partner-solutions/palo-alto/application-gateway |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Confluent environments, clusters, and topics in Azure | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/create-confluent-resources |
| Configure and manage Azure Confluent Connectors in portal | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/manage-confluent-connectors |
| Configure Datadog Azure resource settings in portal | https://learn.microsoft.com/en-us/azure/partner-solutions/datadog/manage |
| Manage Dynatrace Azure resource configuration settings | https://learn.microsoft.com/en-us/azure/partner-solutions/dynatrace/manage |
| Configure Elastic resource settings in Azure portal | https://learn.microsoft.com/en-us/azure/partner-solutions/elastic/manage |
| Configure Informatica advanced serverless runtime in Azure | https://learn.microsoft.com/en-us/azure/partner-solutions/informatica/create-advanced-serverless |
| Manage Informatica serverless runtime environments in Azure | https://learn.microsoft.com/en-us/azure/partner-solutions/informatica/manage-serverless |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Confluent Cloud with Azure Blob Storage connectors | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/add-confluent-connectors |
| Connect Confluent Cloud to Azure compute with Service Connector | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/add-connectors |
| Integrate Confluent Cloud with Azure Cosmos DB connectors | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/add-cosmos-db-connector |

### Security
| Topic | URL |
|-------|-----|
| Manage Confluent Cloud users and roles in Azure portal | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/manage-access |
| Configure Azure and Entra prerequisites for Datadog | https://learn.microsoft.com/en-us/azure/partner-solutions/datadog/prerequisites |
| Set up Azure and Entra prerequisites for Dynatrace | https://learn.microsoft.com/en-us/azure/partner-solutions/dynatrace/configure-prerequisites |
| Manage Informatica IDMC SSO and deployment lifecycle | https://learn.microsoft.com/en-us/azure/partner-solutions/informatica/manage |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Apache Kafka and Flink on Confluent Cloud in Azure | https://learn.microsoft.com/en-us/azure/partner-solutions/apache-kafka-confluent-cloud/troubleshoot |
| Troubleshoot Azure Datadog integration issues | https://learn.microsoft.com/en-us/azure/partner-solutions/datadog/troubleshoot |
| Troubleshoot Azure Native Dynatrace Service problems | https://learn.microsoft.com/en-us/azure/partner-solutions/dynatrace/troubleshoot |
| Troubleshoot Elastic Cloud Azure native integration | https://learn.microsoft.com/en-us/azure/partner-solutions/elastic/troubleshoot |
| Diagnose and fix Azure Native New Relic issues | https://learn.microsoft.com/en-us/azure/partner-solutions/new-relic/troubleshoot |

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
