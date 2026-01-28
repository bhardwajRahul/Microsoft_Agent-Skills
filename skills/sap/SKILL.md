---
name: sap
description: Expert knowledge for Sap development including configuration, deployment, security, integrations & coding patterns, troubleshooting, architecture & design patterns, and best practices. Use when building, debugging, or optimizing Sap applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Sap Skill

This skill provides expert guidance for Sap development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design resiliency for Azure Center for SAP Solutions | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/compliance-bcdr-reliabilty |
| Implement customer-enabled disaster recovery for VIS | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/compliance-cedr |
| Design DBMS deployment for SAP on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-general |
| Run SAP on IBM Db2 for LUW on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-ibm |
| Deploy SAP MaxDB, liveCache, Content Server on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-maxdb |
| Deploy Oracle Database for SAP on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-oracle |
| Deploy SAP ASE database for SAP on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-sapase |
| Implement SAP BW near-line storage with SAP IQ on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-sapiq |
| Deploy SQL Server DBMS for SAP on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-sqlserver |
| Architect SAP disaster recovery on Azure infrastructure | https://learn.microsoft.com/en-us/azure/sap/workloads/disaster-recovery-overview-guide |
| Implement disaster recovery strategy for SAP on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/disaster-recovery-sap-guide |
| Select SAP data extraction options to Microsoft Fabric | https://learn.microsoft.com/en-us/azure/sap/workloads/extract-sap-data |
| Plan SAP HANA data tiering and archiving on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-tiering-guidance |
| Design SAP workloads with Azure Availability Zones | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-zones |
| Plan SAP application architecture and deployment on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/planning-guide |
| Select Azure storage types for SAP workloads | https://learn.microsoft.com/en-us/azure/sap/workloads/planning-guide-storage |
| Minimize SAP application latency with Azure placement options | https://learn.microsoft.com/en-us/azure/sap/workloads/proximity-placement-scenarios |
| Design Azure integration architecture for SAP RISE | https://learn.microsoft.com/en-us/azure/sap/workloads/rise-integration |
| Choose network connectivity options for SAP RISE on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/rise-integration-network |
| Plan SAP HANA availability across Azure regions | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-availability-across-regions |
| Design SAP HANA availability within one Azure region | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-availability-one-region |
| Plan SAP HANA availability architectures on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-availability-overview |
| Choose Azure VM HA architectures for SAP NetWeaver | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-architecture-scenarios |
| Use Azure VM restart for higher SAP availability | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-higher-availability-architecture-scenarios |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply SAP on Azure planning and deployment checklist | https://learn.microsoft.com/en-us/azure/sap/workloads/deployment-checklist |
| Configure Azure VM storage for SAP HANA | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-operations-storage |
| Design Premium SSD storage for SAP HANA VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-premium-ssd-v1 |
| Design Premium SSD v2 storage for SAP HANA VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-premium-ssd-v2 |
| Configure Azure Ultra Disk storage for SAP HANA | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-ultra-disk |
| Install HA SAP NetWeaver on Azure using Azure Files SMB | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-windows-azure-files-smb |
| Use Azure Premium Files NFS and SMB for SAP | https://learn.microsoft.com/en-us/azure/sap/workloads/planning-guide-storage-azure-files |

### Configuration
| Topic | URL |
|-------|-----|
| Manage SAP Terraform state with advanced_state_management script | https://learn.microsoft.com/en-us/azure/sap/automation/bash/advanced-state-management |
| Bootstrap SAP deployer with install_deployer.sh | https://learn.microsoft.com/en-us/azure/sap/automation/bash/install-deployer |
| Bootstrap SAP Library using install_library.sh | https://learn.microsoft.com/en-us/azure/sap/automation/bash/install-library |
| Use installer.sh to deploy SAP systems on Azure | https://learn.microsoft.com/en-us/azure/sap/automation/bash/installer |
| Remove SAP control plane with remove_controlplane.sh | https://learn.microsoft.com/en-us/azure/sap/automation/bash/remove-controlplane |
| Tear down SAP systems using remover.sh | https://learn.microsoft.com/en-us/azure/sap/automation/bash/remover |
| Customize disk layouts in SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/configure-extra-disks |
| Configure SAP Ansible parameter files | https://learn.microsoft.com/en-us/azure/sap/automation/configure-sap-parameters |
| Define SAP system tfvars for automation | https://learn.microsoft.com/en-us/azure/sap/automation/configure-system |
| Configure SAP deployment web app in Azure | https://learn.microsoft.com/en-us/azure/sap/automation/configure-webapp |
| Apply standard naming for SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/naming |
| Customize resource naming in SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/naming-module |
| Configure SAP automation for new vs existing Azure setups | https://learn.microsoft.com/en-us/azure/sap/automation/new-vs-existing |
| Bash script reference for SAP automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/reference-bash |
| Configure external tools for SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/tools-configuration |
| Configure datasets and templates in Business Process Solutions | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/configure-dataset |
| Run data extraction and processing in Business Process Solutions | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/run-extraction-data-processing |
| Configure Azure Backup for SAP via VIS | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/acss-backup-integration |
| Prepare and upload SAP installation media to Azure Storage | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/get-sap-installation-media |
| Configure and inspect VIS properties in Azure | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/manage-virtual-instance |
| Configure virtual network for S/4HANA on Azure Center for SAP | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/prepare-network |
| Reference of log data for Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/data-reference |
| Configure alerts for Azure Monitor for SAP solutions in portal | https://learn.microsoft.com/en-us/azure/sap/monitor/get-alerts-portal |
| Create HA Pacemaker cluster provider for AMS | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-ha-pacemaker-cluster |
| Configure SAP HANA provider in Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-hana |
| Configure IBM Db2 provider for Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-ibm-db2 |
| Configure Linux OS provider for Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-linux |
| Configure SAP NetWeaver provider for Azure Monitor | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-netweaver |
| Configure SQL Server provider for Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/provider-sql-server |
| Configure virtual networks for Azure Monitor for SAP solutions | https://learn.microsoft.com/en-us/azure/sap/monitor/set-up-network |
| Set up IBM Db2 HADR on Azure virtual machines | https://learn.microsoft.com/en-us/azure/sap/workloads/dbms-guide-ha-ibm |
| Install and configure SAP HANA on Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-get-started |
| Configure and operate SAP HANA infrastructure on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-operations |
| Configure Azure NetApp Files for SAP HANA VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/hana-vm-operations-netapp |
| Deploy SAP NetWeaver HA on RHEL Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel |
| Set up GlusterFS cluster on RHEL for SAP on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-glusterfs |
| Configure IBM Db2 HADR on RHEL Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-ibm-db2-luw |
| Configure multi-SID SAP NetWeaver HA on RHEL | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-multi-sid |
| Configure SAP NetWeaver HA on RHEL with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-netapp-files |
| Configure SAP NetWeaver HA on RHEL with NFS on Azure Files | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-nfs-azure-files |
| Configure Pacemaker clustering on RHEL in Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-pacemaker |
| Configure outbound connectivity for SAP HA VMs with Standard Load Balancer | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-standard-load-balancer-outbound-connections |
| Deploy SAP NetWeaver HA on SLES Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse |
| Configure multi-SID SAP NetWeaver HA on SLES | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-multi-sid |
| Configure SAP NetWeaver HA on SLES with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-netapp-files |
| Configure highly available NFS server on SLES for SAP | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-nfs |
| Configure SAP NetWeaver HA on SLES with NFS on Azure Files | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-nfs-azure-files |
| Configure SAP NetWeaver HA on SLES with simple mount NFS | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-nfs-simple-mount |
| Configure Pacemaker clustering on SLES in Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-suse-pacemaker |
| Configure Windows DFS-N for SAPMNT with Azure SMB shares | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-windows-dfs |
| Configure SAP LaMa connector for Azure VM operations | https://learn.microsoft.com/en-us/azure/sap/workloads/lama-installation |
| Configure SAP HANA high availability on SLES VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability |
| Set up SAP HANA scale-up HA with Azure NetApp Files on RHEL | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability-netapp-files-red-hat |
| Configure SAP HANA scale-up HA with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability-netapp-files-suse |
| Configure SAP HANA high availability on RHEL Azure VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability-rhel |
| Configure SAP HANA scale-out with HSR and Pacemaker on RHEL | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability-scale-out-hsr-rhel |
| Configure SAP HANA scale-out with HSR and Pacemaker | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-high-availability-scale-out-hsr-suse |
| Deploy SAP HANA scale-out with standby using Azure NetApp Files | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-scale-out-standby-netapp-files-rhel |
| Deploy SAP HANA scale-out with standby on ANF | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-hana-scale-out-standby-netapp-files-suse |
| Cluster SAP ASCS/SCS on WSFC with shared disk in Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-guide-wsfc-shared-disk |
| Deploy and configure Azure VM extension for SAP solutions | https://learn.microsoft.com/en-us/azure/sap/workloads/vm-extension-for-sap |
| Configure the new Azure VM extension for SAP solutions | https://learn.microsoft.com/en-us/azure/sap/workloads/vm-extension-for-sap-new |

### Deployment
| Topic | URL |
|-------|-----|
| Use Bash script to deploy SAP control plane | https://learn.microsoft.com/en-us/azure/sap/automation/bash/deploy-controlplane |
| Use Bash script to deploy SAP workload zone | https://learn.microsoft.com/en-us/azure/sap/automation/bash/install-workloadzone |
| Get SAP media for automation framework BOM | https://learn.microsoft.com/en-us/azure/sap/automation/bom-get-files |
| Prepare SAP Bill of Materials for automation | https://learn.microsoft.com/en-us/azure/sap/automation/bom-prepare |
| Generate SAP application installation templates for BOM | https://learn.microsoft.com/en-us/azure/sap/automation/bom-templates-db |
| Configure control plane for SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/configure-control-plane |
| Set up Azure DevOps for SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/configure-devops |
| Design and configure SAP workload zones | https://learn.microsoft.com/en-us/azure/sap/automation/configure-workload-zone |
| Deploy control plane for SAP automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/deploy-control-plane |
| Deploy SAP systems using automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/deploy-system |
| Deploy SAP workload zones with automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/deploy-workload-zone |
| Use SAP automation framework with Azure DevOps | https://learn.microsoft.com/en-us/azure/sap/automation/devops-tutorial |
| Supported topologies matrix for SAP automation | https://learn.microsoft.com/en-us/azure/sap/automation/supportability |
| Supported platforms and features for SAP Testing Automation Framework | https://learn.microsoft.com/en-us/azure/sap/automation/testing-framework-supportability |
| Tutorial: Deploy SAP automation framework at scale | https://learn.microsoft.com/en-us/azure/sap/automation/tutorial |
| Upgrade SAP Deployment Automation Framework safely | https://learn.microsoft.com/en-us/azure/sap/automation/upgrading |
| Deploy Business Process Solutions workload item in Fabric | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/deploy-workload-item |
| Deploy S/4HANA infrastructure with Azure Center for SAP | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/deploy-s4hana |
| Install SAP software on infrastructure deployed via Azure Center for SAP | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/install-software |
| Register existing SAP systems in Azure Center for SAP solutions | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/register-existing-system |
| Deploy SAP Business One on Azure Virtual Machines | https://learn.microsoft.com/en-us/azure/sap/workloads/business-one-azure |
| Plan and deploy SAP BusinessObjects BI on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/businessobjects-deployment-guide |
| Deploy SAP BusinessObjects BI on Azure for Linux | https://learn.microsoft.com/en-us/azure/sap/workloads/businessobjects-deployment-guide-linux |
| Deploy SAP BusinessObjects BI on Azure for Windows | https://learn.microsoft.com/en-us/azure/sap/workloads/businessobjects-deployment-guide-windows |
| Use Azure SAP certification tables for supported deployments | https://learn.microsoft.com/en-us/azure/sap/workloads/certifications |
| Deploy SAP NetWeaver on Azure Linux VMs | https://learn.microsoft.com/en-us/azure/sap/workloads/deployment-guide |
| Add disaster recovery secondary sites to SAP HANA Pacemaker clusters | https://learn.microsoft.com/en-us/azure/sap/workloads/disaster-recovery-sap-hana |
| Deploy SAP dialog instances on RHEL HA ASCS/SCS clusters in Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-with-dialog-instance |
| Deploy SAP ASCS/SCS, ERS, and HANA on RHEL HA VMs in Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-rhel-with-hana-ascs-ers-dialog-instance |
| Deploy HA SAP NetWeaver on Azure VMs with Azure NetApp Files SMB | https://learn.microsoft.com/en-us/azure/sap/workloads/high-availability-guide-windows-netapp-files-smb |
| Determine supported SAP VM scenarios on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/planning-supported-configurations |
| Configure SAP ASCS/SCS multi-SID HA with WSFC and Azure shared disk | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-ascs-ha-multi-sid-wsfc-azure-shared-disk |
| Configure SAP ASCS/SCS multi-SID HA with WSFC and file shares | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-ascs-ha-multi-sid-wsfc-file-share |
| Configure SAP ASCS/SCS multi-SID HA with WSFC and simulated shared disk | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-ascs-ha-multi-sid-wsfc-shared-disk |
| Onboard SAP Edge Integration Cell to Azure AKS and Arc | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-edge-integration-cell-with-azure |
| Cluster SAP ASCS/SCS on WSFC using Azure file shares | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-guide-wsfc-file-share |
| Prepare Azure infrastructure for SAP ASCS/SCS HA with WSFC and file shares | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-infrastructure-wsfc-file-share |
| Prepare Azure infrastructure for SAP ASCS/SCS WSFC with shared disk | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-infrastructure-wsfc-shared-disk |
| Install SAP NetWeaver HA on WSFC with scale-out file server | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-installation-wsfc-file-share |
| Install SAP NetWeaver HA with WSFC shared disk on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-high-availability-installation-wsfc-shared-disk |
| Check which SAP products are supported on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/supported-product-on-azure |
| Deploy SAP workloads using Azure VM scale sets | https://learn.microsoft.com/en-us/azure/sap/workloads/virtual-machine-scale-set-sap-deployment-guide |
| Deploy the standard Azure VM extension for SAP | https://learn.microsoft.com/en-us/azure/sap/workloads/vm-extension-for-sap-standard |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Azure Monitor for SAP with automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/integration-azure-monitor-sap |
| Run Ansible playbooks to configure SAP systems | https://learn.microsoft.com/en-us/azure/sap/automation/run-ansible |
| Download SAP software via Ansible for automation framework | https://learn.microsoft.com/en-us/azure/sap/automation/software |
| Configure Salesforce as a source in Business Process Solutions | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/configure-salesforce-source-system |
| Integrate SAP source systems with Azure Data Factory | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/configure-source-system-with-data-factory |
| Configure SAP S/4HANA and ECC via Open Mirroring | https://learn.microsoft.com/en-us/azure/sap/business-process-solutions/configure-source-system-with-open-mirroring |
| Soft-stop SAP instances and HANA via VIS APIs | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/soft-stop-sap-and-hana-database |
| Control SAP systems via VIS using Azure tools | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/start-stop-sap-systems |
| Start and stop SAP and VMs via VIS REST API | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/stop-start-sap-and-underlying-vm |
| Integrate SAP ABAP outbound email with Exchange Online | https://learn.microsoft.com/en-us/azure/sap/workloads/exchange-online-integration-sap-email-outbound |
| Enable SAP principal propagation for live OData with Power Query | https://learn.microsoft.com/en-us/azure/sap/workloads/expose-sap-odata-to-power-query |
| Integrate Azure services and apps with SAP RISE | https://learn.microsoft.com/en-us/azure/sap/workloads/rise-integration-services |
| Integrate SAP ILM Store with Azure Blob Storage | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-information-lifecycle-management |
| Enable SAP front-end printing via Universal Print | https://learn.microsoft.com/en-us/azure/sap/workloads/universal-print-sap-frontend |

### Security
| Topic | URL |
|-------|-----|
| Set SPN secrets in Key Vault with set_secrets.sh | https://learn.microsoft.com/en-us/azure/sap/automation/bash/set-secrets |
| Update SAP Library SAS token in Key Vault | https://learn.microsoft.com/en-us/azure/sap/automation/bash/update-sas-token |
| Configure Azure RBAC for Azure Center for SAP solutions | https://learn.microsoft.com/en-us/azure/sap/center-sap-solutions/manage-with-azure-rbac |
| Configure TLS 1.2+ for Azure Monitor for SAP | https://learn.microsoft.com/en-us/azure/sap/monitor/enable-tls-azure-monitor-sap-solutions |
| Configure Trusted Access and private endpoints for AMS | https://learn.microsoft.com/en-us/azure/sap/monitor/enable-trusted-access |
| Securely expose SAP Process Orchestration using Azure PaaS | https://learn.microsoft.com/en-us/azure/sap/workloads/expose-sap-process-orchestration-on-azure |
| Integrate Azure identity and security with SAP RISE | https://learn.microsoft.com/en-us/azure/sap/workloads/rise-integration-security |
| Configure Azure Files NFS encryption in transit for SAP systems | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-azure-files-nfs-encryption-in-transit-guide |
| Secure identity and access for SAP on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-security-identity |
| Secure Azure infrastructure foundation for SAP applications | https://learn.microsoft.com/en-us/azure/sap/workloads/sap-security-infrastructure |
| Design Entra ID-based secure access for SAP platforms | https://learn.microsoft.com/en-us/azure/sap/workloads/scenario-azure-first-sap-identity-integration |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot SAP Deployment Automation Framework issues | https://learn.microsoft.com/en-us/azure/sap/automation/troubleshooting |
| Use SAP Insights in AMS to troubleshoot workloads | https://learn.microsoft.com/en-us/azure/sap/monitor/enable-sap-insights |
| Troubleshoot Azure Monitor for SAP solutions via FAQ | https://learn.microsoft.com/en-us/azure/sap/monitor/faq |
| Resolve common issues with SAP VM scale sets on Azure | https://learn.microsoft.com/en-us/azure/sap/workloads/virtual-machine-scale-set-sap-faq |
| Diagnose and fix Azure VM Extension for SAP issues | https://learn.microsoft.com/en-us/azure/sap/workloads/vm-extension-for-sap-troubleshooting |

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
