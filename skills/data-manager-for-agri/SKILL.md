---
name: data-manager-for-agri
description: Expert knowledge for Data Manager For Agri development including security, integrations & coding patterns, limits & quotas, and configuration. Use when building, debugging, or optimizing Data Manager For Agri applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Data Manager For Agri Skill

This skill provides expert guidance for Data Manager For Agri development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Configuration
| Topic | URL |
|-------|-----|
| Enable and configure logging and diagnostics for Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-audit-logs |
| Configure Azure Data Manager for Agriculture event schemas with Azure Event Grid | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-use-events |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate and ingest farm activities data into Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-farm-operations-data |
| Ingest satellite imagery into Azure Data Manager for Agriculture using Sentinel Hub | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-ingest-satellite-imagery |
| Ingest sensor data into Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-ingest-sensor-data |
| Integrate weather forecast providers with Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-ingest-weather-data |
| Use generative AI and copilot templates with Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-llm-apis |
| Ingest and egress farm activities data using Azure Data Manager for Agriculture jobs | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-ingest-and-egress-farm-operations-data |
| Integrate Azure Data Manager for Agriculture with farm activities data providers | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-integrate-with-farm-ops-data-provider |
| Install and use ISV solutions with Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-isv-solution |
| Push and consume sensor data as provider and customer in Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-sensor-as-customer-and-partner |
| Set up sensor integrations as a customer in Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-sensors-customer |
| Integrate sensor partners with Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-sensors-partner |
| Use plant tissue nutrient APIs in Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-use-nutrient-apis |
| Consume Azure Data Manager for Agriculture Event Grid events | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/sample-events |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Plan and manage API throttling limits for Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-understanding-throttling |

### Security
| Topic | URL |
|-------|-----|
| Store and manage third-party license credentials in Azure Data Manager for Agriculture | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/concepts-byol-and-credentials |
| Secure Azure Data Manager for Agriculture with Private Link and private endpoints | https://learn.microsoft.com/en-us/azure/data-manager-for-agri/how-to-set-up-private-links |

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
