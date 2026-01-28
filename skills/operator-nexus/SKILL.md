---
name: operator-nexus
description: Expert knowledge for Operator Nexus development including configuration, security, troubleshooting, limits & quotas, best practices, deployment, integrations & coding patterns, and architecture & design patterns. Use when building, debugging, or optimizing Operator Nexus applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Operator Nexus Skill

This skill provides expert guidance for Operator Nexus development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use placement hints for Nexus virtual machine scheduling | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-virtual-machine-placement-hints |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply best practices for Nexus bare metal operations | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-bare-metal-best-practices |

### Configuration
| Topic | URL |
|-------|-----|
| Sample cluster.jsonc configuration for Nexus ARM deployments | https://learn.microsoft.com/en-us/azure/operator-nexus/cluster-jsonc-example |
| Sample cluster.parameters.jsonc for multi-rack Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/cluster-parameters-jsonc-example |
| Use clusterManager.jsonc template for Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/clustermanager-jsonc-example |
| Use clusterManager.parameters.jsonc for Operator Nexus deployments | https://learn.microsoft.com/en-us/azure/operator-nexus/clustermanager-parameters-jsonc-example |
| Disable BGP neighbors using Nexus read-write commands | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-disable-border-gateway-protocol-neighbors |
| Modify Nexus Fabric device configuration with read-write commands | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-network-fabric-read-write-commands |
| Batch update and commit Nexus Network Fabric resources | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-network-fabric-resource-update-commit |
| Automate Nexus Network Fabric operator password rotation v1 | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-password-rotation-v1 |
| Customize CoreDNS and node-local-dns in Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/how-to-customize-kubernetes-cluster-dns |
| Manage IP prefixes and rules in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/how-to-ip-prefixes |
| Create and manage route policies in Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/how-to-route-policy |
| Append custom suffixes to Nexus interface descriptions | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-append-custom-suffix-to-interface-descriptions |
| Apply ACL configurations to Nexus network-to-network interconnects | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-apply-access-control-list-to-network-to-network-interconnects |
| Run lifecycle management commands on Nexus bare metal | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-functions |
| Check runtime versions of key Nexus components | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-check-runtime-version |
| Manage Cluster Manager lifecycle in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-manager |
| Configure metrics collection settings for Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-metrics-configuration-management |
| Configure diagnostic settings and config-drift monitoring for Nexus Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-diagnostic-settings-monitor-configuration-differences |
| Configure L2 and L3 isolation domains in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-isolation-domain |
| Configure Azure Operator Nexus Network Fabric via CLI | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-network-fabric |
| Configure Network Fabric Controller in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-network-fabric-controller |
| Configure Network Packet Broker and TAP rules in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-network-packet-broker |
| Configure ACL rules for Nexus NNIs and L3 external networks | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-create-access-control-list-for-network-to-network-interconnects |
| Delete ACL resources from Nexus network-to-network interconnects | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-delete-access-control-list-network-to-network-interconnect |
| Delete L3 isolation domains in Azure Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-delete-layer-3-isolation-domains |
| Disable cgroupsv2 on Azure Operator Nexus nodes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-disable-cgroupsv2 |
| Disable internal and external networks in Nexus L3 domain | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-disable-internal-external-networks-enabled-layer-3-isolation-domain |
| Configure BMP log streaming for Operator Nexus fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-enable-log-streaming |
| Enable Micro-BFD on Nexus CE and PE devices | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-enable-micro-bfd |
| Install Azure CLI extensions for Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-install-cli-extensions |
| Configure and manage agent pools in Nexus Kubernetes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-agent-pools |
| Customize Nexus Kubernetes worker nodes via DaemonSet | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-customize-workers |
| Configure dual-stack networking for Nexus Kubernetes clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-dual-stack |
| Configure huge pages on Nexus Kubernetes node pools | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-huge-pages |
| Configure service load balancers in Nexus Kubernetes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-service-load-balancer |
| Monitor interface packet rates for Nexus Fabric devices in Azure portal | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-monitor-interface-packet-rate |
| Configure monitoring for Nexus Kubernetes clusters with Container Insights | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-monitor-naks-cluster |
| Configure monitoring for VNF virtual machines on Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-monitor-virtualized-network-functions-virtual-machines |
| Configure QoS policies in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-network-fabric-quality-of-service |
| Put Nexus network devices into maintenance mode safely | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-put-device-in-maintenance-mode |
| Reboot Nexus network devices using graceful and ungraceful modes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-reboot-network-device |
| Restrict serial port access and configure timeouts on Nexus Terminal Servers | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-restrict-serial-port-access-and-set-timeout-on-terminal-server |
| Use administrative lock to protect Nexus fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-set-administrative-lock-or-unlock-for-network-fabric |
| Track Azure Operator Nexus async operations via CLI | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-track-async-operations-cli |
| Update ACL associations for Nexus NNIs and external networks | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-update-access-control-list-for-network-to-network-interconnects |
| Use Commit Workflow v2 to stage Nexus changes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-commit-workflow-v2 |
| Reference available Nexus diagnostic logs for monitoring | https://learn.microsoft.com/en-us/azure/operator-nexus/list-logs-available |
| Use Nexus metrics reference for Azure Monitor integration | https://learn.microsoft.com/en-us/azure/operator-nexus/list-of-metrics-collected |
| Define Azure Nexus Kubernetes clusters with ARM templates | https://learn.microsoft.com/en-us/azure/operator-nexus/quickstarts-kubernetes-cluster-deployment-arm |
| Author Bicep templates for Azure Nexus Kubernetes clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/quickstarts-kubernetes-cluster-deployment-bicep |
| Configure Nexus VNF virtual machines with ARM templates | https://learn.microsoft.com/en-us/azure/operator-nexus/quickstarts-virtual-machine-deployment-arm |
| Define Nexus VNF virtual machines using Bicep | https://learn.microsoft.com/en-us/azure/operator-nexus/quickstarts-virtual-machine-deployment-bicep |
| Configure Azure Operator Nexus ACL traffic policies | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-acl-configuration |
| Configure Provider Edge connectivity for Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-customer-edge-provider-edge-connectivity |
| Configure Azure Operator Nexus isolation domains | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-isolation-domain-configuration |
| Isolation domain configuration examples for Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-isolation-domain-configuration-examples |
| Assign and interpret BareMetal machine roles in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-near-edge-baremetal-machine-roles |
| Configure neighbor groups for load-balanced Nexus traffic | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-neighbor-group-configuration |
| Use Operator Nexus observability metrics for NNF | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-operator-nexus-observability-metrics |
| Configure Azure Operator Nexus route policies | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-route-policy-configuration |

### Deployment
| Topic | URL |
|-------|-----|
| Perform runtime upgrades for Azure Operator Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-runtime-upgrade |
| Use template-based runtime upgrades for Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-runtime-upgrade-template |
| Run Nexus cluster upgrades with PauseAfterRack strategy | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-runtime-upgrade-with-pauseafterrack-strategy |
| Deploy and manage Azure Operator Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-cluster |
| Checklist for decommissioning an Azure Operator Nexus instance | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-decommission-nexus-instance-checklist |
| Restart Azure Operator Nexus Kubernetes cluster nodes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-action-restart |
| Deploy a Nexus instance using parameterized template | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-nexus-instance-deployment-template |
| Complete prerequisites for Azure Operator Nexus deployment | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-platform-prerequisites |
| Replace Nexus network devices via RMA with minimal disruption | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-replace-network-devices |
| Replace a terminal server in Azure Operator Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-replace-terminal-server |
| Upgrade Azure Operator Nexus Network Fabric with validations | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-upgrade-nexus-fabric |
| Template-driven runtime upgrades for Nexus Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-upgrade-nexus-fabric-template |
| Upgrade the operating system of a Nexus Terminal Server | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-upgrade-os-of-terminal-server |
| Perform A/B staged configuration updates in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-ab-staged-commit-configuration-update-commit-workflow |
| Build VM images for Azure Operator Nexus virtual machines | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-virtual-machine-image |
| Match Nexus versions to supported storage software versions | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-near-edge-storage-supported-versions |
| Select supported VM SKUs for Nexus Kubernetes clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-nexus-kubernetes-cluster-sku |
| Plan Kubernetes version lifecycle for Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-nexus-kubernetes-cluster-supported-versions |
| Understand Operator Nexus platform runtime upgrade cadence | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-nexus-platform-runtime-upgrades |
| Reference supported software versions for Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-supported-software-versions |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure BYO storage and UAMI integration for Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-bring-your-own-storage-network-fabric |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use persistent storage classes for Nexus Kubernetes workloads | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-storage-kubernetes |
| Prepare NFC and Cluster Manager deployment for Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-azure-operator-nexus-prerequisites |
| Apply technical limits for Nexus isolation domains | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-isolation-domain-technical-requirements |
| Apply Azure Operator Nexus resource limits and quotas | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-limits-and-quotas |
| Plan near-edge storage appliances for Nexus instances | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-near-edge-storage |

### Security
| Topic | URL |
|-------|-----|
| Manage BMC credential rotation in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-baseboard-management-controller-credential-rotation |
| Configure cross-subscription permissions for Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-cross-subscription-deployments-required-rbac-for-network-fabric |
| Configure access and identity for Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-security-access-identity |
| Configure customer Key Vault for Nexus credential rotation | https://learn.microsoft.com/en-us/azure/operator-nexus/how-to-credential-manager-key-vault |
| Manage emergency SSH access to Nexus BMCs | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-bmc-ssh |
| Manage emergency SSH access to Nexus bare metal machines | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-bmm-ssh |
| Use managed identities and user resources in Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-cluster-managed-identity-user-provided-resources |
| Create SSH ACLs on Nexus management VPN NNI | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-configure-acls-for-ssh-management-on-access-vpn |
| Manage credential rotation lifecycle in Azure Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-credential-rotation |
| Enable or disable vulnerability scanning in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-enable-disable-vulnerability-scanning |
| Configure Entra ID RBAC for Nexus Kubernetes clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-aad-rbac |
| Securely connect to Azure Operator Nexus Kubernetes nodes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-connect |
| Install Microsoft Defender for Containers on Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-install-microsoft-defender |
| Configure SSH key access to Nexus Kubernetes nodes | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-manage-ssh-key |
| Set up Method D v2.0 secure break-glass access for Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-set-up-break-glass-access |
| Configure in-band management break-glass access for Nexus Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-set-up-break-glass-access-using-in-band-management |
| Enable Defender for Cloud security for Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-set-up-defender-for-cloud-security |
| Update ExpressRoute authorization keys in Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-update-expressroute-authorization-key |
| Secure Nexus resources using Azure Policy | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-azure-policy |
| Use Method D v2.0 break-glass access with Nexus built-in roles | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-break-glass-access |
| Configure MDE runtime protection on Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-mde-runtime-protection |
| Configure secret rotation v1 for Nexus fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-password-rotation-v1 |
| Use VM Console Service for secure Nexus VM access | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-use-vm-console-service |
| Enroll Nexus VMs in Azure Arc using managed identities | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-virtual-machines-arc-enroll-with-managed-identities |
| Create Nexus VMs with managed identities and authenticate | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-virtual-machines-authenticate-with-managed-identities |
| Use Key Vault secret references for Nexus cluster passwords | https://learn.microsoft.com/en-us/azure/operator-nexus/reference-key-vault-credential |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Nexus network devices with read-only commands | https://learn.microsoft.com/en-us/azure/operator-nexus/concepts-network-fabric-read-only-commands |
| Validate Nexus Network Fabric cabling with diagnostic APIs | https://learn.microsoft.com/en-us/azure/operator-nexus/how-to-validate-cables |
| Use nexusctl for emergency bare metal recovery actions | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-nexusctl |
| Collect diagnostic data from Nexus bare metal machines | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-run-data-extract |
| Troubleshoot Nexus bare metal with run-read diagnostics | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-baremetal-run-read |
| Gather trace IDs for Nexus PersistentVolumeClaim failures | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-gather-pvc-trace-id |
| Collect diagnostic data for Nexus VM Console issues | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-gather-vm-console-data |
| Run Nexus Kubernetes log collector for support | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-kubernetes-cluster-log-collector-script |
| Run read-only diagnostics on Nexus storage appliances | https://learn.microsoft.com/en-us/azure/operator-nexus/howto-storage-run-read |
| Troubleshoot accepted cluster hydration issues in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-accepted-cluster-hydration |
| Fix degraded status on Nexus bare metal machines | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-bare-metal-machine-degraded |
| Troubleshoot bare-metal machine provisioning in Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-bare-metal-machine-provisioning |
| Resolve warning status messages on Nexus bare metal machines | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-bare-metal-machine-warning |
| Diagnose Operator Nexus cluster heartbeat disconnection | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-cluster-heartbeat-connection-status-disconnected |
| Restore Operator Nexus control plane quorum after node loss | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-control-plane-quorum |
| Fix CSN storage pod containers stuck in creating state | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-csn-storage-pod-container-stuck-in-creating |
| Troubleshoot DNS issues in Nexus Network Fabric | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-dns-issues |
| Fix failed volume attachments in Operator Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-failed-volume-attachments |
| Resolve hardware validation failures for Nexus servers | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-hardware-validation-failure |
| Troubleshoot CSN-connected internet host access in AKS hybrid | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-internet-host-virtual-machine |
| Troubleshoot Operator Nexus isolation domain provisioning failures | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-isolation-domain |
| Diagnose dual-stack Nexus Kubernetes cluster issues | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-kubernetes-cluster-dual-stack-configuration |
| Resolve Ready, SchedulingDisabled nodes after runtime upgrade | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-kubernetes-cluster-node-cordoned |
| Recover stuck workloads after Nexus node power failure | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-kubernetes-cluster-stuck-workloads-due-to-power-failure |
| Diagnose LACP bonding issues on Operator Nexus hosts | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-lacp-bonding |
| Fix Operator Nexus log disruption after 48-hour disconnect | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-logs-disrupted-post-prolonged-disconnection |
| Troubleshoot Kubernetes container memory limits on Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-memory-limits |
| Resolve common issues with multiple Operator Nexus storage appliances | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-multiple-storage-appliances |
| Fix Neighbor Group AuthorizationFailed deployment errors | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-neighbor-group-creation-error |
| Fix unhealthy NFS pods in Operator Nexus clusters | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-network-file-system-unhealthy |
| Troubleshoot Nexus Kubernetes pods stuck in ContainerCreating | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-nexus-kubernetes-cluster-pods |
| Fix NotReady nodes in Operator Nexus KubernetesCluster | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-not-ready-kubernetes-cluster-node |
| Troubleshoot packet loss between NAKS worker nodes | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-packet-loss |
| Troubleshoot Nexus bare metal servers with restart, reimage, replace | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-reboot-reimage-replace |
| Interpret and act on Operator Nexus resource health alerts | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-resource-health-alerts |
| Troubleshoot storage control plane connectivity in Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-storage-control-plane-disconnected |
| Resolve TWAMP over UDP failures with NAT in Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-twamp-udp-not-working |
| Resolve unhealthy CSI storage pods in Operator Nexus | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-unhealthy-container-storage-interface |
| Troubleshoot unhealthy or degraded Operator Nexus storage appliances | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-unhealthy-degraded-storage-appliance |
| Troubleshoot Arc enrollment for Nexus VMs with managed identity | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-virtual-machines-arc-enroll-with-managed-identities |
| Resolve VM errors after restarting Operator Nexus bare-metal machines | https://learn.microsoft.com/en-us/azure/operator-nexus/troubleshoot-vm-error-after-reboot |

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
