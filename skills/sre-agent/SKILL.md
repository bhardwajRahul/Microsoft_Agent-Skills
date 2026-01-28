---
name: sre-agent
description: Expert knowledge for Sre Agent development including security, configuration, integrations & coding patterns, troubleshooting, and best practices. Use when building, debugging, or optimizing Sre Agent applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Sre Agent Skill

This skill provides expert guidance for Sre Agent development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Optimize incident management workflows with Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/incident-management |

### Configuration
| Topic | URL |
|-------|-----|
| Configure and use code interpreter in Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/code-interpreter |
| Configure SRE Agent memory system for incident knowledge | https://learn.microsoft.com/en-us/azure/sre-agent/memory-system |
| Configure scheduled tasks in Azure SRE Agent for automation | https://learn.microsoft.com/en-us/azure/sre-agent/scheduled-tasks |
| Create and manage subagents with Azure SRE Agent builder | https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-overview |
| Configure Azure SRE Agent subagents for operational workflows | https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-scenarios |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Azure SRE Agent with source code repositories | https://learn.microsoft.com/en-us/azure/sre-agent/code-repository-connect |
| Configure connectors to external services in Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/connectors |
| Implement custom Python tools and integrations in SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/custom-logic-python |
| Connect Azure SRE Agent to custom MCP servers securely | https://learn.microsoft.com/en-us/azure/sre-agent/custom-mcp-server |

### Security
| Topic | URL |
|-------|-----|
| Manage SRE Agent managed identity and user permissions | https://learn.microsoft.com/en-us/azure/sre-agent/agent-managed-identity |
| Control Azure SRE Agent run modes and consent for actions | https://learn.microsoft.com/en-us/azure/sre-agent/agent-run-modes |
| Understand data residency and privacy for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/data-privacy |
| Configure roles, permissions, and RBAC for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/roles-permissions-overview |
| Configure RBAC user access roles for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/user-access-roles |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure SRE Agent issues and errors | https://learn.microsoft.com/en-us/azure/sre-agent/faq |
| Troubleshoot Azure App Service apps with SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-app-service |
| Troubleshoot Azure Container Apps with SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-container-apps |

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
