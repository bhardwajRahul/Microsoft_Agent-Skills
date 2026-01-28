---
name: cdn
description: Expert knowledge for Cdn development including best practices, security, integrations & coding patterns, limits & quotas, configuration, troubleshooting, architecture & design patterns, deployment, and comparing x vs. y. Use when building, debugging, or optimizing Cdn applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Cdn Skill

This skill provides expert guidance for Cdn development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Implement data lake capture pattern with Databricks Delta | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-events |
| Design solutions using Azure Blob change feed | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-change-feed |
| React to Azure Blob events with Event Grid | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-overview |
| Use clustered applications with shared Elastic SAN volumes | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-shared-volumes |
| Plan Azure File Sync deployment architecture and options | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-planning |
| Plan Azure Files deployment and access patterns | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-planning |
| Design scalable, performant Azure Table storage schemas | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design |
| Design Azure Table storage for data modification | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design-for-modification |
| Design Azure Table storage for efficient queries | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design-for-query |
| Apply design guidelines for Azure Table storage | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design-guidelines |
| Model relationships in Azure Table storage schemas | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design-modeling |
| Use Azure Table storage design patterns and anti-patterns | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-design-patterns |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply Azure Blob access tier cost-optimization practices | https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-best-practices |
| Optimize Azure blob inventory performance | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-inventory-performance-characteristics |
| Apply monitoring best practices for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-storage-monitoring-scenarios |
| Implement concurrency control for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/concurrency-manage |
| Best practices for Azure Data Lake Storage accounts | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-best-practices |
| Optimize lifecycle management performance in Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-performance-characteristics |
| Monitor Blob lifecycle policies with events and logs | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-policy-monitor |
| Run NFS 3.0 performance benchmarks on Azure Blob | https://learn.microsoft.com/en-us/azure/storage/blobs/network-file-system-protocol-performance-benchmark |
| Optimize NFS 3.0 performance on Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/network-file-system-protocol-support-performance |
| Tune SFTP performance for Azure Blob Storage workloads | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-performance |
| Choose between blob soft delete and versioning | https://learn.microsoft.com/en-us/azure/storage/blobs/soft-delete-vs-versioning-options |
| Create and manage Azure Blob client instances efficiently | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-client-management |
| Design Azure Blob Storage applications for low latency | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-latency |
| Tune .NET Azure Blob uploads and downloads | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-tune-upload-download |
| Tune Go Azure Blob uploads and downloads | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-tune-upload-download-go |
| Tune Java Azure Blob uploads and downloads | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-tune-upload-download-java |
| Tune Azure Storage JavaScript uploads and downloads | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-tune-upload-download-javascript |
| Tune Python Azure blob uploads and downloads | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-tune-upload-download-python |
| Optimize Azure Blob Storage partition naming for performance | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-performance-blob-partitions |
| Apply Azure Blob Storage performance optimization checklist | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-performance-checklist |
| Performance optimization checklist for Azure Blob apps | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-performance-checklist-developers |
| Configure retry policies for Azure Blob .NET client | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-retry-policy |
| Implement Azure Blob retry policies in Go | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-retry-policy-go |
| Configure retry policies for Azure Blobs in Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-retry-policy-java |
| Implement retry policies for Azure Blob Storage in JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-retry-policy-javascript |
| Implement robust retry policies for Blob Storage in Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-retry-policy-python |
| Optimize Azure Elastic SAN configuration and performance | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-best-practices |
| Use and manage Azure Elastic SAN volume snapshots | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-snapshots |
| Choose effective Azure File Sync tiering policies | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-choose-cloud-tiering-policies |
| Disaster recovery best practices for Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-disaster-recovery-best-practices |
| Modify Azure File Sync topology without data loss | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-modify-sync-topology |
| Replace drives on Azure File Sync servers | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-replace-drive |
| Replace an Azure File Sync server correctly | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-replace-server |
| Deprovision Azure File Sync server endpoints safely | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-server-endpoint-delete |
| Recover an Azure File Sync server after failure | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-server-recovery |
| Migrate between Azure file shares using File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-share-to-share-migration |
| Handle large directories on Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/nfs-large-directories |
| Tune NFS Azure file share performance at scale | https://learn.microsoft.com/en-us/azure/storage/files/nfs-performance |
| Improve performance of premium SMB Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/smb-performance |
| Optimize Azure Files performance for your workload | https://learn.microsoft.com/en-us/azure/storage/files/understand-performance |
| Optimize Azure Files for virtual desktop workloads | https://learn.microsoft.com/en-us/azure/storage/files/virtual-desktop-workloads |
| Best practices for monitoring Azure Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/queues-storage-monitoring-scenarios |
| Apply security best practices to Azure Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/security-recommendations |
| Optimize Queue Storage performance and scalability | https://learn.microsoft.com/en-us/azure/storage/queues/storage-performance-checklist |
| Optimize Azure Table storage performance and scalability | https://learn.microsoft.com/en-us/azure/storage/tables/storage-performance-checklist |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Map Azure Blob REST operations to billing categories | https://learn.microsoft.com/en-us/azure/storage/blobs/map-rest-apis-transaction-categories |
| Understand Azure Container Storage billing and cost components | https://learn.microsoft.com/en-us/azure/storage/container-storage/container-storage-billing |
| Choose Elastic SAN storage options for AKS workloads | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-aks-options |
| Choose between Microsoft.FileShares and classic Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/create-file-share |
| Estimate Azure Files costs across billing models | https://learn.microsoft.com/en-us/azure/storage/files/file-estimate-cost |
| Use Azure Files Reservations to reduce storage costs | https://learn.microsoft.com/en-us/azure/storage/files/files-reserve-capacity |
| Migrate Linux servers to NFS Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-nfs |
| Choose between Azure Files and Azure NetApp Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-netapp-comparison |
| Compare Azure Files billing models and costs | https://learn.microsoft.com/en-us/azure/storage/files/understanding-billing |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure Storage blob inventory reports | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-inventory-how-to |
| Generate BlobFuse2 autocompletion scripts | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-completion |
| Create bash completion for BlobFuse2 CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-completion-bash |
| Create fish completion for BlobFuse2 CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-completion-fish |
| Create PowerShell completion for BlobFuse2 CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-completion-powershell |
| Create zsh completion for BlobFuse2 CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-completion-zsh |
| Use blobfuse2 help for command reference | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-help |
| Generate BlobFuse2 config from BlobFuse v1 | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-mountv1 |
| Use blobfuse2 unmount to remove mount points | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-unmount |
| Use blobfuse2 unmount all for all mounts | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-unmount-all |
| Check BlobFuse2 version and updates | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-version |
| Configure BlobFuse2 settings for Azure Blob mounts | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-configuration |
| Use BlobFuse2 Health Monitor for mount diagnostics | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-health-monitor |
| Install and configure BlobFuse2 mounts on Linux | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-how-to-deploy |
| Construct and use ABFS URIs for Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction-abfs-uri |
| Use customer-provided encryption keys with Blob storage | https://learn.microsoft.com/en-us/azure/storage/blobs/encryption-customer-provided-keys |
| Create and configure encryption scopes for Blob storage | https://learn.microsoft.com/en-us/azure/storage/blobs/encryption-scope-manage |
| Define lifecycle policies to tier blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-policy-access-tiers |
| Configure Azure Blob lifecycle management policies | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-policy-configure |
| Define lifecycle policies to delete blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-policy-delete |
| Understand Blob Storage lifecycle policy schema | https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-policy-structure |
| Reference for monitoring Azure Blob Storage data | https://learn.microsoft.com/en-us/azure/storage/blobs/monitor-blob-storage-reference |
| Mount Azure Blob containers via NFS 3.0 on Linux | https://learn.microsoft.com/en-us/azure/storage/blobs/network-file-system-protocol-support-how-to |
| Enable or disable SFTP on Azure Blob Storage accounts | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-support-how-to |
| Enable and configure blob soft delete | https://learn.microsoft.com/en-us/azure/storage/blobs/soft-delete-blob-enable |
| Manage and restore soft-deleted blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/soft-delete-blob-manage |
| Enable and configure container soft delete | https://learn.microsoft.com/en-us/azure/storage/blobs/soft-delete-container-enable |
| Check blob encryption status using portal, CLI, and PowerShell | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-encryption-status |
| Map custom domains to Blob storage and static website endpoints | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name |
| Configure BlobFuse v1 to mount Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-how-to-mount-container-linux |
| Run Azurite-based tests for Blob private endpoints | https://learn.microsoft.com/en-us/azure/storage/blobs/use-azurite-to-run-automated-tests |
| Enable and manage blob versioning settings | https://learn.microsoft.com/en-us/azure/storage/blobs/versioning-enable |
| Configure storage pool parameters for Container Storage v1 | https://learn.microsoft.com/en-us/azure/storage/container-storage/container-storage-storage-pool-parameters |
| Configure and interpret Azure Elastic SAN metrics | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-metrics |
| Silently install and configure Azure File Sync agent | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-agent-silent-installation |
| Configure Azure File Sync cloud tiering policies | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-cloud-tiering-policy |
| Install and manage Azure File Sync agent on Arc | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-extension |
| Manage Azure File Sync cloud-tiered files via PowerShell | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-how-to-manage-tiered-files |
| Monitor Azure File Sync cloud tiering metrics | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-monitor-cloud-tiering |
| Configure public and private endpoints for Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-networking-endpoints |
| Configure networking for Azure File Sync servers | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-networking-overview |
| Configure Azure File Sync server endpoints and options | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-server-endpoint-create |
| Configure and manage registered servers for Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-server-registration |
| Use Azure Monitor reference for Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/monitor-file-sync-reference |
| Configure Azure classic file share performance and tiers | https://learn.microsoft.com/en-us/azure/storage/files/create-classic-file-share |
| Change redundancy configuration for Azure Files accounts | https://learn.microsoft.com/en-us/azure/storage/files/files-change-redundancy-configuration |
| Migrate files between SMB Azure file shares with Robocopy | https://learn.microsoft.com/en-us/azure/storage/files/migrate-files-between-shares |
| Migrate to Azure Files using Azure Storage Mover | https://learn.microsoft.com/en-us/azure/storage/files/migrate-files-storage-mover |
| Modify Azure file share size, cost, and performance | https://learn.microsoft.com/en-us/azure/storage/files/modify-file-share |
| Configure point-to-site VPN on Linux for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-configure-p2s-vpn-linux |
| Configure point-to-site VPN on Windows for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-configure-p2s-vpn-windows |
| Configure site-to-site VPN for Azure Files access | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-configure-s2s-vpn |
| Mount NFS Azure file shares on Linux | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-how-to-mount-nfs-shares |
| Migrate to SMB Azure file shares using Robocopy | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-robocopy |
| Configure Azure Monitor metrics and logs for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-monitoring |
| Reference for Azure Files monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-monitoring-reference |
| Configure DNS forwarding for Azure Files private endpoints | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-networking-dns |
| Configure public and private endpoints for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-networking-endpoints |
| Configure soft delete for Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-prevent-file-share-deletion |
| Mount SMB Azure file shares on Linux | https://learn.microsoft.com/en-us/azure/storage/files/storage-how-to-use-files-linux |
| Mount Azure file shares on macOS via SMB | https://learn.microsoft.com/en-us/azure/storage/files/storage-how-to-use-files-mac |
| Mount SMB Azure file shares on Windows | https://learn.microsoft.com/en-us/azure/storage/files/storage-how-to-use-files-windows |
| Use and manage Azure Files share snapshots | https://learn.microsoft.com/en-us/azure/storage/files/storage-snapshots-files |
| Monitoring data reference for Azure Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/monitor-queue-storage-reference |
| Configure monitoring for Azure Table Storage with Azure Monitor | https://learn.microsoft.com/en-us/azure/storage/tables/monitor-table-storage |
| Reference for Azure Table Storage monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/storage/tables/monitor-table-storage-reference |

### Deployment
| Topic | URL |
|-------|-----|
| Migrate on-premises HDFS data to Azure Storage with Data Box | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-migrate-on-premises-hdfs-cluster |
| Enable and deploy static websites in Azure Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-how-to |
| Deploy static website to Blob storage with GitHub Actions | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-static-site-github-actions |
| Check Blob feature support by storage account type | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-feature-support-in-storage-accounts |
| Deploy static website on Azure Storage with Terraform | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-static-website-terraform |
| Upgrade Blob Storage accounts to Data Lake Gen2 via ARM | https://learn.microsoft.com/en-us/azure/storage/blobs/upgrade-to-data-lake-storage-gen2-how-to |
| Deploy Azure File Sync with portal, PowerShell, or CLI | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-deployment-guide |
| Migrate GlusterFS volumes to Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/glusterfs-migration-guide |
| Migrate Linux file services to Azure File Sync hybrid | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-linux-hybrid |
| Migrate on-premises NAS to Azure Files with Data Box | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-nas-cloud-databox |
| Migrate on-premises NAS SMB shares to Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-nas-hybrid |
| Migrate NAS to Azure File Sync via Azure Data Box | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-nas-hybrid-databox |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Trigger Azure Functions from blob rehydration events | https://learn.microsoft.com/en-us/azure/storage/blobs/archive-rehydrate-handle-event |
| Use Azure CLI to manage block blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-cli |
| Manage Azure Blob containers with Azure CLI commands | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-containers-cli |
| Manage Azure Blob containers using PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-containers-powershell |
| Use Azure PowerShell to manage block blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/blob-powershell |
| Use BlobFuse2 commands to manage Blob mounts | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands |
| Mount Azure Blob containers with blobfuse2 mount | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-mount |
| Mount all Blob containers using blobfuse2 mount all | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-mount-all |
| List BlobFuse2 mount points with mount list | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-mount-list |
| Calculate blob counts and sizes with Synapse | https://learn.microsoft.com/en-us/azure/storage/blobs/calculate-blob-count-size |
| Implement client-side encryption for blobs with .NET and Key Vault | https://learn.microsoft.com/en-us/azure/storage/blobs/client-side-encryption |
| Convert append and page blobs to block blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/convert-append-and-page-blobs-to-block-blobs |
| Manage Data Lake Storage data with Azure CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-cli |
| Use .NET SDK to manage Data Lake Storage data | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-dotnet |
| Use Java SDK to manage Data Lake Storage data | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-java |
| Use Node.js SDK to manage Data Lake Storage data | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-javascript |
| Manage Data Lake Storage data with PowerShell | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-powershell |
| Use Python SDK to manage Data Lake Storage data | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-directory-file-acl-python |
| Filter Data Lake Storage data with query acceleration | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-query-acceleration-how-to |
| Use Azure services that integrate with Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-supported-azure-services |
| Use open source platforms with Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-supported-open-source-platforms |
| ETL with HDInsight Hive and Sqoop into SQL Database | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-tutorial-extract-transform-load-hive |
| Access Data Lake Storage from Azure Databricks Spark | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-use-databricks-spark |
| Use DistCp to copy data to Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-use-distcp |
| Use HDFS CLI against Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-use-hdfs-data-lake-storage |
| Query Data Lake Storage using Synapse serverless SQL | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-use-sql |
| Use query acceleration SQL for Azure Blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/query-acceleration-sql-reference |
| Use C++ client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/quickstart-blobs-c-plus-plus |
| Manage Azure blobs from JavaScript in the browser | https://learn.microsoft.com/en-us/azure/storage/blobs/quickstart-blobs-javascript-browser |
| Create service SAS for blobs with .NET SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/sas-service-create-dotnet |
| Connect SFTP clients to Azure Blob Storage endpoints | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-support-connect |
| Create and manage blob snapshots using .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/snapshots-manage-dotnet |
| Append data to Azure append blobs with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-append |
| Compute blob container statistics using Databricks | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-calculate-container-statistics-databricks |
| Process Azure Blob change feed with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-change-feed-how-to |
| Create Azure Blob containers with .NET client | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-create |
| Create Azure blob containers using Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-create-go |
| Create Azure Blob containers using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-create-java |
| Create Azure blob containers using JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-create-javascript |
| Create Azure blob containers using Python SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-create-python |
| Delete and restore Azure Blob containers in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-delete |
| Delete and restore Azure blob containers with Go | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-delete-go |
| Delete and restore Blob containers with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-delete-java |
| Delete and restore blob containers with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-delete-javascript |
| Delete and restore Azure blob containers with Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-delete-python |
| Manage Azure Blob container leases in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-lease |
| Manage Azure Blob container leases in Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-lease-java |
| Manage Azure blob container leases in JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-lease-javascript |
| Manage Azure blob container leases with Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-lease-python |
| Set container properties and metadata with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-properties-metadata |
| Manage container properties and metadata with Go | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-properties-metadata-go |
| Set container properties and metadata with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-properties-metadata-java |
| Set container properties and metadata with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-properties-metadata-javascript |
| Manage Azure blob container properties and metadata in Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-container-properties-metadata-python |
| List Azure Blob containers using .NET SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-containers-list |
| List Azure blob containers with Go client | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-containers-list-go |
| List Azure Blob containers using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-containers-list-java |
| List Azure blob containers using JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-containers-list-javascript |
| List Azure blob containers using Python client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-containers-list-python |
| Copy Azure blobs using .NET client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy |
| Asynchronously copy Azure blobs using .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-async-dotnet |
| Asynchronously copy Azure blobs using Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-async-go |
| Perform asynchronous blob copy operations in Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-async-java |
| Copy Azure blobs asynchronously with JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-async-javascript |
| Asynchronously copy Azure blobs with Python SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-async-python |
| Copy Azure blobs using Go client module | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-go |
| Copy Azure blobs using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-java |
| Copy Azure blobs with JavaScript client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-javascript |
| Copy Azure blobs using the Python client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-python |
| Copy blobs from source URLs with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-url-dotnet |
| Copy blobs from URL with Go in Azure Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-url-go |
| Copy blobs from source URLs with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-url-java |
| Copy blobs from source URLs using JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-url-javascript |
| Copy Azure blobs from URL using Python SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-copy-url-python |
| Delete and restore Azure blobs using .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-delete |
| Delete and restore Azure blobs with Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-delete-go |
| Delete and restore Azure blobs using Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-delete-java |
| Delete and restore Azure blobs with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-delete-javascript |
| Delete and restore Azure blobs with Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-delete-python |
| Connect to Azure Blob Storage using .NET SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-dotnet-get-started |
| Download Azure blobs with the .NET client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-download |
| Download Azure blobs with Go client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-download-go |
| Download Azure blobs using Java client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-download-java |
| Download Azure blobs using JavaScript client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-download-javascript |
| Download Azure blobs using the Python client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-download-python |
| Route Blob storage events to webhooks via CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-quickstart |
| Retrieve Azure blob and container URLs in JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-get-url-javascript |
| Set and query blob index tags programmatically | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-index-how-to |
| Analyze blob inventory with Synapse and Power BI | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-inventory-report-analytics |
| Create and manage Azure blob leases in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-lease |
| Manage Azure blob leases with Java client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-lease-java |
| Create and manage Azure blob leases in JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-lease-javascript |
| Manage Azure blob leases with Python SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-lease-python |
| Manage blob properties and metadata in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-properties-metadata |
| Manage blob properties and metadata with Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-properties-metadata-go |
| Set blob properties and metadata using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-properties-metadata-java |
| Manage Azure blob properties and metadata in JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-properties-metadata-javascript |
| Manage blob properties and metadata in Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-properties-metadata-python |
| Discover Blob endpoints via Azure management SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-query-endpoint-srp |
| Use blob index tags with .NET to query data | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-tags |
| Manage Azure blob index tags with Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-tags-go |
| Use blob index tags with Azure Storage Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-tags-java |
| Manage Azure blob index tags with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-tags-javascript |
| Use blob index tags with Python for search | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-tags-python |
| Upload blobs to Azure Storage using .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-upload |
| Upload blobs to Azure Storage using Go | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-upload-go |
| Upload Azure block blobs using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-upload-java |
| Upload blobs to Azure Storage with JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-upload-javascript |
| Upload Azure blobs using the Python client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-upload-python |
| Set or change Azure blob access tiers in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-use-access-tier-dotnet |
| Change Azure blob access tiers with Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-use-access-tier-java |
| Set Azure blob access tiers using JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-use-access-tier-javascript |
| Set Azure blob access tiers using Python | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-use-access-tier-python |
| Create user delegation SAS for blobs with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-user-delegation-sas-create-dotnet |
| List blobs in Azure Storage with .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-list |
| List Azure Blob Storage blobs using Go SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-list-go |
| List Azure blobs hierarchically with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-list-java |
| List Azure blobs using JavaScript client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-list-javascript |
| List Azure blobs with Python client library | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-list-python |
| Encrypt and decrypt blobs using Key Vault client-side keys | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-encrypt-decrypt-blobs-key-vault |
| Use .NET client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet |
| Use Go client module for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-go |
| Use Java client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-java |
| Integrate Quarkus apps with Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-java-quarkus |
| Use JavaScript client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-nodejs |
| Use TypeScript client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-nodejs-typescript |
| Use Python client library for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-python |
| Create and list Azure blob versions in .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/versions-manage-dotnet |
| Enable Prometheus monitoring for Azure Container Storage | https://learn.microsoft.com/en-us/azure/storage/container-storage/enable-monitoring |
| Integrate Azure Container Storage v1 with Azure Elastic SAN | https://learn.microsoft.com/en-us/azure/storage/container-storage/use-container-storage-with-elastic-san |
| Configure Azure Container Storage with local NVMe on AKS | https://learn.microsoft.com/en-us/azure/storage/container-storage/use-container-storage-with-local-disk |
| Use Azure Container Storage v1 with Azure managed disks | https://learn.microsoft.com/en-us/azure/storage/container-storage/use-container-storage-with-managed-disks |
| Use Azure Managed Grafana dashboards for Container Storage | https://learn.microsoft.com/en-us/azure/storage/container-storage/use-grafana-dashboard |
| Batch-create Azure Elastic SAN volumes with PowerShell | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-batch-create-sample |
| Integrate Azure Elastic SAN with AKS via iSCSI CSI | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-connect-aks |
| Connect Linux clients to Azure Elastic SAN over iSCSI | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-connect-linux |
| Connect Windows clients to Azure Elastic SAN volumes | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-connect-windows |
| Integrate Azure Files with Azure Kubernetes Service using CSI | https://learn.microsoft.com/en-us/azure/storage/files/azure-kubernetes-service-workloads |
| Use Azure Files from .NET applications | https://learn.microsoft.com/en-us/azure/storage/files/storage-dotnet-how-to-use-files |
| Use Azure Files from Java applications | https://learn.microsoft.com/en-us/azure/storage/files/storage-java-how-to-use-file-storage |
| Use Azure Files from Python applications | https://learn.microsoft.com/en-us/azure/storage/files/storage-python-how-to-use-file-storage |
| Manage Azure Queue Storage with PowerShell commands | https://learn.microsoft.com/en-us/azure/storage/queues/storage-powershell-how-to-use-queues |
| Run Azure Table storage operations with PowerShell | https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-how-to-use-powershell |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Rehydrate Azure archive blobs with timing constraints | https://learn.microsoft.com/en-us/azure/storage/blobs/archive-rehydrate-to-online-tier |
| Review limitations and known issues for Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-known-issues |
| Understand NFS 3.0 limitations and issues in Azure Blob | https://learn.microsoft.com/en-us/azure/storage/blobs/network-file-system-protocol-known-issues |
| Use priority replication for Azure Blob object replication | https://learn.microsoft.com/en-us/azure/storage/blobs/object-replication-priority-replication |
| Use point-in-time restore for block blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/point-in-time-restore-overview |
| Reference Azure Blob Storage scalability and performance targets | https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets |
| Review scalability targets for premium block blob accounts | https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets-premium-block-blobs |
| Review scalability targets for premium page blob accounts | https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets-premium-page-blobs |
| Review SFTP limitations and known issues in Azure Blob | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-known-issues |
| Understand Azure page blob size and usage constraints | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-pageblob-overview |
| Plan static website hosting on Azure Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website |
| Understand Elastic SAN and VM performance limits | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-performance |
| Plan Azure Elastic SAN capacity and performance | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-planning |
| Elastic SAN scalability, capacity, IOPS, and throughput limits | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-scale-targets |
| Azure File Sync scalability and performance targets | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-scale-targets |
| Azure File Sync API throttling limits and behavior | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-throttling |
| Check redundancy support regions for premium Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/redundancy-premium-file-shares |
| Azure Files and File Sync limits and behavioral FAQs | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-faq |
| Azure Files scalability and performance limits | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-scale-targets |
| Scalability and performance targets for Azure Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/scalability-targets |
| Understand Azure Queue Storage message limits | https://learn.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction |
| Scalability and performance targets for Azure Table storage | https://learn.microsoft.com/en-us/azure/storage/tables/scalability-targets |

### Security
| Topic | URL |
|-------|-----|
| Configure anonymous read access for Azure blobs | https://learn.microsoft.com/en-us/azure/storage/blobs/anonymous-read-access-configure |
| Prevent anonymous blob access in ARM storage accounts | https://learn.microsoft.com/en-us/azure/storage/blobs/anonymous-read-access-prevent |
| Assign Azure RBAC roles for Blob data access | https://learn.microsoft.com/en-us/azure/storage/blobs/assign-azure-role-data-access |
| Authorize blob access using Entra ID and Azure RBAC roles | https://learn.microsoft.com/en-us/azure/storage/blobs/authorize-access-azure-active-directory |
| Authorize blob data operations with Azure CLI and Entra, keys, or SAS | https://learn.microsoft.com/en-us/azure/storage/blobs/authorize-data-operations-cli |
| Authorize blob data access in Azure portal with Entra or keys | https://learn.microsoft.com/en-us/azure/storage/blobs/authorize-data-operations-portal |
| Access blob data with PowerShell using Entra-based RBAC | https://learn.microsoft.com/en-us/azure/storage/blobs/authorize-data-operations-powershell |
| Secure BlobFuse2 configuration files with encryption | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-secure |
| Decrypt BlobFuse2 encrypted configuration files | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-secure-decrypt |
| Encrypt BlobFuse2 configuration files | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-secure-encrypt |
| Read parameters from encrypted BlobFuse2 configs | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-secure-get |
| Modify parameters in encrypted BlobFuse2 configs | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-commands-secure-set |
| Use POSIX-style ACLs in Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control |
| Understand access control model for Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control-model |
| Manage Data Lake Storage ACLs using Azure portal | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-azure-portal |
| Manage Data Lake Storage ACLs with Azure CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-cli |
| Manage Data Lake Storage ACLs using .NET SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-dotnet |
| Manage Data Lake Storage ACLs using Java SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-java |
| Manage Data Lake Storage ACLs using JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-javascript |
| Manage Data Lake Storage ACLs with PowerShell | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-powershell |
| Manage Data Lake Storage ACLs using Python SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-acl-python |
| Set Data Lake Storage ACLs with Storage Explorer | https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-explorer-acl |
| Enforce same-tenant policies for Azure Blob object replication | https://learn.microsoft.com/en-us/azure/storage/blobs/object-replication-prevent-cross-tenant-policies |
| Create service SAS for Blob Storage with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/sas-service-create-java |
| Create service SAS for blobs with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/sas-service-create-javascript |
| Create service SAS tokens for Azure blobs with Python | https://learn.microsoft.com/en-us/azure/storage/blobs/sas-service-create-python |
| Validate SFTP host keys for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-host-keys |
| Authorize SFTP client access to Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/secure-file-transfer-protocol-support-authorize-access |
| Apply security recommendations for Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/security-recommendations |
| Use Azure ABAC role assignment conditions for Blob storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac |
| Supported actions and attributes for Blob ABAC conditions | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-attributes |
| Configure Azure ABAC blob access with Azure CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-cli |
| Example ABAC role assignment conditions for Blob storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-examples |
| Configure Azure ABAC blob access in portal | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-portal |
| Configure Azure ABAC blob access with PowerShell | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-powershell |
| Security considerations when using ABAC conditions for Blob storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-auth-abac-security |
| Generate account SAS tokens with JavaScript SDK | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-account-delegation-sas-create-javascript |
| Create user delegation SAS tokens with JavaScript | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-create-user-delegation-sas-javascript |
| Use customer-provided encryption keys with Blob .NET | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-customer-provided-key |
| Create user delegation SAS for blobs with Azure CLI | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-user-delegation-sas-create-cli |
| Create user delegation SAS tokens with Java | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-user-delegation-sas-create-java |
| Create user delegation SAS for blobs with PowerShell | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-user-delegation-sas-create-powershell |
| Create user delegation SAS tokens with Python for Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-user-delegation-sas-create-python |
| Configure customer-managed key encryption for Elastic SAN | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-configure-customer-managed-keys |
| Configure private endpoints for Azure Elastic SAN volumes | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-configure-private-endpoints |
| Configure service endpoints for Azure Elastic SAN access | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-configure-service-endpoints |
| Manage customer-managed keys for Azure Elastic SAN | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-encryption-manage-customer-keys |
| Configure encryption and key management for Elastic SAN | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-encryption-overview |
| Configure secure networking for Azure Elastic SAN | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-networking |
| Configure firewall and proxy settings for Azure File Sync | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-firewall-and-proxy |
| Use managed identities with Azure File Sync securely | https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-managed-identities |
| Authorize Azure file share data access in the Azure portal | https://learn.microsoft.com/en-us/azure/storage/files/authorize-data-operations-portal |
| Enable OAuth-based REST access to Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/authorize-oauth-rest |
| Encrypt data in transit for NFS Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/encryption-in-transit-for-nfs-shares |
| Use managed identities to access Azure Files over SMB | https://learn.microsoft.com/en-us/azure/storage/files/files-managed-identities |
| Configure NFS Azure file shares security and networking | https://learn.microsoft.com/en-us/azure/storage/files/files-nfs-protocol |
| Disable SMB1 on Linux clients for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/files-remove-smb1-linux |
| Configure SMB Azure file shares and security features | https://learn.microsoft.com/en-us/azure/storage/files/files-smb-protocol |
| Configure NFS root squash for Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/nfs-root-squash |
| Plan identity-based authentication options for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-active-directory-overview |
| Understand Azure Files authorization and access control model | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-authorization-overview |
| Enable AD DS authentication for Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-ad-ds-enable |
| Configure on-premises AD DS authentication for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-ad-ds-overview |
| Rotate AD DS storage account identity password for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-ad-ds-update-password |
| Assign share-level permissions for Azure file shares | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-assign-share-level-permissions |
| Enable Microsoft Entra Domain Services authentication for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-domain-services-enable |
| Configure cloud trust between AD DS and Entra ID for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-hybrid-cloud-trust |
| Configure Microsoft Entra Kerberos authentication for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-hybrid-identities-enable |
| Enable Kerberos authentication for Linux clients with Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-linux-kerberos-enable |
| Configure NTFS directory and file permissions for Azure Files | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-configure-file-level-permissions |
| Use Azure Files with multiple AD DS forests | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-multiple-forests |
| Plan networking and security for Azure Files access | https://learn.microsoft.com/en-us/azure/storage/files/storage-files-networking-overview |
| Assign Azure RBAC roles for Queue data access | https://learn.microsoft.com/en-us/azure/storage/queues/assign-azure-role-data-access |
| Authorize Azure Queue Storage with Entra ID and RBAC | https://learn.microsoft.com/en-us/azure/storage/queues/authorize-access-azure-active-directory |
| Authorize Queue data operations with Azure CLI | https://learn.microsoft.com/en-us/azure/storage/queues/authorize-data-operations-cli |
| Choose authorization method for Queue data in portal | https://learn.microsoft.com/en-us/azure/storage/queues/authorize-data-operations-portal |
| Use PowerShell with Entra credentials for Queue data | https://learn.microsoft.com/en-us/azure/storage/queues/authorize-data-operations-powershell |
| Implement client-side encryption for Azure Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/client-side-encryption |
| Migrate Queue Storage apps to passwordless authentication | https://learn.microsoft.com/en-us/azure/storage/queues/passwordless-migrate-queues |
| Configure ABAC role assignment conditions for Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/queues-auth-abac |
| Actions and ABAC attributes for Queue Storage roles | https://learn.microsoft.com/en-us/azure/storage/queues/queues-auth-abac-attributes |
| ABAC role assignment condition examples for Queue Storage | https://learn.microsoft.com/en-us/azure/storage/queues/queues-auth-abac-examples |
| Assign Azure RBAC roles for Azure Table data access | https://learn.microsoft.com/en-us/azure/storage/tables/assign-azure-role-data-access |
| Authorize Azure Table data access with Entra ID | https://learn.microsoft.com/en-us/azure/storage/tables/authorize-access-azure-active-directory |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common BlobFuse2 mounting and I/O issues | https://learn.microsoft.com/en-us/azure/storage/blobs/blobfuse2-troubleshooting |
| Azure Blob Storage FAQ and issue guidance | https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-faq |
| Troubleshoot Azure Container Storage v1 issues | https://learn.microsoft.com/en-us/azure/storage/container-storage/troubleshoot-container-storage |
| Troubleshoot common Azure Elastic SAN issues | https://learn.microsoft.com/en-us/azure/storage/elastic-san/elastic-san-troubleshoot |

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
