---
name: playwright-testing
description: Expert knowledge for Playwright Testing development including best practices, security, configuration, integrations & coding patterns, limits & quotas, deployment, and troubleshooting. Use when building, debugging, or optimizing Playwright Testing applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Playwright Testing Skill

This skill provides expert guidance for Playwright Testing development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Optimize Playwright Testing suite configuration for speed | https://learn.microsoft.com/en-us/azure/playwright-testing/concept-determine-optimal-configuration |
| Configure Playwright visual comparison tests for cloud runs | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-configure-visual-comparisons |

### Configuration
| Topic | URL |
|-------|-----|
| Create and manage Microsoft Playwright Testing workspaces | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-manage-playwright-workspace |
| Configure Azure regions to optimize Playwright test latency | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-optimize-regional-latency |
| Configure playwright.service.config.ts for Playwright Testing | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-use-service-config-file |
| Use Microsoft Playwright Testing service features effectively | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-use-service-features |
| Access and interpret monitoring data for Playwright Testing | https://learn.microsoft.com/en-us/azure/playwright-testing/monitor-playwright-testing |
| Use Azure Monitor data schema for Microsoft Playwright Testing | https://learn.microsoft.com/en-us/azure/playwright-testing/monitor-playwright-testing-reference |

### Deployment
| Topic | URL |
|-------|-----|
| Set up CI-based Playwright Testing in Azure | https://learn.microsoft.com/en-us/azure/playwright-testing/quickstart-automate-end-to-end-testing |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Run Playwright cloud tests against local or private apps | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-test-local-applications |
| Use Playwright Testing reporting with sharded test runs | https://learn.microsoft.com/en-us/azure/playwright-testing/playwright-testing-reporting-with-sharding |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand Microsoft Playwright Testing free trial limits | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-try-playwright-testing-free |
| Review limits and configuration for Microsoft Playwright Testing | https://learn.microsoft.com/en-us/azure/playwright-testing/resource-limits-quotas-capacity |

### Security
| Topic | URL |
|-------|-----|
| Manage Microsoft Playwright Testing workspace access tokens | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-manage-access-tokens |
| Configure authentication and authorization for Playwright Testing | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-manage-authentication |
| Configure RBAC access for Playwright Testing workspaces | https://learn.microsoft.com/en-us/azure/playwright-testing/how-to-manage-workspace-access |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Microsoft Playwright Testing run failures | https://learn.microsoft.com/en-us/azure/playwright-testing/troubleshoot-test-run-failures |
| Fix AADSTS7000112 sign-in errors in Playwright portal | https://learn.microsoft.com/en-us/azure/playwright-testing/troubleshoot-unable-sign-into-playwright-portal |

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
