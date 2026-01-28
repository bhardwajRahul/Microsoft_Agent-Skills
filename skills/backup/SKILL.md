---
name: backup
description: Expert knowledge for Backup development including configuration, limits & quotas, architecture & design patterns, comparing x vs. y, integrations & coding patterns, troubleshooting, security, best practices, and deployment. Use when building, debugging, or optimizing Backup applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Backup Skill

This skill provides expert guidance for Backup development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Understand Azure Backup architecture for SAP HANA | https://learn.microsoft.com/en-us/azure/backup/azure-backup-architecture-for-sap-hana-backup |

### Best Practices
| Topic | URL |
|-------|-----|
| Configure DPM to back up Exchange to Azure | https://learn.microsoft.com/en-us/azure/backup/backup-azure-backup-exchange-server |
| Back up SQL Server to Azure using DPM | https://learn.microsoft.com/en-us/azure/backup/backup-azure-backup-sql |
| Prepare DPM server for Azure Backup workloads | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dpm-introduction |
| Apply Azure VM backup best practices with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-introduction |
| Back up SQL Always On availability groups with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-sql-server-on-availability-groups |
| Apply Azure Backup best practices for cloud workloads | https://learn.microsoft.com/en-us/azure/backup/guidance-best-practices |
| Restore SAP ASE databases on Azure VMs with special master DB handling | https://learn.microsoft.com/en-us/azure/backup/sap-ase-database-restore |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Estimate and compare Azure Backup costs across workloads | https://learn.microsoft.com/en-us/azure/backup/azure-backup-pricing |

### Configuration
| Topic | URL |
|-------|-----|
| Use MARS agent restore options for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/about-restore-microsoft-azure-recovery-services |
| Create vaulted backup policy for Data Lake Storage | https://learn.microsoft.com/en-us/azure/backup/azure-data-lake-storage-backup-create-policy-quickstart |
| Set up vaulted backups for Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/backup/azure-data-lake-storage-backup-overview |
| Configure Azure Backup for Elastic SAN volumes | https://learn.microsoft.com/en-us/azure/backup/azure-elastic-san-backup-overview |
| Configure snapshot and vaulted backups for Azure Files | https://learn.microsoft.com/en-us/azure/backup/azure-file-share-backup-overview |
| Configure Azure Backup for AKS cluster and volume protection | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-backup-overview |
| Configure AKS backups using Azure Backup in portal | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup |
| Meet prerequisites and trusted access for AKS backup | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup-concept |
| Configure vault diagnostics at scale with Azure Policy | https://learn.microsoft.com/en-us/azure/backup/azure-policy-configure-diagnostics |
| Configure Azure Managed Disk backups in Azure Backup | https://learn.microsoft.com/en-us/azure/backup/back-up-managed-disks-tutorial |
| Use the MARS agent to back up on-premises data to Azure | https://learn.microsoft.com/en-us/azure/backup/backup-azure-about-mars |
| Define PostgreSQL backup policies via Data Protection REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-data-protection-use-rest-api-create-update-postgresql-policy |
| Configure backup for PostgreSQL Flexible Server in portal | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex |
| Manage PostgreSQL Flexible Server backups in Azure portal | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-manage |
| Create backup policies for PostgreSQL Flexible Server via REST | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-use-rest-api-create-update-policy |
| Remove dependencies and delete Recovery Services vaults | https://learn.microsoft.com/en-us/azure/backup/backup-azure-delete-vault |
| Configure diagnostic events for Azure Backup vaults | https://learn.microsoft.com/en-us/azure/backup/backup-azure-diagnostic-events |
| Use legacy Azure Backup diagnostics data model | https://learn.microsoft.com/en-us/azure/backup/backup-azure-diagnostics-mode-data-model |
| Configure application-consistent backups for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/backup/backup-azure-linux-app-consistent |
| Enable database-consistent snapshots with packaged scripts | https://learn.microsoft.com/en-us/azure/backup/backup-azure-linux-database-consistent-enhanced-pre-post |
| Manage and monitor Azure VM backups in Recovery Services vaults | https://learn.microsoft.com/en-us/azure/backup/backup-azure-manage-vms |
| Monitor and manage Azure Recovery Services vaults | https://learn.microsoft.com/en-us/azure/backup/backup-azure-manage-windows-server |
| Set up Azure Monitor alert notifications for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-monitor-alerts-notification |
| Configure Azure Monitor alerts for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-monitoring-alerts |
| Configure Azure Monitor Logs for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-monitoring-use-azuremonitor |
| Use resource-specific diagnostic data model for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-reports-data-model |
| Migrate Azure VM backups from standard to enhanced policy | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vm-migrate-enhanced-policy |
| Configure agentless multidisk crash-consistent VM backups | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-agentless-multi-disk-crash-consistent |
| Configure agentless crash-consistent backups for Azure VMs | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-agentless-multi-disk-crash-consistent-overview |
| Configure Enhanced backup policy for Azure VMs | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-enhanced-policy |
| Govern Azure backup compliance using Backup Center | https://learn.microsoft.com/en-us/azure/backup/backup-center-govern-environment |
| Monitor and operate backups at scale with Backup Center | https://learn.microsoft.com/en-us/azure/backup/backup-center-monitor-operate |
| Analyze backup trends and insights with Backup Center | https://learn.microsoft.com/en-us/azure/backup/backup-center-obtain-insights |
| Create and configure Azure Recovery Services vaults | https://learn.microsoft.com/en-us/azure/backup/backup-create-recovery-services-vault |
| Use ARM and Bicep templates for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-rm-template-samples |
| Configure vaulted blob backup policy in Azure portal | https://learn.microsoft.com/en-us/azure/backup/blob-backup-configure-quick |
| Configure continuous and vaulted backups for Azure Blobs | https://learn.microsoft.com/en-us/azure/backup/blob-backup-overview |
| Configure Azure Backup reporting with Log Analytics | https://learn.microsoft.com/en-us/azure/backup/configure-reports |
| Create and delete Azure Backup vaults | https://learn.microsoft.com/en-us/azure/backup/create-manage-backup-vault |
| Manage Azure Backup vault settings and workloads | https://learn.microsoft.com/en-us/azure/backup/manage-backup-vault |
| Configure telemetry settings in MABS | https://learn.microsoft.com/en-us/azure/backup/manage-telemetry |
| Use Azure Backup metrics to monitor backup health | https://learn.microsoft.com/en-us/azure/backup/metrics-overview |
| Modify Azure VM backup policy JSON via CLI | https://learn.microsoft.com/en-us/azure/backup/modify-vm-policy-cli |
| Monitor backups across estates with Backup Explorer | https://learn.microsoft.com/en-us/azure/backup/monitor-azure-backup-with-backup-explorer |
| Configure Azure Monitor for Azure Backup telemetry | https://learn.microsoft.com/en-us/azure/backup/monitor-backup |
| Reference for Azure Backup monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/backup/monitor-backup-reference |
| Azure Backup built-in Azure Policy definitions reference | https://learn.microsoft.com/en-us/azure/backup/policy-reference |
| Configure pre- and post-backup scripts in MABS | https://learn.microsoft.com/en-us/azure/backup/pre-backup-post-backup-scripts |
| Configure vaulted backup for AKS cluster via Azure Backup | https://learn.microsoft.com/en-us/azure/backup/quick-backup-aks |
| Create Azure Files backup policy in Azure portal | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-portal |
| Configure PostgreSQL Flexible Server backup policy via CLI | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-cli |
| Create backup policy for PostgreSQL Flexible Server in portal | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-portal |
| Create PostgreSQL Flexible Server backup policy using PowerShell | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-powershell |
| Set up Azure VM backup using Bicep configuration | https://learn.microsoft.com/en-us/azure/backup/quick-backup-vm-bicep-file |
| Configure Azure VM backup with ARM template parameters | https://learn.microsoft.com/en-us/azure/backup/quick-backup-vm-template |
| Install and configure Azure Backup extension on AKS | https://learn.microsoft.com/en-us/azure/backup/quick-install-backup-extension |
| Define AKS backup configuration via ARM templates | https://learn.microsoft.com/en-us/azure/backup/quick-kubernetes-backup-arm |
| Configure AKS vaulted backup using Bicep resources | https://learn.microsoft.com/en-us/azure/backup/quick-kubernetes-backup-bicep |
| Configure Azure Backup for SAP ASE (Sybase) on Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sap-ase-database-about |
| Configure Azure Backup for SAP HANA on Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sap-hana-database-about |
| Scripted configuration of file and folder backup policy with MARS | https://learn.microsoft.com/en-us/azure/backup/scripts/set-file-folder-backup-policy |
| Scripted configuration of system state backup policy with MARS | https://learn.microsoft.com/en-us/azure/backup/scripts/set-system-state-backup-policy |
| Configure Azure Backup to use Archive tier | https://learn.microsoft.com/en-us/azure/backup/use-archive-tier-support |

### Deployment
| Topic | URL |
|-------|-----|
| Identify VM SKUs supported by Azure Backup policies | https://learn.microsoft.com/en-us/azure/backup/backup-azure-policy-supported-skus |
| Automate silent installation of MABS V4 | https://learn.microsoft.com/en-us/azure/backup/backup-mabs-unattended-install |
| Review supported workloads for MABS V3 RTM | https://learn.microsoft.com/en-us/azure/backup/microsoft-azure-backup-server-protection-v3 |
| Check supported workloads for MABS V3 UR1 | https://learn.microsoft.com/en-us/azure/backup/microsoft-azure-backup-server-protection-v3-ur1 |
| Provision VM and enable Azure Backup using Terraform | https://learn.microsoft.com/en-us/azure/backup/quick-backup-vm-terraform |
| Deploy AKS cluster and configure backup using Terraform | https://learn.microsoft.com/en-us/azure/backup/quick-kubernetes-backup-terraform |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Data Lake Storage vaulted backup via ARM/Bicep | https://learn.microsoft.com/en-us/azure/backup/azure-data-lake-storage-backup-configure-quickstart-arm-bicep |
| Back up AKS clusters using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup-using-cli |
| Back up AKS clusters using Azure PowerShell | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup-using-powershell |
| Manage AKS backup extension and Trusted Access via CLI | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-manage-backups |
| Restore AKS clusters and volumes using Azure Backup | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-restore |
| Restore AKS clusters using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-restore-using-cli |
| Restore AKS clusters using Azure PowerShell | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-restore-using-powershell |
| Back up PostgreSQL Flexible Server using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/back-up-azure-database-postgresql-flex-backup-cli |
| Back up PostgreSQL Flexible Server using PowerShell | https://learn.microsoft.com/en-us/azure/backup/back-up-azure-database-postgresql-flex-backup-powershell |
| Back up Azure Files to Recovery Services vault with CLI | https://learn.microsoft.com/en-us/azure/backup/backup-afs-cli |
| Back up Azure Files via Azure PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/backup/backup-azure-afs-automation |
| Configure and trigger VM backups via REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-backupazurevms |
| Create Azure Backup policies using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-createorupdatepolicy |
| Create Recovery Services vaults using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-createorupdatevault |
| Manage Azure Backup jobs programmatically via REST | https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-managejobs |
| Restore Azure virtual machines using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-restoreazurevms |
| Configure PostgreSQL backups using Data Protection REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-data-protection-use-rest-api-backup-postgresql |
| Restore PostgreSQL Flexible Server backups using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-restore-cli |
| Restore PostgreSQL Flexible Server backups with PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-restore-powershell |
| Back up PostgreSQL Flexible Server using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-use-rest-api |
| Restore PostgreSQL flexible servers via Backup REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-use-rest-api-restore |
| Configure blob backups in a storage account using REST | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-backup-blobs |
| Configure and run Azure Disk backups using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-backup-disks |
| Create Backup vault and blob policy via REST | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-create-update-backup-vault |
| Create Azure Blob backup policies via Data Protection REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-create-update-blob-policy |
| Create and manage Azure Disk backup policies via REST | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-create-update-disk-policy |
| Restore blobs in a storage account using REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-restore-blobs |
| Restore Azure Disks using Azure Data Protection REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dataprotection-use-rest-api-restore-disks |
| Configure Azure Files backup using Azure Backup REST APIs | https://learn.microsoft.com/en-us/azure/backup/backup-azure-file-share-rest-api |
| Integrate Defender ransomware alerts with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-integrate-microsoft-defender-using-logic-apps |
| Back up SQL in Azure VMs via PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sql-automation |
| Back up SQL Server in Azure VMs using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sql-backup-cli |
| Manage Azure Backup for SQL VMs using CLI | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sql-manage-cli |
| Restore SQL Server in Azure VMs using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sql-restore-cli |
| Back up SQL Server in Azure VMs via REST API | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sql-vm-rest-api |
| Back up and restore Azure VMs with PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-automation |
| Back up blobs via ARM template with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-blobs-storage-account-arm-template |
| Back up blobs via Bicep using vaulted policies | https://learn.microsoft.com/en-us/azure/backup/backup-blobs-storage-account-bicep |
| Back up Azure Blobs using Azure CLI commands | https://learn.microsoft.com/en-us/azure/backup/backup-blobs-storage-account-cli |
| Back up Azure Blobs in a storage account with PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-blobs-storage-account-ps |
| Automate MARS Windows Server backups with PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-client-automation |
| Automate Azure Backup for DPM with PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-dpm-automation |
| Back up Azure Managed Disks using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/backup-managed-disks-cli |
| Back up Azure Managed Disks using PowerShell | https://learn.microsoft.com/en-us/azure/backup/backup-managed-disks-ps |
| Back up PostgreSQL on Azure VMs using CLI | https://learn.microsoft.com/en-us/azure/backup/backup-postgresql-cli |
| Back up Azure PostgreSQL with PowerShell commands | https://learn.microsoft.com/en-us/azure/backup/backup-postgresql-ps |
| Email Azure Backup reports using Logic Apps | https://learn.microsoft.com/en-us/azure/backup/backup-reports-email |
| Query Azure Backup data with Log Analytics system functions | https://learn.microsoft.com/en-us/azure/backup/backup-reports-system-functions |
| Manage Azure Backup resources using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/create-manage-azure-services-using-azure-command-line-interface |
| Manage Azure Files backups using Azure CLI commands | https://learn.microsoft.com/en-us/azure/backup/manage-afs-backup-cli |
| Manage Azure Files backups with Azure PowerShell | https://learn.microsoft.com/en-us/azure/backup/manage-afs-powershell |
| Manage Azure Files backups with Azure Backup REST APIs | https://learn.microsoft.com/en-us/azure/backup/manage-azure-file-share-rest-api |
| Manage Azure Backup for SQL VMs via REST API | https://learn.microsoft.com/en-us/azure/backup/manage-azure-sql-vm-rest-api |
| Use Azure Backup PowerShell script samples | https://learn.microsoft.com/en-us/azure/backup/powershell-backup-samples |
| Query Azure Backup state using Resource Graph | https://learn.microsoft.com/en-us/azure/backup/query-backups-using-azure-resource-graph |
| Configure Azure Files vaulted backup via ARM template | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-arm |
| Configure Azure Files vaulted backup via Bicep | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-bicep |
| Configure Azure Files vaulted backup using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-cli |
| Configure Azure Files vaulted backup using PowerShell | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-powershell |
| Configure Azure Files vaulted backup using Terraform | https://learn.microsoft.com/en-us/azure/backup/quick-backup-azure-files-vault-tier-terraform |
| Back up SAP HANA System Replication using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/quick-backup-hana-cli |
| Configure PostgreSQL Flexible Server backup via ARM | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-arm |
| Configure PostgreSQL Flexible Server backup via Bicep | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-bicep |
| Configure PostgreSQL Flexible Server backup via Terraform | https://learn.microsoft.com/en-us/azure/backup/quick-backup-postgresql-flexible-server-terraform |
| Configure Azure VM backup using Azure CLI commands | https://learn.microsoft.com/en-us/azure/backup/quick-backup-vm-cli |
| Back up an Azure VM using Azure PowerShell AZ module | https://learn.microsoft.com/en-us/azure/backup/quick-backup-vm-powershell |
| Configure vaulted blob backup using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/quick-blob-vaulted-backup-cli |
| Configure vaulted blob backup using PowerShell | https://learn.microsoft.com/en-us/azure/backup/quick-blob-vaulted-backup-powershell |
| Set up AKS vaulted backup using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/quick-kubernetes-backup-cli |
| Configure AKS vaulted backup using PowerShell commands | https://learn.microsoft.com/en-us/azure/backup/quick-kubernetes-backup-powershell |
| Restore SAP HANA System Replication using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/quick-restore-hana-cli |
| Perform cross-region PostgreSQL restore with Azure PowerShell | https://learn.microsoft.com/en-us/azure/backup/quick-secondary-region-restore-postgresql-powershell |
| Restore Azure Files from Recovery Services vault using CLI | https://learn.microsoft.com/en-us/azure/backup/restore-afs-cli |
| Restore Azure Files using Azure Backup PowerShell | https://learn.microsoft.com/en-us/azure/backup/restore-afs-powershell |
| Restore PostgreSQL Flexible Server as files in portal | https://learn.microsoft.com/en-us/azure/backup/restore-azure-database-postgresql-flex |
| Restore Azure Files using Azure Backup REST APIs | https://learn.microsoft.com/en-us/azure/backup/restore-azure-file-share-rest-api |
| Restore SQL Server in Azure VMs via REST API | https://learn.microsoft.com/en-us/azure/backup/restore-azure-sql-vm-rest-api |
| Restore Azure Blobs to a point in time with Azure CLI | https://learn.microsoft.com/en-us/azure/backup/restore-blobs-storage-account-cli |
| Restore Azure Blobs using Azure Backup PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/backup/restore-blobs-storage-account-ps |
| Restore Azure Managed Disks using Azure CLI | https://learn.microsoft.com/en-us/azure/backup/restore-managed-disks-cli |
| Restore Azure Managed Disks using PowerShell | https://learn.microsoft.com/en-us/azure/backup/restore-managed-disks-ps |
| Restore Azure PostgreSQL backups with Azure CLI | https://learn.microsoft.com/en-us/azure/backup/restore-postgresql-database-cli |
| Restore Azure PostgreSQL backups using PowerShell | https://learn.microsoft.com/en-us/azure/backup/restore-postgresql-database-ps |
| Restore PostgreSQL databases via Data Protection REST API | https://learn.microsoft.com/en-us/azure/backup/restore-postgresql-database-use-rest-api |
| Back up SAP ASE databases on Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sap-ase-database-backup-tutorial |
| Use PowerShell to locate Azure Backup vault for a storage account | https://learn.microsoft.com/en-us/azure/backup/scripts/backup-powershell-script-find-recovery-services-vault |
| Disable Azure Files soft delete via ARM API script | https://learn.microsoft.com/en-us/azure/backup/scripts/disable-soft-delete-for-file-shares |
| Scripted installation of latest MARS agent on Windows servers | https://learn.microsoft.com/en-us/azure/backup/scripts/install-latest-microsoft-azure-recovery-services-agent |
| End-to-end PowerShell configuration of Azure Backup for Windows servers | https://learn.microsoft.com/en-us/azure/backup/scripts/microsoft-azure-recovery-services-powershell-all |
| Register on-premises Windows machines with Recovery Services vault via script | https://learn.microsoft.com/en-us/azure/backup/scripts/register-microsoft-azure-recovery-services-agent |
| Configure SAP HANA instance snapshot backup with CLI | https://learn.microsoft.com/en-us/azure/backup/tutorial-configure-sap-hana-database-instance-snapshot-backup |
| Manage backed-up SAP HANA databases via Azure CLI | https://learn.microsoft.com/en-us/azure/backup/tutorial-sap-hana-manage-cli |
| Restore SAP HANA databases on Azure VMs using CLI | https://learn.microsoft.com/en-us/azure/backup/tutorial-sap-hana-restore-cli |
| Update Recovery Services vault settings via REST | https://learn.microsoft.com/en-us/azure/backup/use-restapi-update-vault-properties |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use AKS backup FAQ for support limits | https://learn.microsoft.com/en-us/azure/backup/aks-backup-faq |
| Review vaulted backup limits for Data Lake Storage | https://learn.microsoft.com/en-us/azure/backup/azure-data-lake-storage-backup-support-matrix |
| Manage Elastic SAN backups and review backup limitations | https://learn.microsoft.com/en-us/azure/backup/azure-elastic-san-backup-manage |
| Restore Azure Elastic SAN backups and understand limitations | https://learn.microsoft.com/en-us/azure/backup/azure-elastic-san-backup-restore |
| Support matrix for Azure Elastic SAN backup (preview) | https://learn.microsoft.com/en-us/azure/backup/azure-elastic-san-backup-support-matrix |
| Support matrix for Azure Files backup | https://learn.microsoft.com/en-us/azure/backup/azure-file-share-support-matrix |
| Check AKS backup support and limitations | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup-support-matrix |
| Consult Azure Backup service FAQ and limits | https://learn.microsoft.com/en-us/azure/backup/backup-azure-backup-faq |
| Configure long-term backup retention for PostgreSQL Flexible Server | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-overview |
| Review backup support matrix for PostgreSQL Flexible Server | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-support-matrix |
| Azure Backup retention and capabilities for PostgreSQL | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-overview |
| Use PostgreSQL server backup FAQ and retirement details | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-server-faq |
| Understand backup support limits for PostgreSQL server | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-support-matrix |
| Consult MABS and DPM backup FAQ and limits | https://learn.microsoft.com/en-us/azure/backup/backup-azure-dpm-azure-server-faq |
| Check MARS Agent backup FAQ and constraints | https://learn.microsoft.com/en-us/azure/backup/backup-azure-file-folder-backup-faq |
| Use Azure Files backup FAQ for limits and behavior | https://learn.microsoft.com/en-us/azure/backup/backup-azure-files-faq |
| Use long-term retention for MySQL Flexible Server backups | https://learn.microsoft.com/en-us/azure/backup/backup-azure-mysql-flexible-server-about |
| Support matrix for Azure Database for MySQL backups | https://learn.microsoft.com/en-us/azure/backup/backup-azure-mysql-flexible-server-support-matrix |
| Review Azure VM backup FAQ and limits | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vm-backup-faq |
| Use Backup Center FAQ for feature constraints | https://learn.microsoft.com/en-us/azure/backup/backup-center-faq |
| Backup center support matrix for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-center-support-matrix |
| Review Azure VM Instant Restore performance limits | https://learn.microsoft.com/en-us/azure/backup/backup-instant-restore-capability |
| MABS v4 protection support matrix for workloads and data types | https://learn.microsoft.com/en-us/azure/backup/backup-mabs-protection-matrix |
| Review automation support matrix for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-support-automation |
| General Azure Backup support settings and limits | https://learn.microsoft.com/en-us/azure/backup/backup-support-matrix |
| Support matrix and limits for Azure VM backups | https://learn.microsoft.com/en-us/azure/backup/backup-support-matrix-iaas |
| MABS and DPM Azure Backup support matrix | https://learn.microsoft.com/en-us/azure/backup/backup-support-matrix-mabs-dpm |
| Support matrix for MARS agent backups | https://learn.microsoft.com/en-us/azure/backup/backup-support-matrix-mars-agent |
| Consult Azure Blob backup FAQ and constraints | https://learn.microsoft.com/en-us/azure/backup/blob-backup-faq |
| Check support limits for Azure Blob backups | https://learn.microsoft.com/en-us/azure/backup/blob-backup-support-matrix |
| Review Azure Disk backup FAQ and limits | https://learn.microsoft.com/en-us/azure/backup/disk-backup-faq |
| Azure Disk Backup regional and scenario support matrix | https://learn.microsoft.com/en-us/azure/backup/disk-backup-support-matrix |
| Check SQL Server on Azure VM backup FAQ and limits | https://learn.microsoft.com/en-us/azure/backup/faq-backup-sql-server |
| Understand and configure Azure VM backup retention and recovery points | https://learn.microsoft.com/en-us/azure/backup/manage-recovery-points |
| SAP ASE backup support matrix on Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sap-ase-backup-support-matrix |
| SAP HANA backup support matrix on Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sap-hana-backup-support-matrix |
| Review SAP HANA on Azure VM backup FAQ and constraints | https://learn.microsoft.com/en-us/azure/backup/sap-hana-faq-backup-azure-vm |
| Use selective disk backup and restore for Azure VMs | https://learn.microsoft.com/en-us/azure/backup/selective-disk-backup-restore |
| Protect Azure file shares with soft delete | https://learn.microsoft.com/en-us/azure/backup/soft-delete-azure-file-share |
| Support matrix for SQL Server backup in Azure VMs | https://learn.microsoft.com/en-us/azure/backup/sql-support-matrix |
| View Azure Backup reports and workspace limits | https://learn.microsoft.com/en-us/azure/backup/view-reports |

### Security
| Topic | URL |
|-------|-----|
| Audit and enforce AKS backup via Azure Policy | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-cluster-backup-policy |
| Auto-enable Azure VM backups using Azure Policy | https://learn.microsoft.com/en-us/azure/backup/backup-azure-auto-enable-backup |
| Configure enhanced soft delete for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-enhanced-soft-delete-about |
| Configure and manage Azure Backup soft delete | https://learn.microsoft.com/en-us/azure/backup/backup-azure-enhanced-soft-delete-configure-manage |
| Enforce Azure Files backup compliance with Azure Policy | https://learn.microsoft.com/en-us/azure/backup/backup-azure-files-policy-automation |
| Protect Azure Backup data with immutable vaults | https://learn.microsoft.com/en-us/azure/backup/backup-azure-immutable-vault-concept |
| Manage Azure Backup Immutable vault settings | https://learn.microsoft.com/en-us/azure/backup/backup-azure-immutable-vault-how-to-manage |
| Secure Azure Backup with private endpoints v2 | https://learn.microsoft.com/en-us/azure/backup/backup-azure-private-endpoints-concept |
| Configure and manage Azure Backup private endpoints v2 | https://learn.microsoft.com/en-us/azure/backup/backup-azure-private-endpoints-configure-manage |
| Restore Key Vault keys and secrets for encrypted VMs | https://learn.microsoft.com/en-us/azure/backup/backup-azure-restore-key-secret |
| Use Azure Backup security features for hybrid workloads | https://learn.microsoft.com/en-us/azure/backup/backup-azure-security-feature |
| Back up and restore encrypted Azure virtual machines | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-encryption |
| Understand encryption options in Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-encryption |
| Back up Azure Managed Disks from Azure portal | https://learn.microsoft.com/en-us/azure/backup/backup-managed-disks |
| Enforce Managed Disks backup policies with Azure Policy | https://learn.microsoft.com/en-us/azure/backup/backup-managed-disks-policy |
| Manage Azure Backup access with RBAC roles | https://learn.microsoft.com/en-us/azure/backup/backup-rbac-rs-vault |
| Compliance certifications and attestations for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/compliance-offerings |
| Enable multi-user authorization with Resource Guard | https://learn.microsoft.com/en-us/azure/backup/enable-multi-user-authorization-quickstart |
| Encrypt Azure Backup data with customer-managed keys | https://learn.microsoft.com/en-us/azure/backup/encryption-at-rest-with-cmk |
| Use CMKs to encrypt data in Backup vaults | https://learn.microsoft.com/en-us/azure/backup/encryption-at-rest-with-cmk-for-backup-vault |
| Configure Multi-user authorization for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/multi-user-authorization |
| Secure Azure Backup operations with Resource Guard MUA | https://learn.microsoft.com/en-us/azure/backup/multi-user-authorization-concept |
| Enable Multi-user authorization with Resource Guard | https://learn.microsoft.com/en-us/azure/backup/multi-user-authorization-tutorial |
| Configure private endpoints for MABS backups | https://learn.microsoft.com/en-us/azure/backup/private-endpoint-configure-vault-backup-server |
| Create private endpoints for Azure Backup | https://learn.microsoft.com/en-us/azure/backup/private-endpoints |
| Secure Azure Backup with private endpoints v1 | https://learn.microsoft.com/en-us/azure/backup/private-endpoints-overview |
| Secure Azure Backup against ransomware attacks | https://learn.microsoft.com/en-us/azure/backup/protect-backups-from-ransomware-faq |
| Re-register MABS vault access after removing private endpoints | https://learn.microsoft.com/en-us/azure/backup/register-public-access-vault-backup-server |
| Restore Azure Disk Encryption–protected virtual machines | https://learn.microsoft.com/en-us/azure/backup/restore-azure-encrypted-virtual-machines |
| Restore Azure Managed Disks with vault managed identity | https://learn.microsoft.com/en-us/azure/backup/restore-managed-disks |
| Store MARS backup passphrases in Azure Key Vault | https://learn.microsoft.com/en-us/azure/backup/save-backup-passphrase-securely-in-azure-key-vault |
| Use secure-by-default soft delete in Azure Backup | https://learn.microsoft.com/en-us/azure/backup/secure-by-default |
| Use secure-by-default soft delete in Azure Backup | https://learn.microsoft.com/en-us/azure/backup/secure-by-default |
| Azure Backup regulatory compliance policy controls | https://learn.microsoft.com/en-us/azure/backup/security-controls-policy |
| Configure and use Azure Backup soft delete securely | https://learn.microsoft.com/en-us/azure/backup/soft-delete-azure-backup-faq |
| Use soft delete for SQL and SAP HANA VM backups | https://learn.microsoft.com/en-us/azure/backup/soft-delete-sql-saphana-in-azure-vm |
| Use soft delete to protect VM backups | https://learn.microsoft.com/en-us/azure/backup/soft-delete-virtual-machines |
| Configure threat detection for Azure VM backups | https://learn.microsoft.com/en-us/azure/backup/threat-detection-configure-monitor-tutorial |
| Detect ransomware in Azure VM backups with Defender | https://learn.microsoft.com/en-us/azure/backup/threat-detection-overview |
| Enable TLS 1.2 for Azure Backup data transfer | https://learn.microsoft.com/en-us/azure/backup/transport-layer-security |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve Azure Data Lake Storage backup issues with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/azure-data-lake-storage-backup-troubleshoot |
| Troubleshoot Azure Kubernetes Service backups and restores with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/azure-kubernetes-service-backup-troubleshoot |
| Troubleshoot data recovery from Microsoft Azure Backup Server | https://learn.microsoft.com/en-us/azure/backup/backup-azure-alternate-dpm-server-troubleshoot |
| Troubleshoot Azure Backup Vault management and operation failures | https://learn.microsoft.com/en-us/azure/backup/backup-azure-backup-vault-troubleshoot |
| Troubleshoot Azure Database for PostgreSQL Flexible Server backups | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-flex-troubleshoot |
| Resolve Azure Database for PostgreSQL backup issues with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-database-postgresql-troubleshoot |
| Troubleshoot encrypted Azure VM backup failures | https://learn.microsoft.com/en-us/azure/backup/backup-azure-encrypted-vm-troubleshoot |
| Fix Azure Backup Server installation and workload protection errors | https://learn.microsoft.com/en-us/azure/backup/backup-azure-mabs-troubleshoot |
| Troubleshoot Azure Backup agent installation and usage | https://learn.microsoft.com/en-us/azure/backup/backup-azure-mars-troubleshoot |
| Resolve Azure Backup monitoring and alert issues | https://learn.microsoft.com/en-us/azure/backup/backup-azure-monitor-alert-faq |
| Resolve Azure Backup monitoring and protection alert issues | https://learn.microsoft.com/en-us/azure/backup/backup-azure-monitor-troubleshoot |
| Fix Azure Database for MySQL Flexible Server backup problems | https://learn.microsoft.com/en-us/azure/backup/backup-azure-mysql-flexible-server-troubleshoot |
| Recover files and folders from Azure VM backups | https://learn.microsoft.com/en-us/azure/backup/backup-azure-restore-files-from-vm |
| Troubleshoot SAP HANA database backups on Azure VMs with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-sap-hana-database-troubleshoot |
| Resolve System Center DPM backup and restore problems with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-azure-scdpm-troubleshooting |
| Troubleshoot System State Backup issues for on-premises Windows servers | https://learn.microsoft.com/en-us/azure/backup/backup-azure-system-state-troubleshoot |
| Diagnose and fix Azure Blob backup and restore failures | https://learn.microsoft.com/en-us/azure/backup/backup-azure-troubleshoot-blob-backup |
| Troubleshoot slow Azure Backup performance for files and folders | https://learn.microsoft.com/en-us/azure/backup/backup-azure-troubleshoot-slow-backup-performance-issue |
| Fix Azure Backup failures from agent and extension issues | https://learn.microsoft.com/en-us/azure/backup/backup-azure-troubleshoot-vm-backup-fails-snapshot-timeout |
| Troubleshoot Azure VM file-level recovery issues | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vm-file-recovery-troubleshoot |
| Resolve Azure VM backup and restore errors | https://learn.microsoft.com/en-us/azure/backup/backup-azure-vms-troubleshoot |
| Address known issues in MABS v3 | https://learn.microsoft.com/en-us/azure/backup/backup-mabs-release-notes-v3 |
| Troubleshoot SQL Server backups on Azure VMs using Azure Backup | https://learn.microsoft.com/en-us/azure/backup/backup-sql-server-azure-troubleshoot |
| Troubleshoot Azure Backup vault management errors | https://learn.microsoft.com/en-us/azure/backup/backup-vault-troubleshoot |
| Diagnose and fix Azure Disk Backup failures | https://learn.microsoft.com/en-us/azure/backup/disk-backup-troubleshoot |
| Resolve SAP HANA database instance backup errors on Azure | https://learn.microsoft.com/en-us/azure/backup/sap-hana-database-instance-troubleshoot |
| Fix Azure Backup archive tier errors when moving recovery points | https://learn.microsoft.com/en-us/azure/backup/troubleshoot-archive-tier |
| Troubleshoot Azure Files backup and restore with Azure Backup | https://learn.microsoft.com/en-us/azure/backup/troubleshoot-azure-files |
| Troubleshoot SAP ASE (Sybase) database backups using Azure Backup | https://learn.microsoft.com/en-us/azure/backup/troubleshoot-sap-ase-sybase-database-backup |

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
