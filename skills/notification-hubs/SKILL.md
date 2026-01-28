---
name: notification-hubs
description: Expert knowledge for Notification Hubs development including integrations & coding patterns, configuration, deployment, security, architecture & design patterns, troubleshooting, limits & quotas, and best practices. Use when building, debugging, or optimizing Notification Hubs applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Notification Hubs Skill

This skill provides expert guidance for Notification Hubs development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design enterprise push architectures with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-enterprise-push-notification-architecture |

### Best Practices
| Topic | URL |
|-------|-----|
| Handle iOS 13 push changes in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notification-updates-ios-13 |

### Configuration
| Topic | URL |
|-------|-----|
| Change Notification Hubs namespace pricing tier | https://learn.microsoft.com/en-us/azure/notification-hubs/change-pricing-tier |
| Configure APNS settings in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-apple-push-notification-service |
| Configure Baidu Cloud Push in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-baidu-cloud-push |
| Configure FCM settings for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-google-firebase-cloud-messaging |
| Configure MPNS settings in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-microsoft-push-notification-service |
| Configure PNS settings for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-notification-hub-portal-pns-settings |
| Configure WNS settings in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-windows-push-notification-service |
| Bulk export and import Notification Hubs registrations | https://learn.microsoft.com/en-us/azure/notification-hubs/export-modify-registrations-bulk |
| Reference for Azure Notification Hubs monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/notification-hubs/monitor-notification-hubs-reference |
| Manage Notification Hubs with Azure PowerShell | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-deploy-and-manage-powershell |
| Configure Azure Notification Hubs diagnostic and resource logs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-diagnostic-logs |
| Configure device registration patterns in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-registration-management |
| Configure routing and tag expressions in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-tags-segment-push-message |
| Use Notification Hubs templates for cross-platform payloads | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-templates-cross-platform-push-messages |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Azure Notification Hubs using Bicep templates | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-bicep |
| Provision Azure Notification Hubs with ARM templates | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-template |
| Create Azure Notification Hubs using Terraform | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-terraform |
| Move Notification Hubs to a different Azure region | https://learn.microsoft.com/en-us/azure/notification-hubs/move-registrations |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Notification Hubs with Android using FCM v1 SDK | https://learn.microsoft.com/en-us/azure/notification-hubs/android-sdk |
| Send browser web push notifications via Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/browser-push |
| Use REST and portal to configure FCM v1 in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-rest |
| Migrate to FCM v1 using Azure Notification Hubs SDKs | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-sdk |
| Update Notification Hubs with FCM v1 credentials via .NET SDK | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-update-sdk |
| Use Notification Hubs iOS SDK 3.0.0-preview1 for push | https://learn.microsoft.com/en-us/azure/notification-hubs/ios-sdk-current |
| Configure APNS and Notification Hubs for iOS push | https://learn.microsoft.com/en-us/azure/notification-hubs/ios-sdk-get-started |
| Integrate Notification Hubs with Android using FCM SDK 0.6 | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-android-push-notification-google-fcm-get-started |
| Send user-specific iOS notifications with ASP.NET backend | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-ios-apple-apns-notification |
| Send rich iOS push notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-ios-apple-push-notification-service-apns-rich |
| Target user-specific WNS notifications via Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-windows-dotnet-wns-notification |
| Implement secure push for Windows with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-windows-dotnet-wns-secure-push-notification |
| Send cross-platform user notifications with templates | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-cross-platform-notification |
| Integrate Azure Notification Hubs with Baidu Push | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-baidu-china-android-notifications-get-started |
| Migrate Notification Hubs from GCM/FCM legacy to FCM v1 | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-gcm-to-fcm |
| Register iOS users via ASP.NET Web API for push | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-aspnet-register-user-from-backend-to-push-notification |
| Send localized iOS push notifications using Notification Hubs templates | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-xplat-localized-apns-push-notification |
| Send targeted iOS device notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-xplat-segmented-apns-push-notification |
| Use the Java SDK with Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-java-push-notification-tutorial |
| Send push notifications from Node.js using Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-nodejs-push-notification-tutorial |
| Send push notifications from PHP with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-php-push-notification-tutorial |
| Send geofenced push notifications with Bing Spatial Data | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-bing-spatial-data-geofencing-notification |
| Use APNS token-based HTTP/2 auth with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-http2-token-authentication |
| Send push notifications from Python using Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-python-push-notification-tutorial |
| Send segmented UWP notifications with Notification Hubs tags | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-notification-dotnet-push-xplat-segmented-wns |
| Push notifications to UWP apps with Notification Hubs and WNS | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-store-dotnet-get-started-wns-push-notification |
| Implement localized WNS notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-store-dotnet-xplat-localized-wns-push-notification |
| Target specific Android devices with Notification Hubs and FCM | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notifications-android-specific-devices-firebase-cloud-messaging |
| Send user-targeted Android notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notifications-android-specific-users-firebase-cloud-messaging |
| Send APNS VoIP notifications via Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/voip-apns |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Schedule future notifications in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-send-push-notifications-scheduled |

### Security
| Topic | URL |
|-------|-----|
| Review data-at-rest encryption in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/encrypt-at-rest |
| Understand EU data boundary behavior in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/eu-data-boundary |
| Apply the Notification Hubs security model | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-security |
| Plan for TLS version support in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-tls12 |
| Configure Azure Notification Hubs with Private Link | https://learn.microsoft.com/en-us/azure/notification-hubs/private-link |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot and design solutions with Notification Hubs FAQ | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-faq |
| Diagnose and fix dropped notifications in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-fixer |

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
