---
name: deployment-environments
description: Expert knowledge for Deployment Environments development including best practices, security, configuration, deployment, integrations & coding patterns, and troubleshooting. Use when building, debugging, or optimizing Deployment Environments applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Deployment Environments Skill

This skill provides expert guidance for Deployment Environments development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Structure Azure Deployment Environments catalogs efficiently | https://learn.microsoft.com/en-us/azure/deployment-environments/best-practice-catalog-structure |

### Configuration
| Topic | URL |
|-------|-----|
| Use environment.yaml schema for ADE definitions | https://learn.microsoft.com/en-us/azure/deployment-environments/concept-environment-yaml |
| Install and use the DevCenter Azure CLI extension for ADE | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-install-devcenter-cli-extension |
| Use ADE CLI commands for custom image management | https://learn.microsoft.com/en-us/azure/deployment-environments/reference-deployment-environment-cli |
| Reference ADE environment variables for custom image scripts | https://learn.microsoft.com/en-us/azure/deployment-environments/reference-deployment-environment-variables |

### Deployment
| Topic | URL |
|-------|-----|
| Create Azure Deployment Environments with Azure Developer CLI | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-configure-azure-developer-cli-deployment-environments |
| Use Azure Pipelines to deploy Azure Deployment Environments | https://learn.microsoft.com/en-us/azure/deployment-environments/tutorial-deploy-environments-in-cicd-azure-devops |
| Integrate Azure Deployment Environments with GitHub Actions CI/CD | https://learn.microsoft.com/en-us/azure/deployment-environments/tutorial-deploy-environments-in-cicd-github |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use custom container images with ADE extensibility | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-configure-extensibility-model-custom-image |

### Security
| Topic | URL |
|-------|-----|
| Plan Azure RBAC roles for Deployment Environments | https://learn.microsoft.com/en-us/azure/deployment-environments/concept-deployment-environments-role-based-access-control |
| Authenticate to Azure Deployment Environments REST APIs with Azure CLI | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-authenticate |
| Configure managed identity for Azure Deployment Environments | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-configure-managed-identity |
| Assign RBAC roles for Azure Deployment Environments access | https://learn.microsoft.com/en-us/azure/deployment-environments/how-to-manage-deployment-environments-access |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure Deployment Environments custom image failures | https://learn.microsoft.com/en-us/azure/deployment-environments/troubleshoot-custom-image-logs-errors |

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
