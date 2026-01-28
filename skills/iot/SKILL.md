---
name: iot
description: Expert knowledge for Iot development including integrations & coding patterns, best practices, architecture & design patterns, comparing x vs. y, security, and troubleshooting. Use when building, debugging, or optimizing Iot applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Iot Skill

This skill provides expert guidance for Iot development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use IoT Plug and Play models in solutions | https://learn.microsoft.com/en-us/azure/iot/concepts-model-discovery |
| Enable industrial dataspace architectures on Azure | https://learn.microsoft.com/en-us/azure/iot/howto-iot-industrial-dataspaces |
| Implement Azure industrial IoT reference architecture | https://learn.microsoft.com/en-us/azure/iot/tutorial-iot-industrial-solution-architecture |

### Best Practices
| Topic | URL |
|-------|-----|
| Design resilient Azure IoT device reconnection strategies | https://learn.microsoft.com/en-us/azure/iot/concepts-manage-device-reconnections |
| Model IoT Plug and Play devices with DTDL | https://learn.microsoft.com/en-us/azure/iot/concepts-modeling-guide |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose between Azure IoT C and Embedded C SDKs | https://learn.microsoft.com/en-us/azure/iot/concepts-using-c-sdk-and-embedded-c-sdk |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Apply IoT Plug and Play MQTT message conventions | https://learn.microsoft.com/en-us/azure/iot/concepts-convention |
| Implement IoT Plug and Play devices using SDKs | https://learn.microsoft.com/en-us/azure/iot/concepts-developer-guide-device |
| Build IoT Plug and Play service applications | https://learn.microsoft.com/en-us/azure/iot/concepts-developer-guide-service |
| Format IoT Plug and Play device message payloads | https://learn.microsoft.com/en-us/azure/iot/concepts-message-payloads |
| Integrate on-premises SAP ERP with Azure IoT | https://learn.microsoft.com/en-us/azure/iot/howto-connect-on-premises-sap-to-azure |
| Connect devices to Azure IoT DPS using MQTT | https://learn.microsoft.com/en-us/azure/iot/iot-mqtt-connect-to-iot-dps |
| Connect devices to Azure IoT Hub using MQTT | https://learn.microsoft.com/en-us/azure/iot/iot-mqtt-connect-to-iot-hub |

### Security
| Topic | URL |
|-------|-----|
| Use Azure IoT explorer to test IoT devices securely | https://learn.microsoft.com/en-us/azure/iot/howto-use-iot-explorer |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure IoT embedded device tutorials | https://learn.microsoft.com/en-us/azure/iot/troubleshoot-embedded-device-tutorials |

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
