---
name: azure-netapp-files
description: Expert knowledge for Azure Netapp Files development including best practices, configuration, limits & quotas, integrations & coding patterns, deployment, troubleshooting, architecture & design patterns, security, and comparing x vs. y. Use when building, debugging, or optimizing Azure Netapp Files applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Netapp Files Skill

This skill provides expert guidance for Azure Netapp Files development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design Azure NetApp Files network architecture and connectivity | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-network-topologies |
| Use Azure NetApp Files backup for long-term data protection | https://learn.microsoft.com/en-us/azure/azure-netapp-files/backup-introduction |
| Design solutions with Azure NetApp Files cache volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/cache-volumes |
| Choose Azure NetApp Files data protection and disaster recovery options | https://learn.microsoft.com/en-us/azure/azure-netapp-files/data-protection-disaster-recovery-options |
| Choose data migration options into Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/migrate-data |
| Design Azure VMware Solution datastores with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-azure-vmware-solution-datastore |
| Select Azure NetApp Files replication model for reliability | https://learn.microsoft.com/en-us/azure/azure-netapp-files/replication |

### Best Practices
| Topic | URL |
|-------|-----|
| Add SAP HANA hosts with Azure NetApp Files volume groups | https://learn.microsoft.com/en-us/azure/azure-netapp-files/application-volume-group-add-hosts |
| Apply practical tips when using AzAcSnap | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-tips |
| Create and configure NFS volumes in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes |
| Create SMB3 volumes in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-create-volumes-smb |
| Optimize Azure NetApp Files volume performance and throughput | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-performance-considerations |
| Run performance benchmark tests on Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-performance-metrics-volumes |
| Improve SMB performance with Azure NetApp Files best practices | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-smb-performance |
| Use Azure NetApp Files cool access for inactive data | https://learn.microsoft.com/en-us/azure/azure-netapp-files/cool-access-introduction |
| Design DNS for reliable Azure NetApp Files access | https://learn.microsoft.com/en-us/azure/azure-netapp-files/domain-name-system-concept |
| Enable SMB Continuous Availability for supported workloads | https://learn.microsoft.com/en-us/azure/azure-netapp-files/enable-continuous-availability-existing-smb |
| Use local NFS users with LDAP in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/lightweight-directory-access-protocol-local-users |
| Configure LDAP name mapping rules for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/lightweight-directory-access-protocol-name-mapping |
| Configure LDAP schemas for Azure NetApp Files integration | https://learn.microsoft.com/en-us/azure/azure-netapp-files/lightweight-directory-access-protocol-schemas |
| Manage NFS group memberships and supplemental groups in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/network-file-system-group-memberships |
| Plan performance when using Azure NetApp Files cool access | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-considerations-cool-access |
| Optimize NFS session slots and concurrency for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-concurrency-session-slots |
| Apply Linux direct I/O best practices for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-direct-io |
| Tune Linux filesystem cache for Azure NetApp Files workloads | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-filesystem-cache |
| Configure Linux NFS mount options for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-mount-options |
| Tune Linux NFS read-ahead and cache for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-linux-nfs-read-ahead |
| Run high-performance Oracle databases on multiple Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-oracle-multiple-volumes |
| Optimize Oracle database performance on single Azure NetApp Files volume | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-oracle-single-volumes |
| Select Azure VM SKUs for optimal Azure NetApp Files performance | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-virtual-machine-sku |
| Implement Azure Virtual Desktop with Azure NetApp Files best practices | https://learn.microsoft.com/en-us/azure/azure-netapp-files/solutions-windows-virtual-desktop |
| Safely update Terraform-managed Azure NetApp Files resources | https://learn.microsoft.com/en-us/azure/azure-netapp-files/terraform-manage-volume |
| Apply Azure NetApp Files performance testing methodology | https://learn.microsoft.com/en-us/azure/azure-netapp-files/testing-methodology |
| Plan Active Directory sites for Azure NetApp Files workloads | https://learn.microsoft.com/en-us/azure/azure-netapp-files/understand-guidelines-active-directory-domain-service-site |
| Plan and manage Azure NetApp Files volume hard quotas | https://learn.microsoft.com/en-us/azure/azure-netapp-files/volume-hard-quota-guidelines |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Oracle dNFS vs kernel NFS on Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-oracle-database |
| Evaluate SQL Server TCO using Azure NetApp Files vs block storage | https://learn.microsoft.com/en-us/azure/azure-netapp-files/solutions-benefits-azure-netapp-files-sql-server |

### Configuration
| Topic | URL |
|-------|-----|
| Meet requirements for SAP HANA application volume groups on Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/application-volume-group-considerations |
| Satisfy requirements for Oracle application volume groups on Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/application-volume-group-oracle-considerations |
| Configure azacsnap delete command for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-delete |
| Configure azacsnap details command for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-details |
| Use azacsnap restore command with NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-restore |
| Configure azacsnap runbefore and runafter hooks | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-runbefore-runafter |
| Configure databases for AzAcSnap with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-configure-database |
| Configure Azure storage and identities for AzAcSnap | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-configure-storage |
| Set up AzAcSnap preview features for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-preview |
| Configure NFS export policies for Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-export-policy |
| Configure NFSv4.1 ID domain for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-configure-nfsv41-domain |
| Delegate a subnet to Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-delegate-subnet |
| Register NetApp resource provider for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-register |
| Create capacity pools for Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-set-up-capacity-pool |
| Meet requirements for Azure NetApp Files backup | https://learn.microsoft.com/en-us/azure/azure-netapp-files/backup-requirements-considerations |
| Configure Oracle application volume groups using Azure NetApp REST API | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-application-volume-oracle-api |
| Configure Azure NetApp Files cache volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-cache-volumes |
| Configure LDAP directory servers for Azure NetApp Files NFS | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-directory-server |
| Configure NFSv4.1 Kerberos encryption for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-kerberos-encryption |
| Configure Standard and Basic network features for NetApp volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-network-features |
| Configure Linux NFS clients for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-nfs-clients |
| Set Unix permissions and chown mode on NetApp NFS volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-unix-permissions-change-ownership-mode |
| Configure Azure Virtual WAN connectivity for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-virtual-wan |
| Convert Azure NetApp Files NFS volumes between v3 and v4.1 | https://learn.microsoft.com/en-us/azure/azure-netapp-files/convert-nfsv3-nfsv41 |
| Configure cross-zone replication for NetApp volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/create-cross-zone-replication |
| Manage cross-zone-region replication for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/cross-zone-region-replication-configure |
| Use tags to manage Azure NetApp Files billing | https://learn.microsoft.com/en-us/azure/azure-netapp-files/manage-billing-tags |
| Manage manual QoS capacity pools in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/manage-manual-qos-capacity-pool |
| Configure Azure NetApp Files object REST API access | https://learn.microsoft.com/en-us/azure/azure-netapp-files/object-rest-api-access-configure |
| Satisfy configuration requirements for Azure NetApp Files replication | https://learn.microsoft.com/en-us/azure/azure-netapp-files/replication-requirements |
| Configure and use Azure NetApp Files snapshots | https://learn.microsoft.com/en-us/azure/azure-netapp-files/snapshots-introduction |

### Deployment
| Topic | URL |
|-------|-----|
| Perform disaster recovery with AzAcSnap on Azure Large Instances | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-disaster-recovery |
| Install AzAcSnap for Azure NetApp Files and Large Instances | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-installation |
| Deploy Oracle application volume groups with ARM templates | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-application-volume-oracle-azure-resource-manager |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Execute AzAcSnap backup command for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-backup |
| Run AzAcSnap configure command for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-configure |
| Use AzAcSnap test command with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-cmd-ref-test |
| Use Azure NetApp Files REST API endpoints | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-develop-with-rest-api |
| Configure SAP HANA application volume groups via REST API | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-application-volume-group-sap-hana-api |
| Call NetApp Files REST API using PowerShell | https://learn.microsoft.com/en-us/azure/azure-netapp-files/develop-rest-api-powershell |
| Use Azure NetApp Files with integrated Azure services | https://learn.microsoft.com/en-us/azure/azure-netapp-files/faq-integration |
| Access NetApp Files object REST API with S3-compatible clients | https://learn.microsoft.com/en-us/azure/azure-netapp-files/object-rest-api-browser |
| Integrate Azure Databricks with NetApp Files object REST API | https://learn.microsoft.com/en-us/azure/azure-netapp-files/object-rest-api-databricks |
| Connect OneLake shortcuts to Azure NetApp Files via object REST API | https://learn.microsoft.com/en-us/azure/azure-netapp-files/object-rest-api-onelake |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use extended NFS auxiliary group limits in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/auxiliary-groups |
| Reference Azure NetApp Files resource limits and quota increases | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-resource-limits |
| Understand Azure NetApp Files service level throughput limits | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-service-levels |
| Apply resizing limits for Azure NetApp Files cache volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/cache-volumes-resize-guidelines |
| Enable AD DS LDAP with extended groups for NFS volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-ldap-extended-groups |
| Configure user and group quotas on Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/default-individual-user-group-quotas-introduction |
| Estimate directory size growth from metadata in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/directory-sizes-concept |
| Check NFS protocol limits for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/faq-nfs |
| Understand Azure NetApp Files performance limits | https://learn.microsoft.com/en-us/azure/azure-netapp-files/faq-performance |
| Review SMB protocol limits on Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/faq-smb |
| Understand size and capacity limits for large Azure NetApp Files volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/large-volumes |
| Apply requirements and size ranges for Azure NetApp Files large volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/large-volumes-requirements-considerations |
| Use maxfiles limits and avoid inode-related space errors in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/maxfiles-concept |
| Use Azure NetApp Files datastore performance benchmarks for Azure VMware Solution | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-benchmarks-azure-vmware-solution |
| Use Azure NetApp Files Linux performance benchmarks | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-benchmarks-linux |
| Use breakthrough mode performance for large Linux volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-large-volume-breakthrough-mode-linux |
| Plan Azure NetApp Files large volume performance for Linux | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-large-volumes-linux |
| Understand Azure NetApp Files regional capacity quotas | https://learn.microsoft.com/en-us/azure/azure-netapp-files/regional-capacity-quota |
| Apply file and path length limits in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/understand-path-lengths |
| Use volume language and character set limits in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/understand-volume-languages |

### Security
| Topic | URL |
|-------|-----|
| Apply Azure Policy definitions to govern Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-policy-definitions |
| Configure NFSv4.1 ACL-based security in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-access-control-lists |
| Configure customer-managed keys for NetApp Files encryption | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-customer-managed-keys |
| Use HSM-backed customer-managed keys for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-customer-managed-keys-hardware |
| Configure AD DS LDAP over TLS for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-ldap-over-tls |
| Configure Azure NetApp Files control plane security options | https://learn.microsoft.com/en-us/azure/azure-netapp-files/control-plane-security |
| Configure Active Directory connections for Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/create-active-directory-connections |
| Configure cross-tenant customer-managed keys for NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/customer-managed-keys-cross-tenant |
| Configure and use Azure NetApp Files data plane security features | https://learn.microsoft.com/en-us/azure/azure-netapp-files/data-plane-security |
| Disable NFS showmount for Azure NetApp Files security | https://learn.microsoft.com/en-us/azure/azure-netapp-files/disable-showmount |
| Apply Azure NetApp Files security and access settings | https://learn.microsoft.com/en-us/azure/azure-netapp-files/faq-security |
| Join Linux VMs to Microsoft Entra Domain Services | https://learn.microsoft.com/en-us/azure/azure-netapp-files/join-active-directory-domain |
| Manage SMB share ACL permissions in Azure NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/manage-smb-share-access-control-lists |
| Modify Azure NetApp Files Active Directory connections | https://learn.microsoft.com/en-us/azure/azure-netapp-files/modify-active-directory-connections |
| Evaluate Kerberos security and performance on Azure NetApp Files NFSv4.1 | https://learn.microsoft.com/en-us/azure/azure-netapp-files/performance-impact-kerberos |
| Configure advanced ransomware protection in NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/ransomware-configure |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot AzAcSnap communication and test failures | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-troubleshoot |
| Fix Azure NetApp Files Resource Provider errors | https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-troubleshoot-resource-provider-errors |
| Fix application volume group issues in NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-application-volume-groups |
| Resolve Azure NetApp Files capacity pool errors | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-capacity-pools |
| Resolve cross-region replication errors in NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-cross-region-replication |
| Troubleshoot customer-managed key encryption in NetApp Files | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-customer-managed-keys |
| Troubleshoot NetApp Files with Diagnose and Solve | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-diagnose-solve-problems |
| Break and resolve file locks in NetApp volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-file-locks |
| Troubleshoot NetApp Files snapshot policy errors | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-snapshot-policies |
| Troubleshoot LDAP user access on NetApp volumes | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-user-access-ldap |
| Troubleshoot Azure NetApp Files volume errors | https://learn.microsoft.com/en-us/azure/azure-netapp-files/troubleshoot-volumes |

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
