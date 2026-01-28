---
name: cost-management-billing
description: Expert knowledge for Cost Management Billing development including configuration, deployment, security, troubleshooting, limits & quotas, best practices, and integrations & coding patterns. Use when building, debugging, or optimizing Cost Management Billing applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Cost Management Billing Skill

This skill provides expert guidance for Cost Management Billing development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Apply Azure Cost Management optimization best practices | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices |
| Onboard to Microsoft Customer Agreement effectively | https://learn.microsoft.com/en-us/azure/cost-management-billing/microsoft-customer-agreement/onboard-microsoft-customer-agreement |
| Understand how Azure applies centrally assigned SQL licenses | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/manage-licenses-centrally |
| Use SQL HADR with centrally managed Hybrid Benefit | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/sql-server-hadr-licenses |
| Transition to centrally managed Azure Hybrid Benefit | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/transition-existing |
| Optimize Azure Hybrid Benefit for SQL Server centrally | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/tutorial-azure-hybrid-benefits-sql |

### Configuration
| Topic | URL |
|-------|-----|
| Create and manage Azure cost allocation rules | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/allocate-costs |
| Apply and manage billing tags for Azure costs | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/billing-tags |
| Configure tag inheritance for Azure cost allocation | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/enable-tag-inheritance |
| Configure Cost Management access for Azure partners | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/get-started-partners |
| Define Azure cost budgets using Bicep templates | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/quick-create-budget-bicep |
| Configure Azure cost budgets via ARM templates | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/quick-create-budget-template |
| Configure Azure reservation utilization alert thresholds | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/reservation-utilization-alerts |
| Configure markup rules in Azure 21Vianet | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/markup-china |
| Configure and manage tenants in MCA billing accounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/microsoft-customer-agreement/manage-tenants |
| Find Azure reservation purchasers using Monitor logs | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/find-reservation-purchaser-from-logs |
| Identify software meters excluded from savings plans | https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/software-costs-not-included |
| Create SQL Server license assignments for Azure Hybrid Benefit | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/create-sql-license-assignments |
| Configure SQL IaaS extension registration for cost management | https://learn.microsoft.com/en-us/azure/cost-management-billing/scope-level/sql-iaas-extension-registration |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy and use Azure Cost Management Power BI app | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/analyze-cost-data-azure-cost-management-power-bi-template-app |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Cost Management exports using SAS keys | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/export-cost-data-storage-account-sas-key |
| Automate Azure cost management with APIs and scripts | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/manage-automation |
| Migrate EA cost APIs to Microsoft Customer Agreement | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/migrate-cost-management-api |
| Map billing scenarios to Azure Cost Management APIs | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/cost-management-automation-scenarios |
| Automate MCA billing role migration across tenants with PowerShell | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/mca-role-migration |
| Create MCA subscriptions across associated Entra tenants | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-customer-agreement-associated-billing-tenants |
| Use REST APIs to programmatically create Azure subscriptions | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription |
| Create Enterprise Agreement subscriptions via latest APIs | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription-enterprise-agreement |
| Create MCA subscriptions programmatically with latest APIs | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription-microsoft-customer-agreement |
| Programmatically create MCA subscriptions across tenants | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription-microsoft-customer-agreement-across-tenants |
| Create Partner Agreement subscriptions via latest APIs | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription-microsoft-partner-agreement |
| Programmatically create Azure subscriptions via legacy APIs | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/programmatically-create-subscription-preview |
| Use Cost Details REST API for EA billing data | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/review-enterprise-billing |
| Use Cost Details REST API for subscription billing | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/review-subscription-billing |
| Use Azure Reservation APIs for automation | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/reservation-apis |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Configure and interpret Azure Cost Management alerts | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-alerts-monitor-usage-spending |
| Understand Azure Cost Management data timing and cycles | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/understand-cost-mgt-data |
| Avoid unexpected charges on Azure free accounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/avoid-charges-free-account |
| Track Azure free-tier usage against limits | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/check-free-service-usage |
| Use Azure free account services and credits | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/create-free-services |
| Understand timing and availability of EA invoice files | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/direct-ea-billing-invoice-documents |
| Azure EA pricing calculations and charge details | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/ea-pricing-overview |
| Understand and manage Azure subscription spending limits | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/spending-limit |
| Understand Azure subscription state behaviors | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/subscription-states |
| Change Azure subscription offers and eligibility | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/switch-azure-offer |
| Use Microsoft Agent Pre-Purchase commit units | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/agent-pre-purchase |
| Understand Copilot Credit P3 pre-purchase commit units | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/copilot-credit-p3 |
| Use Poland Central VM limited-time reservation offers | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/limited-time-central-poland |
| Leverage Sweden Central Linux VM promo discounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/limited-time-central-sweden |
| Use limited-time Linux VM reservation discounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/limited-time-linux |
| Apply US West VM limited-time reservation savings | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/limited-time-us-west |
| Apply Poland Central SQL services promo reservations | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/poland-limited-time-sql-services-reservations |
| Understand Azure reservation exchange policy limits and changes | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/reservation-exchange-policy-changes |
| Configure automatic renewal behavior for Azure reservations | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/reservation-renew |
| Check Azure savings plan utilization and data latency | https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/view-utilization |
| Understand limits when creating multiple Azure subscriptions | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/create-subscriptions-deploy-resources |
| Azure billing meter ID update impacts and behavior | https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/billing-meter-id-updates |
| Understand shared Azure billing meter regions and costs | https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/billing-meter-location |

### Security
| Topic | URL |
|-------|-----|
| Assign RBAC access to Azure Cost Management data | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/assign-access-acm-data |
| Manage Azure subscription administrators with RBAC | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/add-change-subscription-administrator |
| Prevent unused Azure subscriptions from auto-blocking | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/avoid-unused-subscriptions |
| Create customer subscriptions under Microsoft Partner Agreement | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/create-customer-subscription |
| Elevate Global Administrator access to Azure billing accounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/elevate-access-global-admin |
| Configure Azure marketplace purchase and access policies | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/enable-marketplace-purchases |
| Grant RBAC permissions to create EA subscriptions | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/grant-access-to-create-subscription |
| Link Partner Admin ID to Azure accounts for customer management | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id |
| Configure PAL for Power Platform and Dynamics with Azure credentials | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/link-partner-id-power-apps-accounts |
| Configure Azure subscription movement policies securely | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/manage-azure-subscription-policy |
| Configure Azure billing access roles by account type | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/manage-billing-access |
| Configure multitenant billing relationships and access in Azure | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/manage-billing-across-tenants |
| Check Azure credit balance and required roles | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/mca-check-azure-credits-balance |
| Secure tenants and subscriptions from fraud and abuse | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/protect-tenants-subscriptions |
| Admin roles and permissions for Azure Enterprise Agreements | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/understand-ea-roles |
| Manage billing roles for Microsoft Customer Agreement accounts | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/understand-mca-roles |
| View Azure reservations as a Cloud Solution Provider | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/how-to-view-csp-reservations |
| Grant RBAC access to Azure reservations using PowerShell | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/manage-reservations-rbac-powershell |
| Configure permissions to view and manage Azure reservations | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/view-reservations |
| Determine eligibility to buy Azure savings plans | https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/permission-buy-savings-plan |
| Configure permissions to manage Azure savings plans | https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/permission-view-manage |
| Access roles for viewing Azure tax documents | https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/mca-download-tax-document |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure Cost Management error codes | https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-management-error-codes |
| Fix disabled Azure for Students subscriptions | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/azurestudents-subscription-disabled |
| Troubleshoot and reactivate disabled Azure subscriptions | https://learn.microsoft.com/en-us/azure/cost-management-billing/manage/subscription-disabled |
| Troubleshoot subscription access after MCA signup | https://learn.microsoft.com/en-us/azure/cost-management-billing/microsoft-customer-agreement/troubleshoot-subscription-access |
| Fix unavailable Azure reservation usage downloads | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-download-usage |
| Fix 'No eligible subscriptions' for Azure reservations | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-no-eligible-subscriptions |
| Resolve 'reservation type not available' in Azure | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-product-not-available |
| Troubleshoot Azure reservation recommendation issues | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-reservation-recommendation |
| Troubleshoot Azure reservation directory transfers | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-reservation-transfers-between-tenants |
| Diagnose and fix low Azure reservation utilization | https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/troubleshoot-reservation-utilization |
| Diagnose abnormal Azure savings plan utilization reporting | https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/troubleshoot-savings-plan-utilization |
| Troubleshoot Azure payment information update errors | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/billing-troubleshoot-azure-payment-issues |
| Fix EA user errors when creating Azure VMs | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/cannot-create-vm |
| Resolve Azure billing account visibility problems | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-account-not-found |
| Fix issues viewing Azure invoices in portal | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-cant-find-invoice |
| Use CSP usage pivot tables to diagnose billing | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-csp-billing-issues-usage-file-pivot-tables |
| Use MCA usage pivot tables to diagnose billing | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-customer-agreement-billing-issues-usage-file-pivot-tables |
| Resolve declined credit card issues in Azure | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-declined-card |
| Use EA usage pivot tables to diagnose billing | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-ea-billing-issues-usage-file-pivot-tables |
| Fix Azure billing threshold authorization problems | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-billing/troubleshoot-threshold-billing |
| Fix Azure subscription sign-up directory association error | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/cannot-sign-up-subscription |
| Resolve 'No subscriptions found' Azure sign-in error | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/no-subscriptions-found |
| Resolve common Azure portal sign-up issues | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/troubleshoot-azure-sign-up |
| Resolve 'Not available due to conflict' for reservations | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/troubleshoot-not-available-conflict |
| Fix Azure subscription sign-in problems | https://learn.microsoft.com/en-us/azure/cost-management-billing/troubleshoot-subscription/troubleshoot-sign-in-issue |

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
