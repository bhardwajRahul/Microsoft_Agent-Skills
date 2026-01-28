---
name: role-based-access-control
description: Expert knowledge for Role Based Access Control development including best practices, security, limits & quotas, troubleshooting, and integrations & coding patterns. Use when building, debugging, or optimizing Role Based Access Control applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Role Based Access Control Skill

This skill provides expert guidance for Role Based Access Control development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Apply best practices for Azure RBAC access control | https://learn.microsoft.com/en-us/azure/role-based-access-control/best-practices |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Assign Azure RBAC roles using Bicep templates | https://learn.microsoft.com/en-us/azure/role-based-access-control/quickstart-role-assignments-bicep |
| Assign Azure RBAC roles with ARM templates | https://learn.microsoft.com/en-us/azure/role-based-access-control/quickstart-role-assignments-template |
| Assign Azure RBAC roles to groups via PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/tutorial-role-assignments-group-powershell |
| Grant Azure RBAC access using PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/tutorial-role-assignments-user-powershell |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Migrate Azure classic administrators to RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/classic-administrators |
| Scale Azure RBAC role assignments with ABAC attributes | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-custom-security-attributes-example |
| Design and manage Azure RBAC custom roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles |
| Create Azure RBAC custom roles in portal | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-portal |

### Security
| Topic | URL |
|-------|-----|
| Use Azure built-in RBAC roles and permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles |
| Assign AI and machine learning Azure RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/ai-machine-learning |
| Use analytics-focused Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/analytics |
| Assign compute-focused Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/compute |
| Secure container workloads using Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/containers |
| Grant database access with Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/databases |
| Use DevOps Azure built-in RBAC roles for pipelines | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/devops |
| Use general-purpose Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/general |
| Use hybrid and multicloud RBAC roles in Azure | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/hybrid-multicloud |
| Manage identity access with Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/identity |
| Use integration-focused Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/integration |
| Secure IoT solutions with Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/internet-of-things |
| Use management and governance RBAC roles in Azure | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/management-and-governance |
| Use Azure RBAC built-in migration roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/migration |
| Use Azure RBAC built-in monitor roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/monitor |
| Configure networking access with Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/networking |
| Apply privileged Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/privileged |
| Apply security-focused Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/security |
| Manage storage access using Azure built-in RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/storage |
| Control web and mobile resources with Azure RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/web-and-mobile |
| View Azure RBAC change history in Activity Log | https://learn.microsoft.com/en-us/azure/role-based-access-control/change-history-report |
| Use actions and attributes in Azure ABAC conditions | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-authorization-actions-attributes |
| Restrict blob read access with tags and ABAC | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-custom-security-attributes |
| Author Azure ABAC role assignment condition syntax | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-format |
| Meet prerequisites to use Azure RBAC conditions | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-prerequisites |
| Manage Azure RBAC ABAC conditions with Azure CLI | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-role-assignments-cli |
| Configure Azure RBAC ABAC conditions in portal | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-role-assignments-portal |
| Manage Azure RBAC ABAC conditions with PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-role-assignments-powershell |
| Configure Azure RBAC ABAC conditions via REST API | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-role-assignments-rest |
| Add Azure RBAC ABAC conditions using ARM templates | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-role-assignments-template |
| Define Azure RBAC custom roles using Bicep | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-bicep |
| Manage Azure RBAC custom roles with Azure CLI | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-cli |
| Manage Azure RBAC custom roles with PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-powershell |
| Manage Azure RBAC custom roles via REST API | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-rest |
| Define Azure RBAC custom roles with ARM templates | https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-template |
| Example ABAC conditions for delegating RBAC management | https://learn.microsoft.com/en-us/azure/role-based-access-control/delegate-role-assignments-examples |
| Delegate Azure RBAC role management with ABAC | https://learn.microsoft.com/en-us/azure/role-based-access-control/delegate-role-assignments-overview |
| Delegate Azure RBAC role management with ABAC conditions | https://learn.microsoft.com/en-us/azure/role-based-access-control/delegate-role-assignments-portal |
| List and understand Azure RBAC deny assignments | https://learn.microsoft.com/en-us/azure/role-based-access-control/deny-assignments |
| Elevate Global Administrator access to all Azure subscriptions | https://learn.microsoft.com/en-us/azure/role-based-access-control/elevate-access-global-admin |
| Use AI and ML Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/ai-machine-learning |
| Use analytics-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/analytics |
| Use compute-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/compute |
| Use containers-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/containers |
| Use databases-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/databases |
| Use DevOps-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/devops |
| Use general-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/general |
| Assign RBAC permissions for hybrid and multicloud resources | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/hybrid-multicloud |
| Use identity-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/identity |
| Use integration-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/integration |
| Use IoT-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/internet-of-things |
| Configure RBAC permissions for management and governance resources | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/management-and-governance |
| Use migration-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/migration |
| Use Azure Monitor RBAC permission strings in custom roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/monitor |
| Use networking-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/networking |
| Use security-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/security |
| Use storage-category Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/storage |
| Use web and mobile Azure RBAC permissions | https://learn.microsoft.com/en-us/azure/role-based-access-control/permissions/web-and-mobile |
| Use PIM for eligible and time-bound Azure RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/pim-integration |
| Apply built-in Azure Policy definitions for RBAC governance | https://learn.microsoft.com/en-us/azure/role-based-access-control/policy-reference |
| Differentiate Azure RBAC, Entra, and classic admin roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/rbac-and-directory-admin-roles |
| Reference Azure resource provider permission operations | https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations |
| Configure and interpret Azure RBAC role assignments | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments |
| Create alerts for privileged Azure RBAC role assignments | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-alert |
| Assign Azure RBAC roles using Azure CLI | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-cli |
| Activate eligible Azure RBAC roles in the portal | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-eligible-activate |
| Grant Azure RBAC access to external B2B users | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-external-users |
| List Azure RBAC role assignments using Azure CLI | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-list-cli |
| List Azure RBAC role assignments in the portal | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-list-portal |
| List Azure RBAC role assignments with PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-list-powershell |
| List Azure RBAC role assignments via REST API | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-list-rest |
| Assign Azure RBAC roles using the portal | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal |
| Assign Azure RBAC roles starting from a managed identity | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal-managed-identity |
| Assign subscription Owner with constrained RBAC conditions | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal-subscription-admin |
| Assign Azure RBAC roles using PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-powershell |
| Remove Azure RBAC role assignments via portal and scripts | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-remove |
| Assign Azure RBAC roles via REST API | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-rest |
| Understand steps to assign Azure RBAC roles | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-steps |
| Assign Azure RBAC roles with ARM templates | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-template |
| Understand Azure RBAC role definition structure | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-definitions |
| List Azure RBAC role definitions via portal and APIs | https://learn.microsoft.com/en-us/azure/role-based-access-control/role-definitions-list |
| Determine and apply Azure RBAC scopes | https://learn.microsoft.com/en-us/azure/role-based-access-control/scope-overview |
| Use Azure Policy compliance controls for Azure RBAC | https://learn.microsoft.com/en-us/azure/role-based-access-control/security-controls-policy |
| Transfer Azure subscriptions between Entra directories securely | https://learn.microsoft.com/en-us/azure/role-based-access-control/transfer-subscription |
| Create Azure custom RBAC roles with CLI | https://learn.microsoft.com/en-us/azure/role-based-access-control/tutorial-custom-role-cli |
| Create Azure custom RBAC roles with PowerShell | https://learn.microsoft.com/en-us/azure/role-based-access-control/tutorial-custom-role-powershell |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure role assignment condition failures | https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-troubleshoot |
| Resolve Azure RBAC role assignment limit issues | https://learn.microsoft.com/en-us/azure/role-based-access-control/troubleshoot-limits |
| Diagnose and fix common Azure RBAC access issues | https://learn.microsoft.com/en-us/azure/role-based-access-control/troubleshooting |

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
