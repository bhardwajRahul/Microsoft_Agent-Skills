---
name: azure-vmware
description: Expert knowledge for Azure Vmware development including configuration, architecture & design patterns, security, limits & quotas, integrations & coding patterns, troubleshooting, best practices, and deployment. Use when building, debugging, or optimizing Azure Vmware applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Vmware Skill

This skill provides expert guidance for Azure Vmware development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use API Management with Azure VMware workloads | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-api-management |
| Design internet connectivity for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-design-public-internet-access |
| Integrate Azure VMware into hub-and-spoke networks | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-hub-and-spoke |
| Choose VMware HCX migration options for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-migrate |
| Plan network design for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-network-design-considerations |
| Plan storage and vSAN usage in Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-storage |
| Design vSAN stretched clusters for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-stretched-clusters |
| Design and deploy VMware Horizon on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/azure-vmware-solution-horizon |
| Architect GitHub Enterprise Server on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-github-enterprise-server |
| Design networking for VMware Cloud Director tenants on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/enable-vmware-vcd-with-azure-network |

### Best Practices
| Topic | URL |
|-------|-----|
| Optimize NSX scale and performance for HCX migrations | https://learn.microsoft.com/en-us/azure/azure-vmware/azure-vmware-solution-nsx-scale-and-performance-recommendations-for-vmware-hcx |
| Use HCX Mobility Optimized Networking with AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/vmware-hcx-mon-guidance |

### Configuration
| Topic | URL |
|-------|-----|
| Enable guest management and extensions on Arc-enabled AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/arc-enable-guest-management |
| Configure networking and interconnectivity for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-networking |
| Configure Cloud Backup policies for ANF datastores and AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/backup-azure-netapp-files-datastores-vms |
| Configure VM-level backups for AVS using Azure Backup Server | https://learn.microsoft.com/en-us/azure/azure-vmware/backup-azure-vmware-solution-virtual-machines |
| Configure alerts and metrics for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-alerts-for-azure-vmware-solution |
| Create Azure Monitor resource health alerts for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-azure-monitor-for-resource-health-for-azure-vmware-solution |
| Configure new performance and health metrics for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-azure-vmware-solution-metrics |
| Manage datastores and VMDKs with Cloud Backup for VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-cloud-backup-virtual-machine |
| Configure DHCP services for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-dhcp-azure-vmware-solution |
| Configure DNS forwarder and private DNS for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-dns-azure-vmware-solution |
| Create VMware HCX network extensions for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-hcx-network-extension |
| Enable DHCP to non-NSX servers on HCX L2 stretch | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-l2-stretched-vmware-hcx-networks |
| Configure NSX network segments via Azure VMware portal | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-nsx-network-components-azure-portal |
| Configure port mirroring for Azure VMware traffic analysis | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-port-mirroring-azure-vmware-solution |
| Configure vSAN storage policies for Azure VMware Solution VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-storage-policy |
| Configure on-premises VMware HCX Connector for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-vmware-hcx |
| Configure diagnostic settings to collect VMware syslogs in AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-vmware-syslogs |
| Configure VMware vSAN settings on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-vsan |
| Configure Windows Server Failover Cluster on Azure VMware Solution vSAN | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-windows-server-failover-cluster |
| Configure AVS Interconnect between private clouds | https://learn.microsoft.com/en-us/azure/azure-vmware/connect-multiple-private-clouds-same-region |
| Deploy JetStream DR for Azure VMware Solution workloads | https://learn.microsoft.com/en-us/azure/azure-vmware/deploy-disaster-recovery-using-jetstream |
| Deploy Zerto disaster recovery for on-premises and AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/deploy-zerto-disaster-recovery |
| Configure or disable internet routing in Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/disable-internet-access |
| Deploy VMware Site Recovery Manager for AVS disaster recovery | https://learn.microsoft.com/en-us/azure/azure-vmware/disaster-recovery-using-vmware-site-recovery-manager |
| Enable and configure Managed SNAT for AVS workloads | https://learn.microsoft.com/en-us/azure/azure-vmware/enable-managed-snat-for-workloads |
| Enable NSX Edge public IPs for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/enable-public-ip-nsx-edge |
| Enable SQL Server Azure Hybrid Benefit on AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/enable-sql-azure-hybrid-benefit |
| Install Cloud Backup for Virtual Machines on AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/install-cloud-backup-virtual-machines |
| Install and activate VMware HCX on Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/install-vmware-hcx |
| Manage Arc resource bridge and credentials for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/manage-arc-enabled-azure-vmware-solution |
| Configure automatic peering sync for AVS Gen 2 | https://learn.microsoft.com/en-us/azure/azure-vmware/native-auto-peering-sync |
| Configure DNS forward lookup zones for AVS Gen 2 | https://learn.microsoft.com/en-us/azure/azure-vmware/native-dns-forward-lookup-zone |
| Restore AVS virtual machines using Cloud Backup | https://learn.microsoft.com/en-us/azure/azure-vmware/restore-azure-netapp-files-vms |
| Restore guest files and folders from AVS VM backups | https://learn.microsoft.com/en-us/azure/azure-vmware/restore-guest-files-folders |
| Set up Azure Backup Server to protect AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/set-up-backup-server-for-azure-vmware-solution |
| Set up jump box access to AVS vCenter | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-access-private-cloud |
| Configure networking and ExpressRoute for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-configure-networking |
| Configure ExpressRoute Global Reach to Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-expressroute-global-reach-private-cloud |
| Network planning checklist for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-network-checklist |
| Add NSX network segments for AVS virtual machines | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-nsx-t-network-segment |
| Create additional NSX Tier-1 gateways in AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-nsx-tier-1-gateway |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Arc-enabled VMware vSphere for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/deploy-arc-for-azure-vmware-solution |
| Remove Arc-enabled AVS vSphere resources from Azure | https://learn.microsoft.com/en-us/azure/azure-vmware/remove-arc-enabled-azure-vmware-solution-vsphere-resources-from-azure |
| Plan and configure self-service maintenance for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/self-service-maintenance-orchestration |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Attach Azure NetApp Files NFS datastores to AVS hosts | https://learn.microsoft.com/en-us/azure/azure-vmware/attach-azure-netapp-files-to-azure-vmware-solution-hosts |
| Configure Azure Elastic SAN iSCSI datastores for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-azure-elastic-san |
| Use Azure Native Pure Storage Cloud with AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-azure-native-pure-storage-cloud |
| Configure Pure Cloud Block Store with Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-pure-cloud-block-store |
| Configure vWAN site-to-site VPN for Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-site-to-site-vpn-gateway |
| Configure VMware Cloud Director Service on Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-vmware-cloud-director-service-azure-vmware-solution |
| Integrate Traffic Manager with Azure VMware workloads | https://learn.microsoft.com/en-us/azure/azure-vmware/deploy-traffic-manager-balance-workloads |
| Forward AVS VMware syslogs to log management via Logic Apps | https://learn.microsoft.com/en-us/azure/azure-vmware/logs-via-logic-app |
| Use Azure NetApp Files NFS shares with AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/netapp-files-with-azure-vmware-solution |
| Use VMware HCX Run Commands on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/use-hcx-run-commands |
| Configure VMware Aria Operations integration for AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/vrealize-operations-for-azure-vmware-solution |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review Azure VMware private cloud and cluster limits | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-private-clouds |
| Configure VMware vSAN ESA and host support on Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-vsan-esa |
| Plan external storage capacity for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/ecosystem-external-storage-solutions |
| Understand Azure VMware Solution host and cluster limits | https://learn.microsoft.com/en-us/azure/azure-vmware/introduction |
| Understand AVS Gen 2 routing architecture and limits | https://learn.microsoft.com/en-us/azure/azure-vmware/native-network-routing-architecture |
| Request and manage AVS host quota capacity | https://learn.microsoft.com/en-us/azure/azure-vmware/request-host-quota-azure-vmware-solution |
| Deploy AVS private cloud and understand host limits | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-create-private-cloud |
| Scale AVS clusters and understand service limits | https://learn.microsoft.com/en-us/azure/azure-vmware/tutorial-scale-private-cloud |

### Security
| Topic | URL |
|-------|-----|
| Configure identity and access roles in Azure VMware | https://learn.microsoft.com/en-us/azure/azure-vmware/architecture-identity |
| Integrate Defender for Cloud with Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/azure-security-integration |
| Configure customer-managed key encryption for AVS vSAN | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-customer-managed-keys |
| Set external LDAP identity source for NSX in AVS | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-external-identity-source-nsx-t |
| Configure external AD identity source for vCenter | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-identity-source-vcenter |
| Enable Trusted Launch and vTPM for AVS virtual machines | https://learn.microsoft.com/en-us/azure/azure-vmware/configure-virtual-trusted-platform-module |
| Configure Extended Security Updates on AVS VMs | https://learn.microsoft.com/en-us/azure/azure-vmware/extended-security-updates-windows-sql-server |
| Enable AVS Gen 2 service principal securely | https://learn.microsoft.com/en-us/azure/azure-vmware/native-first-party-principle-security |
| Manually configure AVS Gen 2 role assignments | https://learn.microsoft.com/en-us/azure/azure-vmware/native-role-assignment |
| Secure AVS web apps with Azure Application Gateway | https://learn.microsoft.com/en-us/azure/azure-vmware/protect-azure-vmware-solution-with-application-gateway |
| Rotate CloudAdmin credentials in Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/rotate-cloudadmin-credentials |
| Apply security best practices to Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/security-recommendations |
| Use Run Command and CloudAdmin role in Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-vmware/using-run-command |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve Azure VMware Solution known issues and workarounds | https://learn.microsoft.com/en-us/azure/azure-vmware/azure-vmware-solution-known-issues |
| Address known issues in AVS disaster recovery solutions | https://learn.microsoft.com/en-us/azure/azure-vmware/ecosystem-disaster-recovery-vms |
| Collect data and open support requests for AVS deployment failures | https://learn.microsoft.com/en-us/azure/azure-vmware/fix-deployment-failures |

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
