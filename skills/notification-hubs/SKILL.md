---
name: notification-hubs
description: Expert knowledge for Notification Hubs development including integrations & coding patterns, deployment, configuration, security, architecture & design patterns, troubleshooting, and limits & quotas. Use when building, debugging, or optimizing Notification Hubs applications.
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
| Enterprise push notification architecture with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-enterprise-push-notification-architecture |

### Configuration
| Topic | URL |
|-------|-----|
| Configure APNS credentials in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-apple-push-notification-service |
| Configure Baidu Cloud Push for Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-baidu-cloud-push |
| Configure FCM settings for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-google-firebase-cloud-messaging |
| Configure MPNS settings in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-microsoft-push-notification-service |
| Configure PNS credentials in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-notification-hub-portal-pns-settings |
| Configure WNS for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/configure-windows-push-notification-service |
| Define Notification Hubs resources using Bicep | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-bicep |
| Configure Notification Hubs with ARM templates | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-template |
| Bulk export and import Notification Hubs registrations | https://learn.microsoft.com/en-us/azure/notification-hubs/export-modify-registrations-bulk |
| Reference for Azure Notification Hubs monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/notification-hubs/monitor-notification-hubs-reference |
| Manage Notification Hubs using Azure PowerShell | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-deploy-and-manage-powershell |
| Configure Azure Notification Hubs diagnostic and resource logs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-diagnostic-logs |
| Configure APNS token-based HTTP/2 auth in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-http2-token-authentication |
| Configure device registration patterns in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-registration-management |
| Configure routing and tag expressions in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-tags-segment-push-message |
| Use Notification Hubs templates for cross-platform payloads | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-templates-cross-platform-push-messages |
| Update Notification Hubs iOS settings for iOS 13 | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notification-updates-ios-13 |

### Deployment
| Topic | URL |
|-------|-----|
| Change Azure Notification Hubs pricing tier safely | https://learn.microsoft.com/en-us/azure/notification-hubs/change-pricing-tier |
| Provision Notification Hubs using Terraform | https://learn.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-terraform |
| Move Azure Notification Hubs between regions | https://learn.microsoft.com/en-us/azure/notification-hubs/move-registrations |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Notification Hubs with Android FCM v1 SDK | https://learn.microsoft.com/en-us/azure/notification-hubs/android-sdk |
| Implement browser web push with Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/browser-push |
| Use REST and portal to configure FCM v1 in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-rest |
| Migrate to FCM v1 using Azure Notification Hubs SDKs | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-sdk |
| Update Notification Hubs with FCM v1 credentials via SDK | https://learn.microsoft.com/en-us/azure/notification-hubs/firebase-migration-update-sdk |
| Use Notification Hubs iOS SDK 3.0.0-preview1 | https://learn.microsoft.com/en-us/azure/notification-hubs/ios-sdk-current |
| Configure APNS and Notification Hubs for iOS apps | https://learn.microsoft.com/en-us/azure/notification-hubs/ios-sdk-get-started |
| Integrate Notification Hubs with Android FCM SDK 0.6 | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-android-push-notification-google-fcm-get-started |
| Send user-specific iOS notifications via ASP.NET backend | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-ios-apple-apns-notification |
| Send rich iOS push notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-ios-apple-push-notification-service-apns-rich |
| Target user-specific notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-windows-dotnet-wns-notification |
| Send secure Windows push notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-backend-windows-dotnet-wns-secure-push-notification |
| Send cross-platform user notifications with templates | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-aspnet-cross-platform-notification |
| Integrate Azure Notification Hubs with Baidu Push | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-baidu-china-android-notifications-get-started |
| Migrate Notification Hubs from FCM legacy to FCM v1 | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-gcm-to-fcm |
| Register iOS users via ASP.NET Web API for push | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-aspnet-register-user-from-backend-to-push-notification |
| Implement localized iOS push templates with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-xplat-localized-apns-push-notification |
| Target specific iOS devices with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-ios-xplat-segmented-apns-push-notification |
| Use the Java SDK with Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-java-push-notification-tutorial |
| Send push notifications from Node.js using Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-nodejs-push-notification-tutorial |
| Send push notifications from PHP with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-php-push-notification-tutorial |
| Send geofenced push notifications with Bing Spatial Data | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-bing-spatial-data-geofencing-notification |
| Use Python to send notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-python-push-notification-tutorial |
| Target specific UWP devices using Notification Hubs tags | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-notification-dotnet-push-xplat-segmented-wns |
| Send push notifications to UWP apps with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-store-dotnet-get-started-wns-push-notification |
| Send localized WNS notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-windows-store-dotnet-xplat-localized-wns-push-notification |
| Target specific Android devices with FCM tags | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notifications-android-specific-devices-firebase-cloud-messaging |
| Send user-targeted Android notifications with Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/push-notifications-android-specific-users-firebase-cloud-messaging |
| Send APNS VOIP notifications via Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/voip-apns |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Schedule notifications with Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-send-push-notifications-scheduled |

### Security
| Topic | URL |
|-------|-----|
| Data-at-rest encryption behavior in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/encrypt-at-rest |
| Understand EU data boundary behavior in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/eu-data-boundary |
| Security model and access control in Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-security |
| TLS version requirements for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-tls12 |
| Configure Azure Notification Hubs with Private Link | https://learn.microsoft.com/en-us/azure/notification-hubs/private-link |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshooting and design FAQs for Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-faq |
| Troubleshoot dropped notifications in Azure Notification Hubs | https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-fixer |

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
