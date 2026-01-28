---
name: digital-twins
description: Expert knowledge for Digital Twins development including integrations & coding patterns, limits & quotas, security, configuration, best practices, and troubleshooting. Use when building, debugging, or optimizing Digital Twins applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Digital Twins Skill

This skill provides expert guidance for Digital Twins development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Best Practices
| Topic | URL |
|-------|-----|
| Implement tagging patterns for Azure Digital Twins models | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-use-tags |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure Digital Twins event endpoints | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-create-endpoints |
| Configure event routes and filters in Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-create-routes |
| Configure monitoring, metrics, and logs for Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-monitor |
| Handle reserved keywords in Digital Twins queries | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-reserved |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Data Explorer plugin to query Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-data-explorer-plugin |
| Configure Azure Digital Twins data history with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-data-history |
| Interpret Azure Digital Twins event notification payloads | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-event-notifications |
| Convert RDF/OWL ontologies to DTDL for Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-ontologies-convert |
| Configure Azure Digital Twins endpoints and event routes | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-route-events |
| Set up Azure Digital Twins data history to Azure Data Explorer | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-create-data-history-connection |
| Ingest IoT Hub telemetry into Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-ingest-iot-hub-data |
| Manage Azure Digital Twins graph relationships programmatically | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-manage-graph |
| Manage Azure Digital Twins instances via SDK and APIs | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-manage-twin |
| Parse and validate DTDL models with .NET parser | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-parse-models |
| Write and run Azure Digital Twins graph queries | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-query-graph |
| Set up twin-to-twin event propagation with Azure Functions | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-send-twin-to-twin-events |
| Call Azure Digital Twins REST APIs using Visual Studio .http files | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-use-apis |
| Use Power Platform connector with Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-use-power-platform-logic-apps-connector |
| Use FROM clause in Azure Digital Twins query language | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-clause-from |
| Use JOIN clause in Azure Digital Twins query language | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-clause-join |
| Use MATCH clause for graph traversal in Digital Twins queries | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-clause-match |
| Use SELECT clause in Azure Digital Twins query language | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-clause-select |
| Use WHERE clause in Azure Digital Twins query language | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-clause-where |
| Use Azure Digital Twins query language functions | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-functions |
| Use Azure Digital Twins query language operators | https://learn.microsoft.com/en-us/azure/digital-twins/reference-query-operators |
| Migrate from Azure Digital Twins preview control plane APIs | https://learn.microsoft.com/en-us/azure/digital-twins/resources-migrate-from-preview-apis |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand and measure Azure Digital Twins Query Units | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-query-units |
| Azure Digital Twins service limits and quotas | https://learn.microsoft.com/en-us/azure/digital-twins/reference-service-limits |

### Security
| Topic | URL |
|-------|-----|
| Apply security best practices for Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/concepts-security |
| Implement client authentication for Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-authenticate-client |
| Create Entra app registrations for Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-create-app-registration |
| Enable Azure Digital Twins private access with Private Link | https://learn.microsoft.com/en-us/azure/digital-twins/how-to-enable-private-link |
| Manage customer personal data in Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/resources-customer-data-requests |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Fix Azure Digital Twins 403 Forbidden errors | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-error-403-digital-twins |
| Fix Azure Digital Twins 404 sub-domain not found errors | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-error-404-digital-twins |
| Resolve Azure Digital Twins Explorer authentication errors | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-error-azure-digital-twins-explorer-authentication |
| Resolve Azure Digital Twins CLI parse failed errors | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-error-cli-parse |
| Resolve known issues in Azure Digital Twins | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-known-issues |
| Troubleshoot Azure Digital Twins performance issues | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-performance |
| Use Azure Resource Health for Digital Twins diagnostics | https://learn.microsoft.com/en-us/azure/digital-twins/troubleshoot-resource-health |

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
