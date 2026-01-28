---
name: operator-service-manager
description: Expert knowledge for Operator Service Manager development including best practices, integrations & coding patterns, configuration, security, deployment, and troubleshooting. Use when building, debugging, or optimizing Operator Service Manager applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Operator Service Manager Skill

This skill provides expert guidance for Operator Service Manager development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Apply onboarding and deployment practices for AOSM | https://learn.microsoft.com/en-us/azure/operator-service-manager/best-practices-onboard-deploy |
| Design and operate AOSM configuration groups | https://learn.microsoft.com/en-us/azure/operator-service-manager/configuration-guide |
| Implement Helm chart best practices for AOSM | https://learn.microsoft.com/en-us/azure/operator-service-manager/helm-requirements |
| Manage AOSM publisher artifact cleanup effectively | https://learn.microsoft.com/en-us/azure/operator-service-manager/resource-cleanup-management |
| Run Helm tests during AOSM NF installs and upgrades | https://learn.microsoft.com/en-us/azure/operator-service-manager/safe-upgrades-helm-test |
| Control AOSM upgrade failure and rollback behavior | https://learn.microsoft.com/en-us/azure/operator-service-manager/safe-upgrades-nf-level-rollback |

### Configuration
| Topic | URL |
|-------|-----|
| Map Helm and ARM parameters to AOSM configuration | https://learn.microsoft.com/en-us/azure/operator-service-manager/concepts-expose-parameters-configuration-group-schema |
| Configure AOSM cluster registry for resilient CNFs | https://learn.microsoft.com/en-us/azure/operator-service-manager/get-started-with-cluster-registry |
| Configure Helm options to retain failed AOSM deployments | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-use-helm-option-parameters |
| Configure geo-replication for AOSM artifact stores | https://learn.microsoft.com/en-us/azure/operator-service-manager/publisher-artifact-store-resiliency |

### Deployment
| Topic | URL |
|-------|-----|
| Interrupt nonterminal AOSM service deployments safely | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-cancel-service-deployments |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use AOSM CLI to discover and upload CNF images | https://learn.microsoft.com/en-us/azure/operator-service-manager/concepts-cli-containerized-network-function-image-upload |
| Manage AOSM artifact store with ACR and CLI | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-manage-artifacts-nexus |
| Push and pull artifacts with AOSM storage-backed artifact store | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-manage-artifacts-virtualized-network-function-cloud |
| Combine ARM templates with AOSM network service designs | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-onboard-azure-resource-manager-resources-cli |
| Onboard containerized network functions with AOSM CLI | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-onboard-containerized-network-function-cli |
| Onboard VNFs to Azure Operator Nexus via AOSM CLI | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-onboard-virtualized-network-function-cli |
| Use AOSM network function operator CLI commands | https://learn.microsoft.com/en-us/azure/operator-service-manager/manage-network-function-operator |

### Security
| Topic | URL |
|-------|-----|
| Secure AOSM artifact backhaul with Private Link | https://learn.microsoft.com/en-us/azure/operator-service-manager/get-started-with-private-link |
| Assign custom AOSM roles to service operators | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-assign-custom-role |
| Create custom RBAC roles for AOSM publishers | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-create-custom-role |
| Configure user-assigned managed identity for AOSM | https://learn.microsoft.com/en-us/azure/operator-service-manager/how-to-create-user-assigned-managed-identity |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure CLI AOSM extension onboarding issues | https://learn.microsoft.com/en-us/azure/operator-service-manager/troubleshoot-cli-common-issues |
| Diagnose Helm install failures in AOSM CNF deployments | https://learn.microsoft.com/en-us/azure/operator-service-manager/troubleshoot-helm-install-failures |

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
