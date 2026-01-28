---
name: sre-agent
description: Expert knowledge for Sre Agent development including security, integrations & coding patterns, troubleshooting, and configuration. Use when building, debugging, or optimizing Sre Agent applications.
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

### Configuration
| Topic | URL |
|-------|-----|
| Configure and use the Azure SRE Agent memory system | https://learn.microsoft.com/en-us/azure/sre-agent/memory-system |
| Configure scheduled tasks in Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/scheduled-tasks |
| Create and manage Azure SRE Agent subagents | https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-overview |
| Configure Azure SRE Agent subagents and workflows | https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-scenarios |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Azure SRE Agent with source code repositories | https://learn.microsoft.com/en-us/azure/sre-agent/code-repository-connect |
| Configure connectors to external services in Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/connectors |
| Run custom Python tools within Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/custom-logic-python |
| Connect Azure SRE Agent to custom MCP servers | https://learn.microsoft.com/en-us/azure/sre-agent/custom-mcp-server |

### Security
| Topic | URL |
|-------|-----|
| Configure RBAC roles and permissions for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/agent-managed-identity |
| Control Azure SRE Agent run modes and consent | https://learn.microsoft.com/en-us/azure/sre-agent/agent-run-modes |
| Understand data residency and privacy for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/data-privacy |
| Understand roles and permission model in Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/roles-permissions-overview |
| Assign user access roles for Azure SRE Agent | https://learn.microsoft.com/en-us/azure/sre-agent/user-access-roles |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure SRE Agent issues and errors | https://learn.microsoft.com/en-us/azure/sre-agent/faq |

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
