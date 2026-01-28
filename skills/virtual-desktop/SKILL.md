---
name: virtual-desktop
description: Expert knowledge for Virtual Desktop development including configuration, architecture & design patterns, integrations & coding patterns, troubleshooting, deployment, best practices, security, limits & quotas, and comparing x vs. y. Use when building, debugging, or optimizing Virtual Desktop applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Virtual Desktop Skill

This skill provides expert guidance for Virtual Desktop development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use App Attach containers for AVD applications | https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-overview |
| Use ephemeral OS disks for stateless Azure Virtual Desktop hosts | https://learn.microsoft.com/en-us/azure/virtual-desktop/deploy/session-hosts/ephemeral-os-disks |
| Choose host pool management approach in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/host-pool-management-approaches |
| Decide preferred app group type for pooled AVD pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/preferred-application-group-type |
| Implement cost-optimized scaling for Azure Virtual Desktop with Automation and Logic Apps | https://learn.microsoft.com/en-us/azure/virtual-desktop/scaling-automation-logic-apps |

### Best Practices
| Topic | URL |
|-------|-----|
| Follow autoscale FAQ guidance and best practices for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/autoscale-faq |
| Apply autoscale scenarios and patterns for Azure Virtual Desktop host pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/autoscale-scenarios |
| Apply Azure Advisor recommendations for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/azure-advisor-recommendations |
| Analyze and optimize Azure Virtual Desktop connection latency | https://learn.microsoft.com/en-us/azure/virtual-desktop/connection-latency |
| Review Azure Virtual Desktop FAQ and best practices | https://learn.microsoft.com/en-us/azure/virtual-desktop/faq |
| Manage AVD user profiles with FSLogix containers | https://learn.microsoft.com/en-us/azure/virtual-desktop/fslogix-profile-containers |
| Manage Azure Virtual Desktop session hosts with Intune and Configuration Manager | https://learn.microsoft.com/en-us/azure/virtual-desktop/management |
| Use proxy servers with Azure Virtual Desktop reliably | https://learn.microsoft.com/en-us/azure/virtual-desktop/proxy-server-support |
| Use RDP Multipath to improve Azure Virtual Desktop connectivity | https://learn.microsoft.com/en-us/azure/virtual-desktop/rdp-multipath |
| Understand RDP Shortpath transport for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/rdp-shortpath |
| Best practices and FAQs for Start VM on Connect in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/start-virtual-machine-connect-faq |
| Apply Windows multi-session best practices on AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/windows-multisession-faq |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose Azure storage for FSLogix AVD profiles | https://learn.microsoft.com/en-us/azure/virtual-desktop/store-fslogix-profile |

### Configuration
| Topic | URL |
|-------|-----|
| Add session host VMs to an Azure Virtual Desktop host pool | https://learn.microsoft.com/en-us/azure/virtual-desktop/add-session-hosts-host-pool |
| Configure Azure Virtual Desktop administrative template in Group Policy and Intune | https://learn.microsoft.com/en-us/azure/virtual-desktop/administrative-template |
| Add and manage App Attach apps in AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-setup |
| Create and configure autoscale scaling plans for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/autoscale-create-assign-scaling-plan |
| Configure diagnostics and logging for Azure Virtual Desktop autoscale | https://learn.microsoft.com/en-us/azure/virtual-desktop/autoscale-diagnostics |
| Validate Azure Virtual Desktop FQDN and endpoint access with Agent URL Tool | https://learn.microsoft.com/en-us/azure/virtual-desktop/check-access-validate-required-fqdn-endpoint |
| Control clipboard direction and data types in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/clipboard-transfer-direction-data-types |
| Configure Configuration Manager collections to update Azure Virtual Desktop session hosts | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-automatic-updates |
| Configure RDP Shortpath for Azure Virtual Desktop sessions | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-rdp-shortpath |
| Configure session lock behavior in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-session-lock-behavior |
| Create and use custom image templates for AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/create-custom-image-templates |
| Understand custom image templates for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/custom-image-templates |
| Configure custom RDP properties for AVD host pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/customize-rdp-properties |
| Increase RDP chroma value to 4:4:4 in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/graphics-chroma-value-increase-4-4-4 |
| Enable GPU-accelerated rendering and encoding in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/graphics-enable-gpu-acceleration |
| Enable and configure Azure Virtual Desktop Insights monitoring | https://learn.microsoft.com/en-us/azure/virtual-desktop/insights |
| Install Microsoft 365 Apps on Azure Virtual Desktop images | https://learn.microsoft.com/en-us/azure/virtual-desktop/install-office-on-wvd-master-image |
| Install Windows 10 language packs on AVD multi-session VMs | https://learn.microsoft.com/en-us/azure/virtual-desktop/language-packs |
| Configure multimedia redirection for video and calls in AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/multimedia-redirection-video-playback-calls |
| Launch OneDrive automatically with AVD RemoteApp | https://learn.microsoft.com/en-us/azure/virtual-desktop/onedrive-remoteapp |
| Set up Private Link endpoints for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/private-link-setup |
| Reference for supported RDP properties in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/rdp-properties |
| Configure QoS policies for Azure Virtual Desktop RDP | https://learn.microsoft.com/en-us/azure/virtual-desktop/rdp-quality-of-service-qos |
| Configure audio and video redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-audio-video |
| Configure camera and video capture redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-camera-webcam-video-capture |
| Configure RDP clipboard redirection for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-clipboard |
| Configure drive and storage redirection over RDP for AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-drives-storage |
| Configure location redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-location |
| Configure MTP/PTP device redirection over RDP | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-plug-play-mtp-ptp |
| Configure printer redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-printers |
| Configure serial and COM port redirection over RDP | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-serial-com-ports |
| Configure smart card redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-smart-cards |
| Configure USB redirection on Windows over RDP for AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-usb |
| Configure WebAuthn redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-configure-webauthn |
| Configure peripheral and resource redirection over RDP for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/redirection-remote-desktop-protocol |
| Use and configure features of the Remote Desktop client for Windows | https://learn.microsoft.com/en-us/azure/virtual-desktop/remote-desktop-client/client-features-windows-msrdc |
| Configure Remote Desktop client for Windows to connect to Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/remote-desktop-client/connect-windows-cloud-services |
| Enable and configure RemoteApp enhancements preview | https://learn.microsoft.com/en-us/azure/virtual-desktop/remoteapp-enhancements |
| Allow required FQDNs and endpoints for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/required-fqdn-endpoint |
| Configure session host update for Azure Virtual Desktop host pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/session-host-update-configure |
| Configure preferred application group type on AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/set-preferred-application-group-type |
| Prepare and upload a custom VHD image for AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-customize-master-image |
| Create a golden image for Azure Virtual Desktop hosts | https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-golden-image |
| Configure Azure Virtual Desktop autoscaling with Automation and Logic Apps | https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-scaling-script |
| Configure Start VM on Connect for Azure Virtual Desktop host pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/start-virtual-machine-connect |
| Configure Microsoft Teams with media optimization on AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/teams-on-avd |
| Use URI schemes with the Azure Virtual Desktop Remote Desktop client | https://learn.microsoft.com/en-us/azure/virtual-desktop/uri-scheme |
| Configure Windows 11 language packs on Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/windows-11-language-packs |

### Deployment
| Topic | URL |
|-------|-----|
| Automatically migrate from AVD classic to current AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/automatic-migration |
| Deploy Azure Virtual Desktop across Azure, Local, and Extended Zones | https://learn.microsoft.com/en-us/azure/virtual-desktop/deploy-azure-virtual-desktop |
| Manually migrate from AVD classic to current AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/manual-migration |
| Recreate Azure Virtual Desktop resources when moving between regions | https://learn.microsoft.com/en-us/azure/virtual-desktop/move-resources |
| Use regional host pools in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/regional-host-pools |
| Deploy Remote Desktop Windows client per-user via Intune or Configuration Manager | https://learn.microsoft.com/en-us/azure/virtual-desktop/remote-desktop-client/install-windows-client-per-user |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use partner solutions with App Attach on AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-partner-solutions |
| Use Azure CLI and PowerShell modules to manage Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/cli-powershell |
| Use MSIXMGR tool parameters for App Attach | https://learn.microsoft.com/en-us/azure/virtual-desktop/msixmgr-tool-syntax-description |
| Integrate WebRTC calling apps with AVD multimedia redirection | https://learn.microsoft.com/en-us/azure/virtual-desktop/multimedia-redirection-developer-integration |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Estimate Azure Virtual Desktop Insights monitoring and log costs | https://learn.microsoft.com/en-us/azure/virtual-desktop/insights-costs |
| Check supported Teams features on Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/teams-supported-features |

### Security
| Topic | URL |
|-------|-----|
| Deploy and access Entra-joined session hosts in AVD | https://learn.microsoft.com/en-us/azure/virtual-desktop/azure-ad-joined-session-hosts |
| Configure AD FS single sign-on for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-adfs-sso |
| Configure managed identities for Azure Virtual Desktop host pools | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-managed-identity |
| Configure Entra ID single sign-on for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/configure-single-sign-on |
| Implement delegated access and role assignments in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/delegated-access-virtual-desktop |
| Set up Kerberos KDC proxy for Azure Virtual Desktop smartcard sign-in | https://learn.microsoft.com/en-us/azure/virtual-desktop/key-distribution-center-proxy |
| Secure Azure Virtual Desktop with Private Link | https://learn.microsoft.com/en-us/azure/virtual-desktop/private-link-overview |
| Provide Azure Virtual Desktop host pool access to external identities | https://learn.microsoft.com/en-us/azure/virtual-desktop/provide-access-external-identities |
| Onboard Azure Virtual Desktop hosts to Microsoft Purview forensic evidence | https://learn.microsoft.com/en-us/azure/virtual-desktop/purview-forensic-evidence |
| Use built-in Azure RBAC roles for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/rbac |
| Enable screen capture protection for Azure Virtual Desktop sessions | https://learn.microsoft.com/en-us/azure/virtual-desktop/screen-capture-protection |
| Apply security recommendations for Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/security-recommendations |
| Assign RBAC and Entra roles to Azure Virtual Desktop service principals | https://learn.microsoft.com/en-us/azure/virtual-desktop/service-principal-assign-roles |
| Enforce multifactor authentication for Azure Virtual Desktop with Conditional Access | https://learn.microsoft.com/en-us/azure/virtual-desktop/set-up-mfa |
| Configure watermarking protection in Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/watermarking |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Test and troubleshoot MSIX packages for App Attach | https://learn.microsoft.com/en-us/azure/virtual-desktop/app-attach-test-msix-packages |
| Monitor and troubleshoot Azure Virtual Desktop autoscale with Insights | https://learn.microsoft.com/en-us/azure/virtual-desktop/autoscale-monitor-operations-insights |
| Collect and query Azure Virtual Desktop connection quality data | https://learn.microsoft.com/en-us/azure/virtual-desktop/connection-quality-monitoring |
| Use Log Analytics with Azure Virtual Desktop diagnostics | https://learn.microsoft.com/en-us/azure/virtual-desktop/diagnostics-log-analytics |
| Diagnose Azure Virtual Desktop graphics performance with RemoteFX counters | https://learn.microsoft.com/en-us/azure/virtual-desktop/remotefx-graphics-performance-counters |
| Interpret and fix Azure Virtual Desktop session host health statuses | https://learn.microsoft.com/en-us/azure/virtual-desktop/session-host-status-health-checks |
| Interpret and fix Azure Virtual Desktop session host health statuses | https://learn.microsoft.com/en-us/azure/virtual-desktop/session-host-status-health-checks |
| Use Log Analytics queries to diagnose Azure Virtual Desktop session host updates | https://learn.microsoft.com/en-us/azure/virtual-desktop/session-host-update-diagnostics |
| Troubleshoot Microsoft Teams issues on Azure Virtual Desktop | https://learn.microsoft.com/en-us/azure/virtual-desktop/troubleshoot-teams |

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
