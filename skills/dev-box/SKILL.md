---
name: dev-box
description: Expert knowledge for Dev Box development including best practices, deployment, configuration, security, integrations & coding patterns, limits & quotas, and troubleshooting. Use when building, debugging, or optimizing Dev Box applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Dev Box Skill

This skill provides expert guidance for Dev Box development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Best practices and troubleshooting for Dev Box image definitions | https://learn.microsoft.com/en-us/azure/dev-box/concept-authoring-troubleshooting-guide-team-customizations |
| Pre-generate Visual Studio caches in Dev Box images | https://learn.microsoft.com/en-us/azure/dev-box/how-to-generate-visual-studio-caches |

### Configuration
| Topic | URL |
|-------|-----|
| Configure networking requirements for Microsoft Dev Box | https://learn.microsoft.com/en-us/azure/dev-box/concept-dev-box-network-requirements |
| Configure Dev Box auto-delete policies to control costs | https://learn.microsoft.com/en-us/azure/dev-box/how-to-auto-delete-dev-box |
| Configure Dev Box catalogs for image definitions | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-catalog |
| Define and manage Dev Box customization tasks in catalogs | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-customization-tasks |
| Configure network connections for Dev Box dev centers | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-network-connections |
| Configure project policies to govern Dev Box usage | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-project-policy |
| Configure stop-on-disconnect timeout for Dev Boxes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-stop-on-disconnect |
| Author Dev Box imagedefinition.yaml for team customizations | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-team-customizations |
| Create and upload Dev Box user customization files | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-user-customizations |
| Configure virtual switches and networking for Dev Boxes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-connect-dev-box-virtual-switch |
| Install and configure Azure CLI devcenter extension for Dev Box | https://learn.microsoft.com/en-us/azure/dev-box/how-to-install-dev-box-cli |
| Configure Dev Box definitions for images and sizes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-manage-dev-box-definitions |
| Configure and manage Microsoft Dev Box pools | https://learn.microsoft.com/en-us/azure/dev-box/how-to-manage-dev-box-pools |
| Manage Microsoft Dev Box projects and pools | https://learn.microsoft.com/en-us/azure/dev-box/how-to-manage-dev-box-projects |
| Create and manage Dev Box dev centers | https://learn.microsoft.com/en-us/azure/dev-box/how-to-manage-dev-center |
| Configure monitoring and diagnostic logs for Microsoft Dev Box | https://learn.microsoft.com/en-us/azure/dev-box/monitor-dev-box |
| Use Dev Box monitoring logs and metrics schema | https://learn.microsoft.com/en-us/azure/dev-box/monitor-dev-box-reference |
| Configure Microsoft Dev Box using ARM templates | https://learn.microsoft.com/en-us/azure/dev-box/quickstart-configure-dev-box-arm-template |
| Configure core Microsoft Dev Box resources in Azure | https://learn.microsoft.com/en-us/azure/dev-box/quickstart-configure-dev-box-service |
| Configure Dev Box resources with Get Started template | https://learn.microsoft.com/en-us/azure/dev-box/quickstart-get-started-template |
| Reference schema for Dev Box imagedefinition.yaml and task.yaml | https://learn.microsoft.com/en-us/azure/dev-box/reference-dev-box-customizations |

### Deployment
| Topic | URL |
|-------|-----|
| Plan and implement a Microsoft Dev Box deployment | https://learn.microsoft.com/en-us/azure/dev-box/concept-dev-box-deployment-guide |
| Configure Dev Box imaging pipeline for team customizations | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-dev-center-imaging |
| Build and distribute Dev Box images with Azure VM Image Builder | https://learn.microsoft.com/en-us/azure/dev-box/how-to-customize-devbox-azure-image-builder |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Connect physical Android devices to a Dev Box | https://learn.microsoft.com/en-us/azure/dev-box/how-to-connect-devices-to-dev-box |
| Integrate Microsoft Dev Box with VS Code via dev tunnels | https://learn.microsoft.com/en-us/azure/dev-box/how-to-set-up-dev-tunnels |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| View and increase Microsoft Dev Box quotas | https://learn.microsoft.com/en-us/azure/dev-box/how-to-request-quota-increase |
| Set per-user Dev Box limits to control project costs | https://learn.microsoft.com/en-us/azure/dev-box/tutorial-dev-box-limits |

### Security
| Topic | URL |
|-------|-----|
| Plan Azure RBAC roles for Microsoft Dev Box deployments | https://learn.microsoft.com/en-us/azure/dev-box/concept-dev-box-role-based-access-control |
| Authenticate to Microsoft Dev Box REST APIs with Azure CLI | https://learn.microsoft.com/en-us/azure/dev-box/how-to-authenticate |
| Secure Dev Box tunnels with Entra conditional access | https://learn.microsoft.com/en-us/azure/dev-box/how-to-conditional-access-dev-tunnels-service |
| Configure Intune Conditional Access for Dev Boxes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-configure-intune-conditional-access-policies |
| Secure Dev Box customizations with Key Vault and service principals | https://learn.microsoft.com/en-us/azure/dev-box/how-to-customizations-connect-resource-repository |
| Set up Intune Endpoint Privilege Management for Dev Boxes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-elevate-privilege-dev-box |
| Enable Microsoft Entra SSO for Dev Boxes | https://learn.microsoft.com/en-us/azure/dev-box/how-to-enable-single-sign-on |
| Assign Dev Box project access with Azure RBAC | https://learn.microsoft.com/en-us/azure/dev-box/how-to-manage-dev-box-access |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Step-by-step guide to troubleshoot Dev Box connectivity | https://learn.microsoft.com/en-us/azure/dev-box/how-to-resolve-dev-box-connectivity-issues |
| Fix stale or inaccessible Dev Boxes in Windows Task view | https://learn.microsoft.com/en-us/azure/dev-box/how-to-troubleshoot-dev-box-task-view |
| Resolve known Microsoft Dev Box connectivity issues | https://learn.microsoft.com/en-us/azure/dev-box/how-to-troubleshoot-remote-desktop-connectivity |
| Use Troubleshoot and Repair to fix Dev Box connectivity | https://learn.microsoft.com/en-us/azure/dev-box/how-to-troubleshoot-repair-dev-box |

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
