---
name: virtual-machines
description: Expert knowledge for Virtual Machines development including configuration, deployment, limits & quotas, architecture & design patterns, security, comparing x vs. y, best practices, integrations & coding patterns, and troubleshooting. Use when building, debugging, or optimizing Virtual Machines applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Virtual Machines Skill

This skill provides expert guidance for Virtual Machines development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Plan backup and disaster recovery for Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/backup-and-disaster-recovery-for-azure-iaas-disks |
| Design low-latency architectures with proximity placement groups | https://learn.microsoft.com/en-us/azure/virtual-machines/co-location |
| Architect clustered applications using Azure shared disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-shared |
| Choose DNS name resolution options for Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/azure-dns |
| Migrate workloads from retiring Azure Dedicated Host SKUs | https://learn.microsoft.com/en-us/azure/virtual-machines/migration/dedicated-host-migration-guide |
| Migrate workloads from retiring Azure Dedicated Host SKUs | https://learn.microsoft.com/en-us/azure/virtual-machines/migration/dedicated-host-migration-guide |
| Migrate retiring general purpose VM sizes to newer series | https://learn.microsoft.com/en-us/azure/virtual-machines/migration/sizes/d-ds-dv2-dsv2-ls-series-migration-guide |
| Migrate NV-series GPU VMs to newer Azure GPU sizes | https://learn.microsoft.com/en-us/azure/virtual-machines/migration/sizes/nv-series-migration-guide |
| Migrate NV-series GPU VMs to newer Azure GPU sizes | https://learn.microsoft.com/en-us/azure/virtual-machines/migration/sizes/nv-series-migration-guide |
| Design backup and DR for Azure unmanaged disks | https://learn.microsoft.com/en-us/azure/virtual-machines/page-blobs-backup-and-disaster-recovery |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply scaling best practices for Azure HPC applications | https://learn.microsoft.com/en-us/azure/virtual-machines/compiling-scaling-applications |
| Apply scaling best practices for Azure HPC applications | https://learn.microsoft.com/en-us/azure/virtual-machines/compiling-scaling-applications |
| Optimize InfiniBand-enabled HB and N-series VMs for HPC | https://learn.microsoft.com/en-us/azure/virtual-machines/configure |
| Optimize InfiniBand-enabled HB and N-series VMs for HPC | https://learn.microsoft.com/en-us/azure/virtual-machines/configure |
| Apply cost optimization best practices for Azure virtual machines | https://learn.microsoft.com/en-us/azure/virtual-machines/cost-optimization-best-practices |
| Best practices for high availability with Azure VMs and disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-high-availability |
| Optimize VM and Disk Performance in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-performance |
| Handle VM extensions on Python 3-enabled Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/issues-using-vm-extensions-python-3 |
| Interpret HBv2 VM performance benchmark results | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv2-performance |
| Optimize NUMA-aware process placement on HBv2 VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv2-series-overview |
| Use HBv3 VM performance and scalability benchmarks | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv3-performance |
| Understand HBv3 VM architecture and NUMA topology | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv3-series-overview |
| Apply HBv4 VM performance and scalability data | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv4-performance |
| Understand HBv4 VM architecture and NUMA layout | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv4-series-overview |
| Use HBv5 VM performance and scalability benchmarks | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv5-performance |
| Understand HBv5 VM architecture and topology | https://learn.microsoft.com/en-us/azure/virtual-machines/hbv5-series-overview |
| Optimize NUMA-aware process placement on HC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/hc-series-overview |
| Interpret HC VM performance benchmark results | https://learn.microsoft.com/en-us/azure/virtual-machines/hc-series-performance |
| Understand HX VM architecture and NUMA topology | https://learn.microsoft.com/en-us/azure/virtual-machines/hx-series-overview |
| Apply best practices for Azure VM Image Builder | https://learn.microsoft.com/en-us/azure/virtual-machines/image-builder-best-practices |
| Understand Azure-specific cloud-init provisioning stages | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cloud-init-deep-dive |
| Format and use temporary disks on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disks-format-mount-temp-disks-linux |
| Optimize Linux performance on Azure Lsv3 and Lasv3 VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/storage-performance |
| Mitigate speculative execution side-channel risks on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/mitigate-se |
| Design High-Performance Apps with Azure Premium SSDs | https://learn.microsoft.com/en-us/azure/virtual-machines/premium-storage-performance |
| Optimize VM boot time using Image Builder | https://learn.microsoft.com/en-us/azure/virtual-machines/vm-boot-optimization |
| Safely repurpose Windows VM D: drive as data disk | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/change-drive-letter |
| Optimize Windows performance on Azure Lsv3 and Lasv3 VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/storage-performance |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose between Azure VM, VMSS, and Compute Fleet | https://learn.microsoft.com/en-us/azure/virtual-machines/compare-compute-products |
| Understand impact of deprecated Azure Marketplace images | https://learn.microsoft.com/en-us/azure/virtual-machines/deprecated-images |
| Compare ZRS vs LRS redundancy for managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-redundancy |
| Compare CoreMark scores for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/compute-benchmark-scores |
| Compare CoreMark scores for Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/compute-benchmark-scores |

### Configuration
| Topic | URL |
|-------|-----|
| Enable automatic extension upgrades for Azure VMs and scale sets | https://learn.microsoft.com/en-us/azure/virtual-machines/automatic-extension-upgrade |
| Configure automatic guest patching for Azure VMs and scale sets | https://learn.microsoft.com/en-us/azure/virtual-machines/automatic-vm-guest-patching |
| Use Azure HPC/AI optimized VM images | https://learn.microsoft.com/en-us/azure/virtual-machines/azure-hpc-vm-images |
| Configure and create Azure capacity reservations | https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-create |
| Share Capacity Reservation Groups across subscriptions | https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-group-share |
| Modify Azure capacity reservations via API and tools | https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-modify |
| Customize VM Watch settings and collector groups | https://learn.microsoft.com/en-us/azure/virtual-machines/configure-vm-watch |
| Use custom data and cloud-init on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/custom-data |
| Convert Azure managed disks between storage types | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-convert-types |
| Copy Azure managed disk snapshots across regions | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-copy-incremental-snapshot-across-regions |
| Deploy and configure Premium SSD v2 managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-deploy-premium-v2 |
| Deploy zone-redundant (ZRS) managed disks in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-deploy-zrs |
| Configure on-demand bursting for Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-bursting |
| Configure and deploy Azure Ultra Disks for VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-ultra-ssd |
| Convert managed disks from LRS to ZRS storage | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-migrate-lrs-zrs |
| Change Azure managed disk performance tiers | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-performance-tiers |
| Enable and configure Azure managed shared disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-shared-enable |
| Configure Torn-Write Prevention on Linux Managed Disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-torn-write-prevention |
| Supported OS images for Azure remote NVMe | https://learn.microsoft.com/en-us/azure/virtual-machines/enable-nvme-interface |
| Deploy Azure VMs with ephemeral OS disks | https://learn.microsoft.com/en-us/azure/virtual-machines/ephemeral-os-disks-deploy |
| Configure Azure Monitor Dependency agent extension on Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/agent-dependency-linux |
| Configure Azure Monitor Dependency agent extension on Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/agent-dependency-windows |
| Install and configure Azure Linux VM Agent (waagent) | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/agent-linux |
| Install and detect Azure Windows VM Agent | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/agent-windows |
| Configure Chef VM extension on Azure Linux and Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/chef |
| Configure Custom Script Extension v2 on Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-linux |
| Configure Custom Script Extension on Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-windows |
| Define DSC VM extension in Azure Resource Manager templates | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/dsc-template |
| Configure DSC extension handler on Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/dsc-windows |
| Enable and configure InfiniBand on Azure HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/enable-infiniband |
| Enable and configure InfiniBand on Azure HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/enable-infiniband |
| Export ARM templates for VMs with extensions | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/export-templates |
| Use Machine Configuration extension to audit and configure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/guest-configuration |
| Configure Application Health extension for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/health-extension |
| Configure InfiniBand driver extension on Azure Linux HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpc-compute-infiniband-linux |
| Configure InfiniBand driver extension on Azure Windows HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpc-compute-infiniband-windows |
| Configure AMD GPU driver extension on Azure Linux N-series VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpccompute-amd-gpu-linux |
| Configure AMD GPU driver extension on Azure Windows NVv4 VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpccompute-amd-gpu-windows |
| Configure NVIDIA GPU driver extension on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpccompute-gpu-linux |
| Configure NVIDIA GPU driver extension on Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/hpccompute-gpu-windows |
| Configure Azure Key Vault VM extension for Linux certificates | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/key-vault-linux |
| Configure Azure Key Vault VM extension for Windows certificates | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/key-vault-windows |
| Configure Qualys Cloud Agent extension on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/qualys |
| Configure Salt Minion VM extension on Azure Linux and Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/salt-minion |
| Configure Stackify Retrace agent extension on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/stackify-retrace-linux |
| Configure Tenable One-Click Nessus agent extension on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/tenable |
| Update and configure Azure Linux Agent on VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/update-linux-agent |
| Use VM Snapshot Linux extension for Azure Backup | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/vmsnapshot-linux |
| Use VM Snapshot Windows extension for Azure Backup | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/vmsnapshot-windows |
| Configure Azure FPGA Attestation for NP-series VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/field-programmable-gate-arrays-attestation |
| Enable and configure Azure Write Accelerator | https://learn.microsoft.com/en-us/azure/virtual-machines/how-to-enable-write-accelerator |
| Install Azure VM Watch via ARM, CLI, PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/install-vm-watch |
| Use Azure Instance Metadata Service from VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/instance-metadata-service |
| Install AMD Radeon V710 GPU drivers on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/azure-n-series-amd-gpu-driver-linux-installation-guide |
| Configure azure-vm-utils for Linux VM device management | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/azure-virtual-machine-utilities |
| Create and upload CentOS VHDs to Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-centos |
| Prepare Linux systems for Azure imaging | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-generic |
| Create and upload OpenBSD images for Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-openbsd |
| Create and upload Ubuntu VHDs for Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-ubuntu |
| Prepare Debian VHD images for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/debian-create-upload-vhd |
| Enable Azure Disk Encryption on Linux VMs with Entra App | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-linux-aad |
| Create and upload Flatcar Linux VHDs to Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/flatcar-create-upload-vhd |
| Configure LVM and RAID on ADE-encrypted Linux disks | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/how-to-configure-lvm-raid-on-crypt |
| Resize Linux disks encrypted with Azure Disk Encryption | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/how-to-resize-encrypted-lvm |
| Author Azure Image Builder Bicep and ARM templates | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-json |
| Configure multiple NICs on Linux Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/multiple-nics |
| Configure NVIDIA GPU drivers on Azure N-series Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/n-series-driver-setup |
| Configure OpenShift deployment on Azure Stack Hub | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/openshift-azure-stack |
| Create and upload Oracle Linux VHDs to Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/oracle-create-upload-vhd |
| Prepare and upload RHEL VHDs for Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/redhat-create-upload-vhd |
| Use Run Command to execute scripts on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/run-command |
| Use managed Run Command on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/run-command-managed |
| Configure internal DNS names for Linux VMs via CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/static-dns-name-resolution-for-linux-on-azure |
| Create and upload SUSE Linux VHDs in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/suse-create-upload-vhd |
| Configure time synchronization for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/time-sync |
| Configure xrdp and desktop environment on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/use-remote-desktop |
| Configure cloud-init support for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/using-cloud-init |
| Define VM maintenance configurations using Bicep | https://learn.microsoft.com/en-us/azure/virtual-machines/maintenance-configurations-bicep |
| Reference for Azure VM monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/virtual-machines/monitor-vm-reference |
| Convert Linux Azure VMs from SCSI to NVMe | https://learn.microsoft.com/en-us/azure/virtual-machines/nvme-linux |
| Configure InfiniBand networking on Azure HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/setup-infiniband |
| Configure MPI for Azure HB and N-series HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/setup-mpi |
| Configure MPI for Azure HB and N-series HPC VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/setup-mpi |
| Create and use Azure VM disk snapshots | https://learn.microsoft.com/en-us/azure/virtual-machines/snapshot-copy-managed-disk |
| Configure and use Soft Delete in Compute Gallery | https://learn.microsoft.com/en-us/azure/virtual-machines/soft-delete-gallery |
| Implement incremental snapshot backup for unmanaged disks | https://learn.microsoft.com/en-us/azure/virtual-machines/unmanaged-disks-incremental-snapshots |
| List, update, and delete Azure Compute Gallery resources | https://learn.microsoft.com/en-us/azure/virtual-machines/update-image-resources |
| Configure Premium SSD v2 disks in availability sets | https://learn.microsoft.com/en-us/azure/virtual-machines/use-premium-ssd-v2-with-availability-set |
| Configure user data scripts for Azure virtual machines | https://learn.microsoft.com/en-us/azure/virtual-machines/user-data |
| Configure managed vs unmanaged disks in ARM templates | https://learn.microsoft.com/en-us/azure/virtual-machines/using-managed-disks-template-deployments |
| Create maintenance control configurations with ARM templates | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machine-scale-sets-maintenance-control-template |
| Configure VM Snapshot extensions for application-consistent restore points | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machines-restore-points-vm-snapshot-extension |
| Configure and deploy VM Applications via Azure Compute Gallery | https://learn.microsoft.com/en-us/azure/virtual-machines/vm-applications-how-to |
| Configure VM vCore customization and SMT settings | https://learn.microsoft.com/en-us/azure/virtual-machines/vm-customization |
| Configure VM Watch collectors, checks, and metrics | https://learn.microsoft.com/en-us/azure/virtual-machines/vm-watch-collector-suite |
| Configure SSH connectivity to Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/connect-ssh |
| Set up WinRM access for Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/connect-winrm |
| Create and Encrypt Windows VM Using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-cli-quickstart |
| Enable Azure Disk Encryption for Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview |
| Prerequisites for Azure Disk Encryption with Entra ID | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview-aad |
| Encrypt Windows VM Disks via Azure Portal | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-portal-quickstart |
| Create and Encrypt Windows VM Using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-powershell-quickstart |
| Azure Disk Encryption Scenarios for Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-windows |
| Enable Azure Disk Encryption with Entra ID on Windows | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-windows-aad |
| Configure Azure Diagnostics Extension for Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/extensions-diagnostics |
| Set up time sync for AD domain Windows VMs in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/external-ntpsource-configuration |
| Configure multiple NICs on Windows Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/multiple-nics |
| Install AMD GPU drivers on Azure N-series Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/n-series-amd-driver-setup |
| Configure NVIDIA GPU drivers on Azure N-series Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/n-series-driver-setup |
| Use Run Command to execute PowerShell on Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/run-command |
| Use managed Run Command to execute scripts in Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/run-command-managed |
| Define Azure virtual machines in ARM templates | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/template-description |
| Configure time synchronization for Azure Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/time-sync |
| Configure in-place upgrade to Ubuntu Pro on Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/workloads/canonical/ubuntu-pro-in-place-upgrade |

### Deployment
| Topic | URL |
|-------|-----|
| Move Azure Marketplace VM to another subscription via CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/azure-cli-change-subscription-marketplace |
| Migrate Linux VMs to Azure Premium Storage using Site Recovery | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/migrate-to-premium-storage-using-azure-site-recovery |
| Configure rolling deployments with Azure Pipelines for Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-devops-azure-pipelines-classic |
| Enable MSP on existing Azure VMs and scale sets | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/brownfield |
| Deploy Azure VMs or scale sets with MSP enabled | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/greenfield |
| FAQ for moving Azure VMs from regional to zonal | https://learn.microsoft.com/en-us/azure/virtual-machines/move-virtual-machines-regional-zonal-faq |
| Perform in-place Windows Server upgrades on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows-in-place-upgrade |
| Migrate Azure VMs from unmanaged to managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/migrate-to-managed-disks |
| Migrate Windows VMs to Azure Premium Storage using Site Recovery | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/migrate-to-premium-storage-using-azure-site-recovery |
| Migrate VHDs from AWS or on-prem to Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/on-prem-to-azure |
| Implement blue-green deployments to Linux VMs with Azure Pipelines | https://learn.microsoft.com/en-us/previous-versions/azure/virtual-machines/linux/tutorial-azure-devops-blue-green-strategy |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate VM Watch signals with Azure Event Hubs | https://learn.microsoft.com/en-us/azure/virtual-machines/configure-eventhub-vm-watch |
| Create Azure VM restore points using REST APIs | https://learn.microsoft.com/en-us/azure/virtual-machines/create-restore-points |
| Register Azure Backup for SQL Server on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/backup-azure-sql-server-running-azure-vm |
| Build Linux Azure VM images with Packer | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/build-image-with-packer |
| Manage Azure virtual machines using common Azure CLI commands | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cli-manage |
| Find Azure Marketplace image URNs and plans using CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cli-ps-findimage |
| Set Linux VM hostnames with cloud-init on Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cloudinit-update-vm-hostname |
| Download Linux VHDs from Azure using portal and CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/download-vhd |
| Retrieve Azure VM CPU metrics via Monitor REST API | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/metrics-vm-usage-rest |
| Create a Linux VM cluster on Azure with Terraform | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-cluster-create-terraform |
| Deploy an Ubuntu VM on Azure using Bicep | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-bicep |
| Create an Ubuntu VM with an ARM template | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-template |
| Provision a Linux VM on Azure using Terraform | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-terraform |
| Use Scheduled Events on Linux Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/scheduled-events |
| Manage VM maintenance configurations using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/maintenance-configurations-cli |
| Configure VM maintenance settings with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/maintenance-configurations-powershell |
| Retrieve Azure VM maintenance notifications with CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/maintenance-notifications-cli |
| Get Azure VM maintenance notifications with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/maintenance-notifications-powershell |
| Specify Azure Marketplace purchase plan for gallery images with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/marketplace-images |
| Query Azure VM availability via Resource Graph | https://learn.microsoft.com/en-us/azure/virtual-machines/resource-graph-availability |
| CLI scripts to copy managed disks across subscriptions | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/copy-managed-disks-to-same-or-different-subscription |
| CLI script to export managed disk VHDs to storage accounts | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/copy-managed-disks-vhd-to-storage-account |
| CLI scripts to copy managed disk snapshots across subscriptions | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/copy-snapshot-to-same-or-different-subscription |
| CLI script to export snapshots to another region storage account | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/copy-snapshot-to-storage-account |
| Create managed disk from snapshot using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/create-managed-disk-from-snapshot |
| Create Azure managed disk from VHD via CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/create-managed-disk-from-vhd |
| Create VM by attaching existing managed OS disk | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/create-vm-from-managed-os-disks |
| Create Azure VM from OS disk snapshot via CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/create-vm-from-snapshot |
| PowerShell script to export managed disk VHDs across regions | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-copy-managed-disks-vhd |
| PowerShell script to copy managed disk snapshots between subscriptions | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-copy-snapshot-to-same-or-different-subscription |
| PowerShell script to export snapshots as VHDs to storage accounts | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-copy-snapshot-to-storage-account |
| Restore managed disks from snapshot with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-create-managed-disk-from-snapshot |
| Create managed disk from VHD using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-create-managed-disk-from-vhd |
| Use VHD snapshot to create multiple managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/scripts/virtual-machines-powershell-sample-create-snapshot-from-vhd |
| Control scale set OS image upgrades with Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machine-scale-sets-maintenance-control-cli |
| Control scale set OS image upgrades with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machine-scale-sets-maintenance-control-powershell |
| Create VM restore points using Azure CLI commands | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machines-create-restore-points-cli |
| Create VM restore points with Azure PowerShell Az module | https://learn.microsoft.com/en-us/azure/virtual-machines/virtual-machines-create-restore-points-powershell |
| Create Windows Azure VM images with Packer and PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/build-image-with-packer |
| Change Azure VM availability set using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/change-availability-set |
| Find Azure Marketplace image URNs and plans using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/cli-ps-findimage |
| Sample Scripts for Azure Disk Encryption on Windows | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-sample-scripts |
| Download Windows VHDs from Azure using the portal | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/download-vhd |
| Automate Azure VM lifecycle using Java SDK | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/java |
| Create and manage Azure virtual networks with PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/ps-common-network-ref |
| Manage Azure virtual machines with common PowerShell commands | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/ps-common-ref |
| Create a Windows VM cluster on Azure with Terraform | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-cluster-create-terraform |
| Deploy a Windows VM on Azure using Bicep | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-bicep |
| Deploy a Windows VM with an ARM template | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-template |
| Provision a Windows VM on Azure using Terraform | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-terraform |
| Monitor Windows VMs for Azure scheduled events | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/scheduled-event-service |
| Use Scheduled Events on Windows Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/scheduled-events |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Work with Azure VM sizes without temp disks | https://learn.microsoft.com/en-us/azure/virtual-machines/azure-vms-no-temp-disk |
| Understand overallocation limits for capacity reservations | https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-overallocate |
| Create legacy managed images and understand constraints | https://learn.microsoft.com/en-us/azure/virtual-machines/capture-image-resource |
| Azure Compute API throttling limits by region | https://learn.microsoft.com/en-us/azure/virtual-machines/compute-throttling-limits |
| Review support matrix and limits for Azure VM restore points | https://learn.microsoft.com/en-us/azure/virtual-machines/concepts-restore-points |
| Use constrained vCPU Azure VM size options | https://learn.microsoft.com/en-us/azure/virtual-machines/constrained-vcpu |
| Compute optimized Dedicated Host SKU capacities and packing | https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-host-compute-optimized-skus |
| General purpose Dedicated Host SKU capacities and packing | https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-host-general-purpose-skus |
| Check GPU-optimized Dedicated Host SKU capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-host-gpu-optimized-skus |
| Memory optimized Dedicated Host SKU capacities and packing | https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-host-memory-optimized-skus |
| Check storage-optimized Dedicated Host SKU capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-host-storage-optimized-skus |
| Use Azure managed disk and VM bursting effectively | https://learn.microsoft.com/en-us/azure/virtual-machines/disk-bursting |
| Understand Azure managed disk performance tiers | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-change-performance |
| Increase IOPS and Throughput with Performance Plus | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-performance |
| Retirement timeline and behavior for Standard HDD OS disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-hdd-os-retirement |
| Use incremental snapshots for Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-incremental-snapshots |
| Access Azure managed disk snapshots instantly | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-instant-access-snapshots |
| Interpret Azure VM disk performance metrics | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-metrics |
| Choose Managed Disk Performance Options in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-performance-options |
| Use Disk Reservations to Optimize Azure Storage Costs | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-reserved-capacity |
| Review scalability and performance targets for Azure VM disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-scalability-targets |
| Select Azure managed disk type by performance limits | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-types |
| Reference Ebsv5 and Ebdsv5 VM size limits | https://learn.microsoft.com/en-us/azure/virtual-machines/ebdsv5-ebsv5-series |
| Reference ECas_cc_v5 and ECads_cc_v5 VM limits | https://learn.microsoft.com/en-us/azure/virtual-machines/ecasccv5-ecadsccv5-series |
| Reference ECasv5 and ECadsv5 confidential VM limits | https://learn.microsoft.com/en-us/azure/virtual-machines/ecasv5-ecadsv5-series |
| Reference ECesv6 confidential VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/ecesv5-ecedsv5-series |
| FAQ for remote NVMe disks on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/enable-nvme-remote-faqs |
| FAQ for temporary NVMe disks on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/enable-nvme-temp-faqs |
| Use ephemeral OS disks for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/ephemeral-os-disks |
| Ephemeral OS disks FAQ and constraints | https://learn.microsoft.com/en-us/azure/virtual-machines/ephemeral-os-disks-faq |
| Reference Ev3 and Esv3 Azure VM specs | https://learn.microsoft.com/en-us/azure/virtual-machines/ev3-esv3-series |
| Azure VM disk FAQs with sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/faq-for-disks |
| HX-series VM performance benchmarks and scaling | https://learn.microsoft.com/en-us/azure/virtual-machines/hx-performance |
| Configure Azure Image Builder triggers and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/image-builder-triggers-how-to |
| Upload or copy managed disks with CLI and AzCopy | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disks-upload-vhd-to-managed-disk-cli |
| Expand Linux VM OS and data disks in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/expand-disks |
| Linux Azure VM FAQ including limits and support details | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/faq |
| Plan around NCv3 VM retirement timelines | https://learn.microsoft.com/en-us/azure/virtual-machines/ncv3-retirement |
| Understand and manage Azure VM vCPU quotas | https://learn.microsoft.com/en-us/azure/virtual-machines/quotas |
| Reference Fadsv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fadsv7-series |
| Reference Faldsv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/faldsv7-series |
| Reference Falsv6 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/falsv6-series |
| Reference Falsv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/falsv7-series |
| Reference Famdsv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/famdsv7-series |
| Reference Famsv6 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/famsv6-series |
| Reference Famsv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/famsv7-series |
| Reference Fasv6 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fasv6-series |
| Reference Fasv7 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fasv7-series |
| Reference Fsv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fsv2-series |
| Reference FX Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fx-series |
| Reference FXmdsv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fxmdsv2-series |
| Reference FXmsv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/compute-optimized/fxmsv2-series |
| Review specs for Azure NMads MA35d video transcoding VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/fpga-accelerated/nm-ads-ma35d-series |
| Use NP-series FPGA VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/fpga-accelerated/np-series |
| Review Azure A-series VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/a-family |
| Use Av2-series Azure VMs with detailed specs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/av2-series |
| Select B-series Azure VMs and credit limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/b-family |
| Evaluate Basv2-series burstable VM capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/basv2-series |
| Assess Bpsv2-series Arm VM size limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/bpsv2-series |
| Plan workloads on Bsv2-series Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/bsv2-series |
| Bv1-series VM specifications and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/bv1-series |
| Explore D-family Azure VM size capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/d-family |
| Reference Dadsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dadsv5-series |
| Reference Dadsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dadsv6-series |
| Plan Dadsv7-series VMs and storage limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dadsv7-series |
| Reference Daldsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/daldsv6-series |
| Configure Daldsv7-series VMs and NVMe limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/daldsv7-series |
| Reference Dalsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dalsv6-series |
| Right-size Dalsv7-series VMs by capacity | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dalsv7-series |
| Reference Dasv4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dasv4-series |
| Reference Dasv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dasv5-series |
| Reference Dasv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dasv6-series |
| Use Dasv7-series VMs with size constraints | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dasv7-series |
| Reference Dav4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dav4-series |
| Reference DCads_cc_v5 parent VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcadsccv5-series |
| Reference DCadsv5 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcadsv5-series |
| Reference DCadsv6 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcadsv6-series |
| Reference DCas_cc_v5 parent VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcasccv5-series |
| Reference DCasv5 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcasv5-series |
| Reference DCasv6 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcasv6-series |
| Reference DCdsv3 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcdsv3-series |
| Reference DCesv6 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcesv6-series |
| Reference DCsv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcsv2-series |
| Reference DCsv3 confidential VM specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dcsv3-series |
| Reference Ddsv4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/ddsv4-series |
| Reference Ddsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/ddsv5-series |
| Deploy Ddsv6-series VMs and storage capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/ddsv6-series |
| Reference Ddv4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/ddv4-series |
| Reference Ddv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/ddv5-series |
| Reference Dldsv5 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dldsv5-series |
| Reference Dldsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dldsv6-series |
| Reference Dlsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dlsv5-series |
| Plan Dlsv6-series VMs and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dlsv6-series |
| Reference Dpdsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpdsv5-series |
| Reference Dpdsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpdsv6-series |
| Reference Dpldsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpldsv5-series |
| Reference Dpldsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpldsv6-series |
| Reference Dplsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dplsv5-series |
| Reference Dplsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dplsv6-series |
| Reference Dpsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpsv5-series |
| Reference Dpsv6 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dpsv6-series |
| Reference Dsv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dsv2-series |
| Dsv3-series VM specifications and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dsv3-series |
| Reference Dsv4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dsv4-series |
| Reference Dsv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dsv5-series |
| Use Dsv6-series VMs with defined capacities | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dsv6-series |
| Reference Dv2 Azure VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dv2-series |
| Dv3-series VM specifications and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dv3-series |
| Reference Dv4 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dv4-series |
| Reference Dv5 VM size specifications and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/general-purpose/dv5-series |
| Reference specs for Azure NC GPU-optimized VM family | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nc-family |
| Evaluate NC RTX PRO 6000 BSE v6 VM specs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nc-rtxpro6000-bse-v6-series |
| Use NC A100 v4 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nca100v4-series |
| Reference specs for Azure NCads H100 v5 GPU VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ncadsh100v5-series |
| Use NCasT4_v3 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ncast4v3-series |
| Check NCCads H100 v5 VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nccadsh100v5-series |
| Use ND GB200-v6 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nd-gb200-v6-series |
| Use ND GB300-v6 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nd-gb300-v6-series |
| Use ND H200 v5 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nd-h200-v5-series |
| Review retired ND-series GPU VM specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nd-series |
| Use ND A100 v4 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ndasra100v4-series |
| Use ND H100 v5 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ndh100v5-series |
| Use NDm A100 v4 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ndma100v4-series |
| Use ND MI300X v5 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ndmi300xv5-series |
| Use NDv2 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ndv2-series |
| Use NGads V620 gaming VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/ngadsv620-series |
| Check detailed specs for Azure NV-series GPU VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nv-series |
| Use NVadsA10_v5 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nvadsa10v5-series |
| Use NVads V710 v5 GPU VM size specifications | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nvadsv710-v5-series |
| Review specs for Azure NVv3 GPU VM sizes | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nvv3-series |
| Review specs for Azure NVv4 partial-GPU VM sizes | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/gpu-accelerated/nvv4-series |
| HBv2 VM size specifications and hardware limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hbv2-series |
| HBv3 VM size specs and capacity limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hbv3-series |
| HBv4 VM size specifications and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hbv4-series |
| HBv5 VM size specs, bandwidth, and storage limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hbv5-series |
| HC VM size specifications and hardware limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hc-series |
| HX VM size specifications and memory capacity limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/high-performance-compute/hx-series |
| Reference Dndsv6 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/dndsv6-series |
| Reference Dnldsv6 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/dnldsv6-series |
| Reference Dnlsv6 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/dnlsv6-series |
| Reference Dnsv6 VM size specs and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/dnsv6-series |
| Review memory-optimized Dv2/Dsv2 VM specs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/dv2-dsv2-series-memory |
| Reference VM specs for Azure Eadsv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/eadsv5-series |
| Reference VM specs for Azure Eadsv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/eadsv6-series |
| Reference VM specs for Azure Eadsv7 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/eadsv7-series |
| Reference Easv4 VM sizes and storage limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/easv4-series |
| Reference VM specs for Azure Easv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/easv5-series |
| Reference VM specs for Azure Easv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/easv6-series |
| Reference VM specs for Azure Easv7 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/easv7-series |
| Reference Eav4 VM sizes and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/eav4-series |
| List Eb family VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/eb-family |
| Reference Ebdsv6 VM sizes and resource limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ebdsv6-series |
| Reference Ebsv6 VM sizes and storage throughput | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ebsv6-series |
| List EC family confidential VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ec-family |
| Reference ECadsv6 confidential VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ecadsv6-series |
| Reference ECasv6 confidential VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ecasv6-series |
| Reference VM specs for Azure Edsv4 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/edsv4-series |
| Reference VM specs for Azure Edsv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/edsv5-series |
| Reference VM specs for Azure Edsv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/edsv6-series |
| Reference VM specs for Azure Edv4 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/edv4-series |
| Reference VM specs for Azure Edv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/edv5-series |
| Reference VM specs for Azure Endsv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/endsv6-series |
| Reference VM specs for Azure Ensv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ensv6-series |
| Reference VM specs for Azure Epdsv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/epdsv5-series |
| Reference VM specs for Azure Epdsv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/epdsv6-series |
| Reference VM specs for Azure Epsv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/epsv5-series |
| Reference VM specs for Azure Epsv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/epsv6-series |
| Reference Esv4 VM sizes and performance limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/esv4-series |
| Reference VM specs for Azure Esv5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/esv5-series |
| Reference VM specs for Azure Esv6 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/esv6-series |
| Reference Ev4 VM sizes and capacity limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ev4-series |
| Reference VM specs for Azure Ev5 series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/ev5-series |
| List M family ultra memory VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/m-family |
| Reference M-series VM sizes and ultra memory limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/m-series |
| Reference specs for Azure Mbdsv3 memory-storage VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mbdsv3-series |
| Reference specs for Azure Mbsv3 memory-storage VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mbsv3-series |
| Reference Mdsv2 Medium Memory VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mdsv2-mm-series |
| Reference specs for Azure Mdsv3 High Memory VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mdsv3-hm-series |
| Reference Mdsv3 Medium Memory VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mdsv3-mm-series |
| Reference specs for Azure Mdsv3 Very High Memory VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mdsv3-vhm-series |
| Reference Msv2 Medium Memory VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/msv2-mm-series |
| Reference specs for Azure Msv3 High Memory VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/msv3-hm-series |
| Reference Msv3 Medium Memory VM sizes and limits | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/msv3-mm-series |
| Reference specs for Azure Msv2 High Memory VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/memory-optimized/mv2-series |
| List of previous-generation and capacity-limited VM series | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/previous-gen-sizes-list |
| Av1-series VM retirement schedule and constraints | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/retirement/av1-series-retirement |
| Retirement timeline for Azure Msv2 and Mdsv2 sizes | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/retirement/msv2-mdsv2-retirement |
| Plan for ND-series VM retirement deadlines | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/retirement/nd-series-retirement |
| Check retired Azure VM series and replacements | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/retirement/retired-sizes-list |
| Reference specs for Azure L family storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/l-family |
| Reference specs for Azure Laosv4 storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/laosv4-series |
| Reference specs for Azure Lasv3 storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/lasv3-series |
| Reference specs for Azure Lasv4 storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/lasv4-series |
| Reference Lsv2 Azure storage-optimized VM specs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/lsv2-series |
| Reference specs for Azure Lsv3 storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/lsv3-series |
| Reference specs for Azure Lsv4 storage-optimized VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/storage-optimized/lsv4-series |
| Upload or copy managed disks with PowerShell direct upload | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disks-upload-vhd-to-managed-disk-powershell |
| Expand Windows VM OS and data disks in Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/expand-disks |
| Windows Azure VM FAQ including limits and configuration details | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/faq |
| Prepare Windows VHD images with Azure size limits | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/prepare-for-upload-vhd-image |
| Retirement details for Azure NC-series GPU VMs | https://learn.microsoft.com/en-us/previous-versions/azure/virtual-machines/sizes/retirement/nc-series-retirement |

### Security
| Topic | URL |
|-------|-----|
| Configure boot integrity monitoring and guest attestation | https://learn.microsoft.com/en-us/azure/virtual-machines/boot-integrity-monitoring-overview |
| Configure server-side encryption for Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disk-encryption |
| Migrate from Azure Disk Encryption to encryption at host | https://learn.microsoft.com/en-us/azure/virtual-machines/disk-encryption-migrate |
| Understand encryption options for Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disk-encryption-overview |
| Configure cross-tenant disk encryption sets with Key Vault | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-cross-tenant-customer-managed-keys |
| Enable customer-managed keys for disks via Azure portal | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-customer-managed-keys-portal |
| Configure double encryption at rest for managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-double-encryption-at-rest-portal |
| Enable host-based disk encryption via Azure portal | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-host-based-encryption-portal |
| Restrict Azure managed disk import/export with Private Link | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-enable-private-links-for-import-export-portal |
| Restrict import and export of Azure managed disks | https://learn.microsoft.com/en-us/azure/virtual-machines/disks-restrict-import-export-overview |
| Enable FIPS 140-3 for Azure Linux VM extensions and agent | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/agent-linux-fips |
| Configure Azure Disk Encryption for Linux VMs via extension | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/azure-disk-enc-linux |
| Configure Azure Disk Encryption for Windows VMs via extension | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/azure-disk-enc-windows |
| Securely pass credentials to Azure VMs using DSC | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/dsc-credentials |
| Enforce Azure Policy to block Linux VM extensions | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/extensions-rmpolicy-howto-cli |
| Use Azure Policy to restrict Windows VM extensions | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/extensions-rmpolicy-howto-ps |
| Deploy Microsoft Antimalware extension on Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/iaas-antimalware-windows |
| Encrypt Azure Compute Gallery image versions with customer-managed keys | https://learn.microsoft.com/en-us/azure/virtual-machines/image-version-encryption |
| Create and manage SSH keys for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-ssh-keys-detailed |
| Create and encrypt Linux VM using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-cli-quickstart |
| Configure Key Vault for Azure Disk Encryption on Linux | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-key-vault |
| Configure Key Vault for Azure Disk Encryption on Linux | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-key-vault-aad |
| Configure Azure Disk Encryption scenarios on Linux | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-linux |
| Enable Azure Disk Encryption on Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-overview |
| Meet Entra app prerequisites for Azure Disk Encryption | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-overview-aad |
| Create and encrypt Linux VM via Azure portal | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-portal-quickstart |
| Create and encrypt Linux VM using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-powershell-quickstart |
| Use sample scripts for Azure Disk Encryption on Linux | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-sample-scripts |
| Upgrade Azure Disk Encryption on existing disks | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-upgrade |
| Enable customer-managed keys for disks using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disks-enable-customer-managed-keys-cli |
| Enable host-based encryption using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disks-enable-host-based-encryption-cli |
| Secure managed disk import/export with Private Links via CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disks-export-import-private-links-cli |
| Verify Azure Disk Encryption status on Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/how-to-verify-encryption-status |
| Configure VM Image Builder permissions with Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-permissions-cli |
| Configure VM Image Builder permissions using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-permissions-powershell |
| Use user-assigned managed identity with Image Builder | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-user-assigned-identity |
| Set up Key Vault for Linux VMs using Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/key-vault-setup |
| Quickly generate SSH keys for Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys |
| Use SSH keys from Windows to access Azure Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/ssh-from-windows |
| Secure Linux NGINX VMs with TLS certificates from Key Vault | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-secure-web-server |
| Configure MSP RBAC allowlists for Azure VM metadata | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/advanced-configuration |
| Configure Metadata Security Protocol for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/configuration |
| Create MSP RBAC allowlists from audit logs | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/other-examples/audit-logs-to-rules |
| Disable Metadata Security Protocol using REST or portal | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/other-examples/disable |
| Configure MSP settings for VMs via Azure portal | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/other-examples/portal |
| Secure Azure VM metadata access with MSP | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/overview |
| Test NSG rules blocking Azure VM traffic | https://learn.microsoft.com/en-us/azure/virtual-machines/network-security-group-test |
| Reference built-in Azure Policy definitions for VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/policy-reference |
| Use Azure Policy regulatory controls for VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/security-controls-policy |
| Map Azure VM Image Builder to regulatory policy controls | https://learn.microsoft.com/en-us/azure/virtual-machines/security-controls-policy-image-builder |
| Apply security features and policies to Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/security-policy |
| Share Azure Compute Gallery resources using RBAC | https://learn.microsoft.com/en-us/azure/virtual-machines/share-gallery |
| Publish Azure Compute Gallery images as community gallery | https://learn.microsoft.com/en-us/azure/virtual-machines/share-gallery-community |
| Directly share Azure Compute Gallery with subscriptions and tenants | https://learn.microsoft.com/en-us/azure/virtual-machines/share-gallery-direct |
| Share Azure Compute Gallery images via app registration | https://learn.microsoft.com/en-us/azure/virtual-machines/share-using-app-registration |
| Create and store SSH keys with Azure CLI | https://learn.microsoft.com/en-us/azure/virtual-machines/ssh-keys-azure-cli |
| Generate and store SSH keys in Azure portal | https://learn.microsoft.com/en-us/azure/virtual-machines/ssh-keys-portal |
| Configure Trusted Launch security for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch |
| Enable Trusted Launch on existing Gen2 Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-existing-vm |
| Upgrade Gen1 Azure VMs to Gen2 Trusted Launch | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-existing-vm-gen-1 |
| Enable Trusted Launch on existing VM scale sets | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-existing-vmss |
| Deploy Azure VMs with Trusted Launch in portal | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-portal |
| Customize Secure Boot UEFI keys for Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-secure-boot-custom-uefi |
| Configure Key Vault Access for Disk Encryption on Windows | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-key-vault |
| Configure Key Vault for Disk Encryption with Entra ID | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-key-vault-aad |
| Enable customer-managed keys for disks using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disks-enable-customer-managed-keys-powershell |
| Enable host-based encryption using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disks-enable-host-based-encryption-powershell |
| Configure Key Vault for Azure VMs using PowerShell | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/key-vault-setup |
| Secure IIS on Windows VMs with TLS certificates in Key Vault | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-secure-web-server |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve Azure Spot VM and scale set error codes | https://learn.microsoft.com/en-us/azure/virtual-machines/error-codes-spot |
| Diagnose and fix Windows VM extension failures | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/troubleshoot |
| Reset and troubleshoot access on Azure Linux VMs with VMAccess | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/vmaccess-linux |
| Reset and troubleshoot access on Azure Windows VMs with VMAccess | https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/vmaccess-windows |
| Troubleshoot common issues on Azure HB and N-series VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/hb-hc-known-issues |
| Troubleshoot Azure VM hibernation issues across Linux and Windows | https://learn.microsoft.com/en-us/azure/virtual-machines/hibernate-resume-troubleshooting |
| Troubleshoot cloud-init provisioning issues on Azure | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cloud-init-troubleshooting |
| Troubleshoot Azure Disk Encryption on isolated Linux networks | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-isolated-network |
| Troubleshoot Azure Disk Encryption for Linux VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-troubleshooting |
| Diagnose and fix Linux VM hibernation issues | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/hibernate-resume-troubleshooting-linux |
| Connect to Azure Image Builder build VM for debugging | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-connect-to-build-vm |
| Troubleshoot Azure VM Image Builder failures | https://learn.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-troubleshoot |
| Troubleshoot MSP key mismatches and reset latched keys | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/other-examples/key-reset |
| Troubleshoot Metadata Security Protocol issues on Azure VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/metadata-security-protocol/troubleshoot-guide |
| Troubleshoot Azure VM restore point failures | https://learn.microsoft.com/en-us/azure/virtual-machines/restore-point-troubleshooting |
| Troubleshoot Azure VM maintenance configuration issues | https://learn.microsoft.com/en-us/azure/virtual-machines/troubleshoot-maintenance-configurations |
| Troubleshoot Azure Compute Gallery shared image issues | https://learn.microsoft.com/en-us/azure/virtual-machines/troubleshooting-shared-images |
| Troubleshoot and understand Azure Trusted Launch FAQs | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch-faq |
| FAQ for Azure Disk Encryption on Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-faq |
| Troubleshoot Azure Disk Encryption Issues on Windows VMs | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-troubleshooting |
| Resolve Windows VM hibernation and resume problems | https://learn.microsoft.com/en-us/azure/virtual-machines/windows/hibernate-resume-troubleshooting-windows |

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
