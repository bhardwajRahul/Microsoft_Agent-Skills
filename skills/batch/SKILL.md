---
name: batch
description: Expert knowledge for Batch development including security, deployment, configuration, integrations & coding patterns, best practices, troubleshooting, and limits & quotas. Use when building, debugging, or optimizing Batch applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Batch Skill

This skill provides expert guidance for Batch development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design efficient Azure Batch list queries | https://learn.microsoft.com/en-us/azure/batch/batch-efficient-list-queries |
| Use task and node state counts to monitor Azure Batch | https://learn.microsoft.com/en-us/azure/batch/batch-get-resource-counts |
| Run MPI workloads with Azure Batch multi-instance tasks | https://learn.microsoft.com/en-us/azure/batch/batch-mpi |
| Use Azure Batch capabilities for rendering workloads | https://learn.microsoft.com/en-us/azure/batch/batch-rendering-functionality |
| Choose storage and data movement options for Azure Batch rendering | https://learn.microsoft.com/en-us/azure/batch/batch-rendering-storage-data-movement |
| Persist Azure Batch task output to durable storage | https://learn.microsoft.com/en-us/azure/batch/batch-task-output |
| Implement performance and design best practices in Azure Batch | https://learn.microsoft.com/en-us/azure/batch/best-practices |
| Optimize Azure Batch jobs with large task counts | https://learn.microsoft.com/en-us/azure/batch/large-number-tasks |

### Configuration
| Topic | URL |
|-------|-----|
| Reference Azure Batch analytics events and alerts | https://learn.microsoft.com/en-us/azure/batch/batch-analytics |
| Configure Azure Batch application packages for node deployment | https://learn.microsoft.com/en-us/azure/batch/batch-application-packages |
| Configure methods to copy applications and data to Batch nodes | https://learn.microsoft.com/en-us/azure/batch/batch-applications-to-pool-nodes |
| Configure autoscaling for Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/batch-automatic-scaling |
| Use Azure Batch task runtime environment variables | https://learn.microsoft.com/en-us/azure/batch/batch-compute-node-environment-variables |
| Configure container isolation and data paths in Batch tasks | https://learn.microsoft.com/en-us/azure/batch/batch-container-isolation-task |
| Configure and run container workloads on Azure Batch | https://learn.microsoft.com/en-us/azure/batch/batch-docker-container-workloads |
| Interpret Azure Batch pool autoscale event details | https://learn.microsoft.com/en-us/azure/batch/batch-pool-autoscale-event |
| Interpret Azure Batch pool create event schema | https://learn.microsoft.com/en-us/azure/batch/batch-pool-create-event |
| Interpret Azure Batch pool delete complete event | https://learn.microsoft.com/en-us/azure/batch/batch-pool-delete-complete-event |
| Interpret Azure Batch pool delete start event | https://learn.microsoft.com/en-us/azure/batch/batch-pool-delete-start-event |
| Interpret Azure Batch pool resize complete event | https://learn.microsoft.com/en-us/azure/batch/batch-pool-resize-complete-event |
| Interpret Azure Batch pool resize start event | https://learn.microsoft.com/en-us/azure/batch/batch-pool-resize-start-event |
| Update Azure Batch pool properties safely | https://learn.microsoft.com/en-us/azure/batch/batch-pool-update-properties |
| Configure VM sizes and images for Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/batch-pool-vm-sizes |
| Use Azure Compute Gallery images for Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/batch-sig-images |
| Interpret Azure Batch task complete event schema | https://learn.microsoft.com/en-us/azure/batch/batch-task-complete-event |
| Interpret Azure Batch task fail event schema | https://learn.microsoft.com/en-us/azure/batch/batch-task-fail-event |
| Interpret Azure Batch task schedule fail event | https://learn.microsoft.com/en-us/azure/batch/batch-task-schedule-fail-event |
| Interpret Azure Batch task start event schema | https://learn.microsoft.com/en-us/azure/batch/batch-task-start-event |
| Configure Auto OS Upgrade for Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/batch-upgrade-policy |
| Configure and monitor extensions on Batch pool nodes | https://learn.microsoft.com/en-us/azure/batch/create-pool-extensions |
| Configure monitoring and metrics for Azure Batch with Azure Monitor | https://learn.microsoft.com/en-us/azure/batch/monitor-batch |
| Use Azure Batch monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/batch/monitor-batch-reference |
| Configure SSH and RDP endpoints on Azure Batch nodes | https://learn.microsoft.com/en-us/azure/batch/pool-endpoint-configuration |
| Create and use Azure Batch resource files on VMs | https://learn.microsoft.com/en-us/azure/batch/resource-files |
| Enable simplified compute node communication in Azure Batch | https://learn.microsoft.com/en-us/azure/batch/simplified-compute-node-communication |
| Configure Batch pools without public IP addresses | https://learn.microsoft.com/en-us/azure/batch/simplified-node-communication-pool-no-public-ip |

### Deployment
| Topic | URL |
|-------|-----|
| Move an Azure Batch account to another region | https://learn.microsoft.com/en-us/azure/batch/account-move |
| Set up Azure Pipelines CI/CD for Batch HPC deployments | https://learn.microsoft.com/en-us/azure/batch/batch-ci-cd |
| Run Azure Batch jobs end-to-end using CLI templates | https://learn.microsoft.com/en-us/azure/batch/batch-cli-templates |
| Migrate Azure Batch custom image pools to Azure Compute Gallery | https://learn.microsoft.com/en-us/azure/batch/batch-custom-image-pools-to-azure-compute-gallery-migration-guide |
| Create Azure Batch custom image pools from managed images | https://learn.microsoft.com/en-us/azure/batch/batch-custom-images |
| Migrate Azure Batch pools to simplified node communication | https://learn.microsoft.com/en-us/azure/batch/batch-pools-to-simplified-compute-node-communication-model-migration-guide |
| Migrate Azure Batch low-priority VMs to Spot VMs | https://learn.microsoft.com/en-us/azure/batch/low-priority-vms-retirement-migration-guide |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Manage Azure Batch with Azure CLI commands | https://learn.microsoft.com/en-us/azure/batch/batch-cli-get-started |
| Build an Azure Batch client using the JavaScript SDK | https://learn.microsoft.com/en-us/azure/batch/batch-js-get-started |
| Manage Azure Batch accounts programmatically with .NET | https://learn.microsoft.com/en-us/azure/batch/batch-management-dotnet |
| Manage Azure Batch resources with PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/batch/batch-powershell-cmdlets-get-started |
| Persist Batch output using .NET File Conventions library | https://learn.microsoft.com/en-us/azure/batch/batch-task-output-file-conventions |
| Use Batch service API to store task output in Azure Storage | https://learn.microsoft.com/en-us/azure/batch/batch-task-output-files |
| Instrument Azure Batch .NET apps with Application Insights | https://learn.microsoft.com/en-us/azure/batch/monitor-application-insights |
| Mount Azure Files shares on Azure Batch nodes | https://learn.microsoft.com/en-us/azure/batch/pool-file-shares |
| Mount virtual file systems on Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/virtual-file-mount |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand Azure Batch service quotas and limits | https://learn.microsoft.com/en-us/azure/batch/batch-quota-limit |

### Security
| Topic | URL |
|-------|-----|
| Rotate shared keys for Azure Batch accounts | https://learn.microsoft.com/en-us/azure/batch/account-key-rotation |
| Enable automatic certificate rotation using Batch managed identities | https://learn.microsoft.com/en-us/azure/batch/automatic-certificate-rotation |
| Authenticate Azure Batch services with Microsoft Entra ID | https://learn.microsoft.com/en-us/azure/batch/batch-aad-auth |
| Use Microsoft Entra ID with Azure Batch Management API | https://learn.microsoft.com/en-us/azure/batch/batch-aad-auth-management |
| Encrypt Azure Batch data with customer-managed keys | https://learn.microsoft.com/en-us/azure/batch/batch-customer-managed-key |
| Configure Azure RBAC roles for Azure Batch accounts | https://learn.microsoft.com/en-us/azure/batch/batch-role-based-access-control |
| Configure Azure Batch task user accounts securely | https://learn.microsoft.com/en-us/azure/batch/batch-user-accounts |
| Provision Azure Batch pools in virtual networks | https://learn.microsoft.com/en-us/azure/batch/batch-virtual-network |
| Securely access Azure Key Vault from Azure Batch | https://learn.microsoft.com/en-us/azure/batch/credential-access-key-vault |
| Enable platform-managed disk encryption for Batch pools | https://learn.microsoft.com/en-us/azure/batch/disk-encryption |
| Manage Azure Batch private endpoint connections | https://learn.microsoft.com/en-us/azure/batch/manage-private-endpoint-connections |
| Configure managed identities on Azure Batch pools | https://learn.microsoft.com/en-us/azure/batch/managed-identity-pools |
| Associate Azure Batch accounts with network security perimeters | https://learn.microsoft.com/en-us/azure/batch/network-security-perimeter |
| Apply built-in Azure Policy definitions for Batch | https://learn.microsoft.com/en-us/azure/batch/policy-reference |
| Configure Azure Batch private endpoints with Private Link | https://learn.microsoft.com/en-us/azure/batch/private-connectivity |
| Configure public network access and IP rules for Azure Batch | https://learn.microsoft.com/en-us/azure/batch/public-network-access |
| Apply security best practices to Azure Batch | https://learn.microsoft.com/en-us/azure/batch/security-best-practices |
| Map Azure Batch to Azure Policy compliance controls | https://learn.microsoft.com/en-us/azure/batch/security-controls-policy |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Diagnose and handle Azure Batch job and task errors | https://learn.microsoft.com/en-us/azure/batch/batch-job-task-error-checking |
| Diagnose and avoid Azure Batch pool and node errors | https://learn.microsoft.com/en-us/azure/batch/batch-pool-node-error-checking |
| Diagnose and handle Azure Batch task and job errors | https://learn.microsoft.com/en-us/azure/batch/error-handling |

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
