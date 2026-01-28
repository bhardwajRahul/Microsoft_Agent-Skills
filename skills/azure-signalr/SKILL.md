---
name: azure-signalr
description: Expert knowledge for Azure Signalr development including configuration, security, best practices, architecture & design patterns, integrations & coding patterns, limits & quotas, troubleshooting, and deployment. Use when building, debugging, or optimizing Azure Signalr applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Signalr Skill

This skill provides expert guidance for Azure Signalr development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design resilient multi-instance architectures for Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-disaster-recovery |
| Scale Azure SignalR with multiple instances and sharding | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-scale-multi-instances |

### Best Practices
| Topic | URL |
|-------|-----|
| Gracefully shut down Azure SignalR app servers | https://learn.microsoft.com/en-us/azure/azure-signalr/server-graceful-shutdown |
| Handle client disconnections and reconnections in Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-client-disconnections |

### Configuration
| Topic | URL |
|-------|-----|
| Configure upstream endpoints and protocols in Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/concept-upstream |
| Configure a custom domain for Azure SignalR Service | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-custom-domain |
| Enable and configure geo-replication for Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-enable-geo-replication |
| Monitor Azure SignalR Service with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-signalr/monitor-signalr |
| Reference for Azure SignalR monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/azure-signalr/monitor-signalr-reference |
| Configure Azure Functions apps with Azure SignalR bindings | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-serverless-development-config |
| Configure and use Azure SignalR Local Emulator for serverless | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-emulator |

### Deployment
| Topic | URL |
|-------|-----|
| Recreate Azure SignalR resources in another region | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-move-across-regions |
| Configure autoscale for Azure SignalR Premium tier | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-scale-autoscale |
| Scale Azure SignalR instances via portal and CLI | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-scale-signalr |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Azure SignalR events with Event Grid subscribers | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-event-grid-integration |
| Send Azure SignalR connection events to Event Grid | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-event-grid-integration |
| Integrate Azure SignalR with reverse proxies | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-reverse-proxy-overview |
| Use Azure SignalR Service SDK in app servers | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-use |
| Manage Azure SignalR clients with the Management SDK | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-use-management-sdk |
| Use Azure SignalR Service with API Management | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-work-with-apim |
| Use Azure SignalR Service with Application Gateway | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-work-with-app-gateway |
| Use Azure SignalR data-plane REST APIs | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-reference-data-plane-rest-api |
| Azure SignalR data-plane REST API v1 reference | https://learn.microsoft.com/en-us/azure/azure-signalr/swagger/signalr-data-plane-rest-v1 |
| Azure SignalR data-plane REST API v1-preview reference | https://learn.microsoft.com/en-us/azure/azure-signalr/swagger/signalr-data-plane-rest-v1-preview |
| Azure SignalR data-plane REST API v20220601 | https://learn.microsoft.com/en-us/azure/azure-signalr/swagger/signalr-data-plane-rest-v20220601 |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand message and connection counting for SignalR billing | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-messages-and-connections |
| Plan Azure SignalR capacity using performance benchmarks | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-performance |

### Security
| Topic | URL |
|-------|-----|
| Disable access key auth and enforce Entra for SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-disable-local-auth |
| Configure network access control for Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-network-access-control |
| Secure Azure SignalR with private endpoints | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-private-endpoints |
| Use Azure SignalR service tags in NSGs | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-service-tags |
| Secure SignalR outbound traffic with shared private endpoints | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-shared-private-endpoints |
| Access Key Vault privately via SignalR shared endpoints | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-shared-private-endpoints-key-vault |
| Use managed identities with Azure SignalR Service | https://learn.microsoft.com/en-us/azure/azure-signalr/howto-use-managed-identity |
| Built-in Azure Policy definitions for SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/policy-reference |
| Apply Azure Policy compliance controls to Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/security-controls-policy |
| Implement custom client authentication for Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-authenticate-oauth |
| Authorize Azure SignalR access with Microsoft Entra ID RBAC | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-concept-authorize-azure-active-directory |
| Authorize Azure SignalR with Microsoft Entra applications | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-authorize-application |
| Configure cross-tenant authorization for Azure SignalR | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-authorize-cross-tenant |
| Authorize Azure SignalR with managed identities | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-authorize-managed-identity |
| Enforce Azure SignalR compliance with Azure Policy | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-azure-policy |
| Configure Azure SignalR Application Firewall rules | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-configure-application-firewall |
| Rotate Azure SignalR access keys securely | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-key-rotation |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Analyze Azure SignalR diagnostic logs with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-diagnostic-logs |
| Troubleshoot common Azure SignalR Service issues | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-troubleshoot-guide |
| Use Azure SignalR live trace tool for diagnostics | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-troubleshoot-live-trace |
| Self-diagnose Azure SignalR connectivity and delivery problems | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-howto-troubleshoot-method |
| Azure SignalR Service FAQ and issue guidance | https://learn.microsoft.com/en-us/azure/azure-signalr/signalr-resource-faq |

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
