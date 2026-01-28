---
name: confidential-computing
description: Expert knowledge for Confidential Computing development including security, comparing x vs. y, architecture & design patterns, integrations & coding patterns, deployment, and configuration. Use when building, debugging, or optimizing Confidential Computing applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Confidential Computing Skill

This skill provides expert guidance for Confidential Computing development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Select Azure confidential computing deployment models | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-computing-deployment-models |
| Understand Azure confidential container options and scenarios | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-containers |
| Understand Azure confidential container options and scenarios | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-containers |
| Use Intel SGX enclave nodes in AKS for confidential apps | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-nodes-aks-overview |
| Design and run enclave-aware containers on AKS | https://learn.microsoft.com/en-us/azure/confidential-computing/enclave-aware-containers |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose the right Azure confidential container offering | https://learn.microsoft.com/en-us/azure/confidential-computing/choose-confidential-containers-offerings |
| Evaluate Azure confidential GPU VM options | https://learn.microsoft.com/en-us/azure/confidential-computing/gpu-options |
| Compare Azure confidential VM options on AMD and Intel | https://learn.microsoft.com/en-us/azure/confidential-computing/virtual-machine-options |

### Configuration
| Topic | URL |
|-------|-----|
| Configure AKS Intel SGX plugin for confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-nodes-aks-addon |
| Configure Virtual Machine Metablob Disk for confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/virtual-machine-metablob-disk |

### Deployment
| Topic | URL |
|-------|-----|
| Run Confidential Containers (preview) on AKS | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-containers-on-aks-preview |
| Use confidential VM node pools with AKS on Azure | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-node-pool-aks |
| Create custom images for Azure confidential VMs with CLI | https://learn.microsoft.com/en-us/azure/confidential-computing/how-to-create-custom-image-confidential-vm |
| Deploy Fortanix Confidential Computing Manager on Azure | https://learn.microsoft.com/en-us/azure/confidential-computing/how-to-fortanix-confidential-computing-manager |
| Migrate nested Azure confidential VMs across regions | https://learn.microsoft.com/en-us/azure/confidential-computing/migrate-nested-confidential-vms |
| Deploy Azure confidential VMs using ARM templates | https://learn.microsoft.com/en-us/azure/confidential-computing/quick-create-confidential-vm-arm |
| Deploy and size Intel SGX confidential VMs on Azure | https://learn.microsoft.com/en-us/azure/confidential-computing/virtual-machine-solutions-sgx |
| Deploy VM scale sets with hardened Linux images | https://learn.microsoft.com/en-us/azure/confidential-computing/vmss-deployment-from-hardened-linux-image |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Run unmodified containers in Intel SGX enclaves on Azure | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-containers-enclaves |
| Build Intel SGX enclave apps with OSS tools on Azure | https://learn.microsoft.com/en-us/azure/confidential-computing/enclave-development-oss |
| Use guest attestation sample apps for confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/guest-attestation-example |
| Run Azure apps with Fortanix CCM and Node Agent | https://learn.microsoft.com/en-us/azure/confidential-computing/how-to-fortanix-confidential-computing-manager-node-agent |
| Implement Secure Key Release for confidential containers in ACI | https://learn.microsoft.com/en-us/azure/confidential-computing/skr-flow-confidential-containers-azure-container-instance |
| Implement Secure Key Release to confidential VMs with AMD SEV-SNP | https://learn.microsoft.com/en-us/azure/confidential-computing/skr-flow-confidential-vm-sev-snp |

### Security
| Topic | URL |
|-------|-----|
| Configure and apply attestation for Azure confidential computing | https://learn.microsoft.com/en-us/azure/confidential-computing/attestation-solutions |
| Apply security policy for AKS Confidential Containers | https://learn.microsoft.com/en-us/azure/confidential-computing/confidential-containers-aks-security-policy |
| Understand Azure confidential VM guest attestation design | https://learn.microsoft.com/en-us/azure/confidential-computing/guest-attestation-confidential-virtual-machines-design |
| Use guest attestation to verify Azure confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/guest-attestation-confidential-vms |
| Secure confidential VMs with Defender for Cloud guest attestation | https://learn.microsoft.com/en-us/azure/confidential-computing/guest-attestation-defender-for-cloud |
| Harden Linux images by removing Azure guest agent | https://learn.microsoft.com/en-us/azure/confidential-computing/harden-a-linux-image-to-remove-azure-guest-agent |
| Harden Linux images by removing sudo users for confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/harden-the-linux-image-to-remove-sudo-users |
| Leverage virtual TPM features in Azure confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/how-to-leverage-virtual-tpms-in-azure-confidential-vms |
| Rotate customer-managed keys for Azure confidential VMs | https://learn.microsoft.com/en-us/azure/confidential-computing/key-rotation-offline |
| Manage secrets and keys in Azure confidential workloads | https://learn.microsoft.com/en-us/azure/confidential-computing/secret-key-management |
| Author Secure Key Release policies for Azure confidential TEEs | https://learn.microsoft.com/en-us/azure/confidential-computing/skr-policy-examples |
| Use virtual TPMs in Azure confidential VMs securely | https://learn.microsoft.com/en-us/azure/confidential-computing/virtual-tpms-in-azure-confidential-vm |

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
