---
name: site-recovery
description: Expert knowledge for Site Recovery development including best practices, deployment, configuration, security, architecture & design patterns, integrations & coding patterns, troubleshooting, limits & quotas, and comparing x vs. y. Use when building, debugging, or optimizing Site Recovery applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Site Recovery Skill

This skill provides expert guidance for Site Recovery development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Enable DR for Storage Spaces Direct clusters in Azure | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-replication-s2d-vms |
| Hyper-V to Azure Site Recovery architecture | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-architecture |
| Plan migration from classic to modernized VMware DR | https://learn.microsoft.com/en-us/azure/site-recovery/move-from-classic-to-modernized-vmware-disaster-recovery |
| Modernized physical server to Azure DR architecture | https://learn.microsoft.com/en-us/azure/site-recovery/physical-server-azure-architecture-modernized |
| Design AD/DNS disaster recovery with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-active-directory |
| Plan VMware-to-Azure DR with Site Recovery Deployment Planner | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-deployment-planner |
| Implement Dynamics AX disaster recovery with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-dynamicsax |
| Configure IIS web app disaster recovery with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-iis |
| Retain Azure VM IP addresses during Site Recovery failover | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-retain-ip-azure-vm-failover |
| Set up SAP NetWeaver disaster recovery with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-sap |
| Protect multi-tier SharePoint with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-sharepoint |
| Plan SQL Server disaster recovery with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-sql |
| Analyze Site Recovery Deployment Planner report for VMware DR | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-vmware-deployment-planner-analyze-report |
| Protect Azure shared disk WSFC clusters with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/tutorial-shared-disk |
| Classic VMware to Azure Site Recovery architecture | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-architecture |
| Modernized VMware to Azure Site Recovery architecture | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-architecture-modernized |

### Best Practices
| Topic | URL |
|-------|-----|
| Use alternative VM size recommendations in failover | https://learn.microsoft.com/en-us/azure/site-recovery/alternative-vm-size-failover-flow |
| Choose and plan failback types in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-types-of-failback |
| Protect on-premises file servers with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/file-server-disaster-recovery |
| Guidance for Citrix XenDesktop/XenApp DR with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-citrix-xenapp-and-xendesktop |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure Migrate vs Site Recovery for migration | https://learn.microsoft.com/en-us/azure/site-recovery/migrate-overview |
| Interpret cost estimations from Site Recovery Deployment Planner | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-vmware-deployment-planner-cost-estimation |

### Configuration
| Topic | URL |
|-------|-----|
| Configure automatic Mobility service updates in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-autoupdate |
| Exclude Azure VM disks from Site Recovery via PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-exclude-disks |
| Enable Azure Site Recovery protection using Azure Policy | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-policy |
| Configure Site Recovery replication using private endpoints | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-replication-private-endpoints |
| Prepare migrated Azure VMs for Site Recovery DR | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-replicate-after-migration |
| Configure multiple IP address failover in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-multiple-ip-address-failover |
| Configure connectivity to Azure VMs after Site Recovery failover | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-on-premises-to-azure-networking |
| Assign public IPs after Site Recovery failover | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-public-ip-address-with-site-recovery |
| Set Mobility Service proxy settings for Azure-to-Azure DR | https://learn.microsoft.com/en-us/azure/site-recovery/configure-mobility-service-proxy-settings |
| Deploy and configure Azure Site Recovery replication appliance | https://learn.microsoft.com/en-us/azure/site-recovery/deploy-vmware-azure-replication-appliance-modernized |
| Configure migration from classic to modernized VMware protection | https://learn.microsoft.com/en-us/azure/site-recovery/how-to-move-from-classic-to-modernized-vmware-disaster-recovery |
| Configure on-premises disks via Site Recovery hydration | https://learn.microsoft.com/en-us/azure/site-recovery/hydration-process |
| Monitor Site Recovery with Azure Monitor Logs and queries | https://learn.microsoft.com/en-us/azure/site-recovery/monitor-log-analytics |
| Configure monitoring for Azure Site Recovery with Azure Monitor | https://learn.microsoft.com/en-us/azure/site-recovery/monitor-site-recovery |
| Use Azure Site Recovery monitoring data reference | https://learn.microsoft.com/en-us/azure/site-recovery/monitor-site-recovery-reference |
| Set up configuration server for physical server DR | https://learn.microsoft.com/en-us/azure/site-recovery/physical-azure-set-up-source |
| Manage configuration server for physical server protection | https://learn.microsoft.com/en-us/azure/site-recovery/physical-manage-configuration-server |
| Enable replication for on-premises physical servers (Modernized) | https://learn.microsoft.com/en-us/azure/site-recovery/physical-server-enable-replication |
| Migrate from deprecated IPConfig parameters in ASR cmdlets | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-ipconfig-cmdlet-parameter-deprecation |
| Configure network adapters for on-premises to Azure DR | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-manage-network-interfaces-on-premises-to-azure |
| Run Site Recovery Deployment Planner for VMware-to-Azure | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-vmware-deployment-planner-run |
| Deploy Azure Site Recovery configuration server for VMware | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-deploy-configuration-server |
| Enable VMware VMs replication to Azure with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-enable-replication |
| Configure replication for newly added VMware VM disks | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-enable-replication-added-disk |
| Install Linux master target server for VMware failback | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-install-linux-master-target |
| Manage Site Recovery configuration server for VMware DR | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-manage-configuration-server |
| Add and manage vCenter servers in Azure Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-manage-vcenter |
| Configure scale-out process servers for VMware DR | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-process-server-scale |
| Configure replication policies for VMware disaster recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-replication |
| Configure source environment for VMware-to-Azure Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-source |

### Deployment
| Topic | URL |
|-------|-----|
| Use ARM templates to deploy Azure Site Recovery resources | https://learn.microsoft.com/en-us/azure/site-recovery/asr-arm-templates |
| Replicate proximity placement group VMs with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/how-to-enable-replication-proximity-placement-groups |
| Review Hyper-V Site Recovery cost estimation report | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-deployment-planner-cost-estimation |
| Run Hyper-V deployment planner for Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-deployment-planner-run |
| Plan VMware to Azure Site Recovery capacity | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-plan-capacity-vmware |
| Prepare VMware VMs for reprotection and failback | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-prepare-failback |
| Set up Azure process server for VMware failback | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-process-server-azure |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Automate Azure VM disaster recovery with PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-powershell |
| Configure Azure shared disk DR using PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-tutorial-enable-replication-shared-disk |
| Enable accelerated networking in Site Recovery DR | https://learn.microsoft.com/en-us/azure/site-recovery/azure-vm-disaster-recovery-with-accelerated-networking |
| Integrate ExpressRoute with Azure Site Recovery DR | https://learn.microsoft.com/en-us/azure/site-recovery/azure-vm-disaster-recovery-with-expressroute |
| Use ExpressRoute with Azure Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-expressroute-with-site-recovery |
| Use Azure Traffic Manager with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-traffic-manager-with-site-recovery |
| Automate Hyper-V VM replication to Azure with PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-powershell-resource-manager |
| Automate Hyper-V VM replication to Azure with PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-powershell-resource-manager |
| Integrate Azure Automation runbooks into recovery plans | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-runbook-automation |
| Replicate Extended Zone VMs to parent region via PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/tutorial-replicate-vms-edge-zone-to-azure-region |
| Use VMM cleanup script to unregister Site Recovery server | https://learn.microsoft.com/en-us/azure/site-recovery/unregister-vmm-server-script |
| Configure VMware disaster recovery to Azure using PowerShell | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-disaster-recovery-powershell |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Quickly enable Azure VM DR with churn limits | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-quickstart |
| Check Azure-to-Azure Site Recovery support and limits | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-support-matrix |
| High churn limits for Azure VM Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-azure-to-azure-high-churn-support |
| Check Hyper-V to Azure Site Recovery support and limits | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-support-matrix |
| Use Deployment Planner for Hyper-V to Azure DR sizing | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-deployment-planner-overview |
| Review replication appliance requirements for VMware DR | https://learn.microsoft.com/en-us/azure/site-recovery/replication-appliance-support-matrix |
| Understand shared disk support for Azure VM DR | https://learn.microsoft.com/en-us/azure/site-recovery/shared-disk-support-matrix |
| Use Azure Site Recovery with Azure Backup safely | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-backup-interoperability |
| Review version history and limitations of Site Recovery Deployment Planner | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-deployment-planner-history |
| Understand Azure Site Recovery capabilities and limits | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-overview |
| Review VMware and physical server DR support matrix | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-physical-azure-support-matrix |
| Plan large-scale VMware/physical disaster recovery deployments | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-physical-large-deployment |
| Understand Mobility service resource impact and usage | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-physical-mobility-service-overview |

### Security
| Topic | URL |
|-------|-----|
| Configure Site Recovery for Azure Disk Encryption VMs | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-replication-ade-vms |
| Replicate CMK-encrypted Azure disks with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-replication-cmk-disks |
| Apply Network Security Groups with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/concepts-network-security-group-with-site-recovery |
| Remediate deprecated Site Recovery data encryption | https://learn.microsoft.com/en-us/azure/site-recovery/encryption-feature-deprecation |
| Migrate Azure Site Recovery runbooks to managed identity | https://learn.microsoft.com/en-us/azure/site-recovery/how-to-migrate-run-as-accounts-managed-identity |
| Configure Site Recovery replication with private endpoints | https://learn.microsoft.com/en-us/azure/site-recovery/hybrid-how-to-enable-replication-private-endpoints |
| Apply Azure RBAC roles for Site Recovery management | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-role-based-linked-access-control |
| Configure TLS usage in Azure Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/transport-layer-security |
| Configure VMware to Azure replication with least-privilege roles | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-replication-tutorial-modernized |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure Site Recovery protection errors | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-protection-errors |
| Resolve other Azure Site Recovery VM issues | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-troubleshoot-errors |
| Troubleshoot Azure Site Recovery network connectivity | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-troubleshoot-network-connectivity |
| Troubleshoot Azure VM replication with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-troubleshoot-replication |
| Fix Azure Site Recovery VM replication errors | https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-virtual-machine-errors |
| Resolve Hyper-V to Azure replication issues in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-troubleshoot |
| Fix Azure Site Recovery VM agent and extension issues | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-extension-troubleshoot |
| Troubleshoot Azure Site Recovery failover to Azure | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-failover-to-azure-troubleshoot |
| Use Site Recovery dashboard and alerts to troubleshoot replication | https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-monitor-and-troubleshoot |
| Troubleshoot Azure Site Recovery configuration server issues | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-configuration-server |
| Troubleshoot VMware failback and reprotection with Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-failback-reprotect |
| Troubleshoot Mobility Service push installation failures | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-push-install |
| Troubleshoot VMware and physical server replication to Azure | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-replication |
| Resolve Azure Site Recovery error 78144 for app-consistent points | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-replication-vss-installation-failure-behaviors |
| Resolve Azure Site Recovery Provider upgrade failures | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-upgrade-failures |
| Diagnose VMware vCenter discovery failures in Azure Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-azure-troubleshoot-vcenter-discovery-failures |
| Fix Azure Site Recovery process server replication issues | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-physical-azure-troubleshoot-process-server |
| Troubleshoot VMware replication appliance health in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-troubleshoot-appliance-health-issue |
| Fix VMware mobility agent health errors in Site Recovery | https://learn.microsoft.com/en-us/azure/site-recovery/vmware-troubleshoot-mobility-agent-health |

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
