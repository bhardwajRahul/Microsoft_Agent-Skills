---
name: azure-fluid-relay
description: Expert knowledge for Azure Fluid Relay development including security, best practices, integrations & coding patterns, configuration, troubleshooting, deployment, and limits & quotas. Use when building, debugging, or optimizing Azure Fluid Relay applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Fluid Relay Skill

This skill provides expert guidance for Azure Fluid Relay development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Manage Azure Fluid Relay containers effectively | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/container-management |
| Automate testing for Azure Fluid Relay applications | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/test-automation |

### Configuration
| Topic | URL |
|-------|-----|
| Match Fluid Framework versions with Fluid Relay | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/version-compatibility |
| Delete Azure Fluid Relay containers using CLI | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/container-deletion |
| Configure AzureClient local mode for Fluid testing | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/local-mode-with-azure-client |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Fluid applications to Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/deploy-fluid-static-web-apps |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Fluid distributed data structures in apps | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/data-structures |
| Implement Fluid Relay TokenProvider with Azure Functions | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/azure-function-token-provider |
| Connect applications to Azure Fluid Relay via AzureClient | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/connect-fluid-azure-service |
| Use Fluid Framework audience features with Azure Client | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/use-audience-in-fluid |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Service limits and throttling for Azure Fluid Relay | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/reference/service-limits |

### Security
| Topic | URL |
|-------|-----|
| Implement auth and authorization for Fluid apps | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/authentication-authorization |
| Configure customer-managed keys for Fluid Relay | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/customer-managed-keys |
| Understand Azure Fluid Relay data encryption | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/concepts/data-encryption |
| Implement Azure Fluid Relay JWT token contract | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/fluid-json-web-token |
| Rotate and manage Azure Fluid Relay access keys | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/rotate-fluid-relay-access-keys |
| Validate Fluid container creator for secure access | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/validate-document-creator |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Recover corrupted Azure Fluid Relay container data | https://learn.microsoft.com/en-us/azure/azure-fluid-relay/how-tos/container-recovery |

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
