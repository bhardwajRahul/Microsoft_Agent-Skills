---
name: azure-health-insights
description: Expert knowledge for Azure Health Insights development including configuration, integrations & coding patterns, security, and best practices. Use when building, debugging, or optimizing Azure Health Insights applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Health Insights Skill

This skill provides expert guidance for Azure Health Insights development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Best Practices
| Topic | URL |
|-------|-----|
| Apply responsible integration practices for Trial Matcher | https://learn.microsoft.com/en-us/azure/azure-health-insights/trial-matcher/integration-and-responsible-use |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure AI Health Insights Docker containers | https://learn.microsoft.com/en-us/azure/azure-health-insights/configure-containers |
| Use communication inference fields in Radiology Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/communication-inference |
| Use guidance inferences tied to findings in Radiology Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/guidance-inference |
| Configure Radiology Insights model parameters | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/model-configuration |
| Interpret quality measure inferences and MIPS results | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/quality-measure-inference |
| Work with radiology procedure inference in Radiology Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/radiology-procedure-inference |
| Interpret follow-up recommendation inference fields in Radiology Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/recommendation-inference |
| Handle scoring and assessment inferences in Radiology Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/scoring-and-assessment-inference |
| Interpret Trial Matcher inference results and evidence flags | https://learn.microsoft.com/en-us/azure/azure-health-insights/trial-matcher/inferences |
| Configure Trial Matcher filters and knowledge graph usage | https://learn.microsoft.com/en-us/azure/azure-health-insights/trial-matcher/model-configuration |
| Provide patient information formats to Trial Matcher | https://learn.microsoft.com/en-us/azure/azure-health-insights/trial-matcher/patient-info |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Retrieve supporting evidence for Radiology Insights inferences via API | https://learn.microsoft.com/en-us/azure/azure-health-insights/radiology-insights/tutorial |
| Call and use Trial Matcher through its API | https://learn.microsoft.com/en-us/azure/azure-health-insights/trial-matcher/get-started |

### Security
| Topic | URL |
|-------|-----|
| Understand data handling and security for Azure AI Health Insights | https://learn.microsoft.com/en-us/azure/azure-health-insights/responsible-ai/data-privacy-security |

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
