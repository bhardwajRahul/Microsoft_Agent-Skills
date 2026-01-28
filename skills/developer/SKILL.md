---
name: developer
description: Expert knowledge for Developer development including deployment, integrations & coding patterns, and configuration. Use when building, debugging, or optimizing Developer applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Developer Skill

This skill provides expert guidance for Developer development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Configuration
| Topic | URL |
|-------|-----|
| Reference for Jenkins plug-ins integrating with Azure services | https://learn.microsoft.com/en-us/azure/developer/jenkins/plug-ins-for-azure |

### Deployment
| Topic | URL |
|-------|-----|
| Run Jenkins build agents on Azure Container Instances | https://learn.microsoft.com/en-us/azure/developer/jenkins/azure-container-instances-as-jenkins-build-agent |
| Install and configure Jenkins on Azure Linux VM | https://learn.microsoft.com/en-us/azure/developer/jenkins/configure-on-linux-vm |
| CI/CD from GitHub to AKS using Jenkins | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-from-github-to-aks |
| Deploy Java web apps to Azure App Service via Jenkins | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-to-azure-app-service-using-azure-cli |
| Deploy Java Azure Functions using Jenkins | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-to-azure-functions |
| Deploy Spring microservices to Azure Spring Apps with Jenkins | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-to-azure-spring-apps-using-azure-cli |
| Deploy to Azure Linux VMs using Jenkins and Azure DevOps | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-to-linux-vm-using-azure-devops-services |
| Deploy Service Fabric Linux apps using Jenkins | https://learn.microsoft.com/en-us/azure/developer/jenkins/deploy-to-service-fabric-cluster |
| Create Jenkins CI/CD pipeline with GitHub and Docker on Azure | https://learn.microsoft.com/en-us/azure/developer/jenkins/pipeline-with-github-and-docker |
| Scale Jenkins workloads with Azure VM agents | https://learn.microsoft.com/en-us/azure/developer/jenkins/scale-deployments-using-vm-agents |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Blob Storage as Jenkins build artifact repository | https://learn.microsoft.com/en-us/azure/developer/jenkins/azure-storage-blobs-as-build-artifact-repository |

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
