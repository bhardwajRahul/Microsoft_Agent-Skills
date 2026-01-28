---
name: hpc-cache
description: Expert knowledge for Hpc Cache development including security, configuration, architecture & design patterns, integrations & coding patterns, troubleshooting, best practices, limits & quotas, and deployment. Use when building, debugging, or optimizing Hpc Cache applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Hpc Cache Skill

This skill provides expert guidance for Hpc Cache development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Choose Azure HPC Cache usage models and policies | https://learn.microsoft.com/en-us/azure/hpc-cache/cache-usage-models |
| Design DNS-based client load balancing for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/client-load-balancing |
| Design and plan Azure HPC Cache aggregated namespace | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-namespace |
| Design regional redundancy and failover for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-region-recovery |
| Decide when Azure HPC Cache fits your workload | https://learn.microsoft.com/en-us/azure/hpc-cache/usage-scenarios |

### Best Practices
| Topic | URL |
|-------|-----|
| Optimize data movement to Blob for HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest |
| Apply NFS Blob storage considerations with Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/nfs-blob-considerations |
| Prime and pre-load Azure HPC Cache for better performance | https://learn.microsoft.com/en-us/azure/hpc-cache/prime-cache |

### Configuration
| Topic | URL |
|-------|-----|
| Configure client-facing namespace paths in HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/add-namespace-paths |
| Prepare Azure CLI environment for managing Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/az-cli-prerequisites |
| Configure networking, NTP, DNS, and snapshots for HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/configuration |
| Configure directory services and extended groups for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/directory-services |
| Configure Azure HPC Cache storage targets | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-add-storage |
| Update Azure HPC Cache storage target settings | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-edit-storage |
| Operate and update Azure HPC Cache instances | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-manage |
| Mount Azure HPC Cache on NFS clients | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-mount |
| Manage lifecycle and capacity of HPC Cache storage targets | https://learn.microsoft.com/en-us/azure/hpc-cache/manage-storage-targets |

### Deployment
| Topic | URL |
|-------|-----|
| Recreate and move Azure HPC Cache workloads across regions | https://learn.microsoft.com/en-us/azure/hpc-cache/move-resource |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use the flush_file Python utility for Azure HPC Cache write-back | https://learn.microsoft.com/en-us/azure/hpc-cache/custom-flush-script |
| Manually copy data to Blob for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-manual |
| Ingest data to HPC Cache using msrsync | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-msrsync |
| Use parallelcp script to ingest data into HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-parallelcp |
| Integrate Azure HPC Cache with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-netapp |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Request Azure HPC Cache quota increases in Azure | https://learn.microsoft.com/en-us/azure/hpc-cache/increase-quota |

### Security
| Topic | URL |
|-------|-----|
| Define and apply client access policies in HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/access-policies |
| Configure customer-managed encryption keys for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/customer-keys |
| Understand security configuration for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-security-info |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Work around Azure Blob firewall issues for HPC Cache targets | https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-blob-firewall-fix |
| Troubleshoot NFS storage target creation for Azure HPC Cache | https://learn.microsoft.com/en-us/azure/hpc-cache/troubleshoot-nas |

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
