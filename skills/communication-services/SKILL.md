---
name: communication-services
description: Expert knowledge for Communication Services development including comparing x vs. y, security, limits & quotas, configuration, best practices, troubleshooting, deployment, integrations & coding patterns, and architecture & design patterns. Use when building, debugging, or optimizing Communication Services applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Communication Services Skill

This skill provides expert guidance for Communication Services development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design an event management platform with Teams, Graph, and ACS | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/events-playbook |
| Architect ACS with Azure ExpressRoute connectivity | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/integrate-express-route |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply best practices for Azure Communication Services calling SDKs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/best-practices |
| Apply best practices for Communication Services user access tokens | https://learn.microsoft.com/en-us/azure/communication-services/concepts/credentials-best-practices |
| Manage Azure email opt-outs for B2C delivery | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-optout-management |
| Improve Azure email sender reputation and delivery | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/sender-reputation-managed-suppression-list |
| Govern Teams meeting experience for ACS virtual visits | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/virtual-visits/govern-meeting-experience |
| Plan user experience for ACS–Teams virtual appointments | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/virtual-visits/plan-user-experience |
| Decide when to use Raw ID identifiers in Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/concepts/raw-id-use-cases |
| Avoid ACS phone numbers being flagged as spam | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/prevent-spam-flag |
| Handle Call Automation known issues and constraints | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/known-issues-call-automation |
| Manage and improve Azure Communication Services call quality | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/manage-call-quality |
| Optimize network for ACS voice and video quality | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/network-requirements |
| Apply ACS UX best practices for calling experiences | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/user-experience |
| Handle emergency calls with Teams Phone Extensibility | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensibility-emergency-call |
| Optimize ACS video layout and resolution on web | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/optimizing-video-placement |
| Implement a trusted auth backend for ACS | https://learn.microsoft.com/en-us/azure/communication-services/samples/trusted-auth-sample |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Understand pricing components for ACS Advanced Messaging | https://learn.microsoft.com/en-us/azure/communication-services/concepts/advanced-messaging/whatsapp/pricing |
| Compare PSTN connectivity options for Teams Phone extensibility | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/tpe/teams-phone-extensibility-connectivity-cost |
| Compare Twilio Video with ACS Calling SDK for migration | https://learn.microsoft.com/en-us/azure/communication-services/concepts/migrate-to-azure-communication-services |
| Understand pricing model for ACS Teams interop scenarios | https://learn.microsoft.com/en-us/azure/communication-services/concepts/pricing/teams-interop-pricing |
| Understand Azure SMS pricing model and options | https://learn.microsoft.com/en-us/azure/communication-services/concepts/sms-pricing |
| Migrate implementations from Twilio Video to ACS Calling | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/migrating-to-azure-communication-services-calling |
| Migrate Twilio Conversations Chat to ACS Chat SDK | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/migrating-to-azure-communication-services-chat |

### Configuration
| Topic | URL |
|-------|-----|
| Enable Azure Monitor logging for ACS resources | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/enable-logging |
| Use ACS chat insights workbooks in Azure Monitor | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/insights/chat-insights |
| Use Azure Workbooks for email insights dashboards | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/insights/email-insights |
| Use Voice and Video Insights workbooks for ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/insights/voice-and-video-insights |
| Interpret Azure Communication Services billing usage log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/billing-usage-log-schema |
| Configure and interpret Call Automation diagnostic logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-automation-logs |
| Use Call Automation metrics and dimensions in Azure Monitor | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-automation-metrics |
| Use ACS call client media statistics time series logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-client-media-statistics-log-schema |
| Use ACS call client operations log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-client-operations-log-schema |
| Understand ACS call diagnostics log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-diagnostics-log-schema |
| Understand ACS call diagnostics updates log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-diagnostics-updates-log-schema |
| Understand ACS call metrics log schema and usage | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-metrics-log-schema |
| Understand ACS call summary log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-summary-log-schema |
| Understand ACS call summary updates log schema | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/call-summary-updates-log-schema |
| Configure and interpret ACS chat logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/chat-logs |
| Use and understand Azure Communication Services Closed Captions logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/closed-captions-logs |
| Configure and use Azure email diagnostic logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/email-logs |
| Configure end of call survey logs for ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/end-of-call-survey-logs |
| Configure and analyze Call Recording summary logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/recording-logs |
| Configure and interpret Azure Communication Services Rooms logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/rooms-logs |
| Configure Job Router operational logs with Azure Monitor | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/router-logs |
| Configure Azure Monitor logging for ACS SMS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/sms-logs |
| Enable and configure ACS voice and video call logs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/logs/voice-and-video-logs |
| Query Azure Communication Services call logs with Log Analytics | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/query-call-logs |
| Query Azure Communication Services call logs with Log Analytics | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/query-call-logs |
| Configure monitoring and alerts for ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/set-up-call-monitoring |
| Use Azure Monitor metrics for ACS SMS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/sms-metrics |
| Configure inline attachments for Azure Email messages | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-attachment-inline |
| Prepare ACS email resources and domains for sending | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/prepare-email-communication-resource |
| Configure firewalls for custom Teams calling with ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/custom-teams-endpoint-firewall-configuration |
| Map Teams Phone capabilities to ACS Calling and Automation SDKs | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/tpe/teams-phone-extensibility-capabilities |
| Provision configuration for Teams Phone extensibility | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/tpe/teams-phone-extensibility-provisioning |
| Configure SIP parameters for Azure direct routing | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/direct-routing-sip-specification |
| Use ACS Data Channel for in-call messaging | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/data-channel |
| Access media quality statistics in Azure Communication Services calls | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/media-quality-sdk |
| Configure Real Time Text (RTT) in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/real-time-text |
| Configure and manage Job Router queues | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/manage-queue |
| Validate domains for Azure direct routing SBCs | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/telephony/domain-validation |
| Enable audio-only calling mode in ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/audio-only-mode |
| Disable end-call confirmation in ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/leave-call-confirmation |
| Configure localization for Azure Communication Services UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/localization |
| Configure screen orientation in ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/orientation |
| Enable picture-in-picture in ACS UI Library calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/picture-in-picture |
| Customize call title and subtitle in ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/setup-title-subtitle |
| Configure theming for ACS UI Library components | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/theming |
| Create and manage ACS Email Communication Service | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/create-email-communication-resource |
| Enable user engagement tracking for Azure email | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/enable-user-engagement-tracking |
| Configure ACS event subscriptions via portal and CLI | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/events/subscribe-to-events |
| Quickstart provisioning for Teams Phone extensibility with ACS | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensibility-quickstart |
| Configure video constraints in ACS calling apps | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-video-constraints |
| Get and use audio volume indicators in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-volume-indicator |
| Disable local preview mirroring in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/local-preview-mirroring |
| Migrate Android ACS push to Firebase FCM v1 | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/call-chat-migrate-android-push-fcm-v1 |
| Register ACS Android push notifications with FCM v1 | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/call-chat-register-android-push-fcm-v1 |
| Proxy ACS calling media and signaling via TURN | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/proxy-calling-support-tutorial |

### Deployment
| Topic | URL |
|-------|-----|
| Teams user capabilities in ACS-hosted calls | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/calling-capabilities |
| Teams user capabilities in ACS-hosted calls | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/calling-capabilities |
| Use Azure Communication Services with Teams in government clouds | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/government-cloud |
| Supported calling capabilities for Teams users in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/teams-user-calling |
| Use Teams users with ACS in government clouds | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/teams-user/government-cloud |
| Teams meeting capabilities for Teams users in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/teams-user/meeting-capabilities |
| Phone calling capabilities for Teams users in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/teams-user/phone-capabilities |
| Select certified SBCs for Azure direct routing | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/certified-session-border-controllers |
| Plan Azure direct routing infrastructure and connectivity | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/direct-routing-infrastructure |
| Determine Teams license requirements for ACS support | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/eligible-teams-licenses |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Communication Services pre-call diagnostics API | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/pre-call-diagnostics |
| Implement Call Automation call control actions via SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/actions-for-call-control |
| Use mid-call media actions with Call Automation | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/control-mid-call-media-actions |
| Pass custom contextual data in Call Automation calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/custom-context |
| Process Call Automation events with the event processor | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/handle-events-with-event-processor |
| Add Microsoft Teams users to calls with Call Automation | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/teams-interop-call-automation |
| Transfer active calls between ACS clients | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/active-call-transfer |
| Retrieve Teams meeting audio conferencing details via ACS | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/audio-conferencing |
| Integrate Teams breakout rooms with ACS | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/breakoutrooms |
| Check browser support using ACS Calling SDK getEnvironmentInfo | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/browser-support |
| Pass UUI headers with ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/call-context |
| Display call transcription state in ACS clients | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/call-transcription |
| Integrate iOS CallKit with ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/callkit-integration |
| Query local user capabilities in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/capabilities |
| Enable closed captions for ACS–Teams interop calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/closed-captions-teams-interop-how-to |
| Subscribe to Teams participant display name changes | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/display-name-changed |
| Render active speakers using ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/dominant-speaker |
| Subscribe to Azure Communication Services calling events | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/events |
| Detect multiple active tabs with ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/is-sdk-active-in-multiple-tabs |
| Control Teams meeting lobby via ACS SDKs | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/lobby |
| Programmatically manage calls with ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/manage-calls |
| Control video streams using ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/manage-video |
| Control participant media access in ACS-powered calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/media-access |
| View Teams PowerPoint Live via ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/powerpoint-live |
| Enable ACS calling push notifications with Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/push-notifications |
| Implement raise hand states in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/raise-hand |
| Send and receive reactions in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/reactions |
| Use spotlight state in ACS calling experiences | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/spotlight |
| Integrate Android TelecomManager with ACS Calling | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/telecommanager-integration |
| Enable Teams Together Mode via ACS Calling SDKs | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/together-mode |
| Transfer calls with Azure Communication Services SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/transfer-calls |
| Archive ACS chat threads to custom storage | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/chat-sdk/archive-chat-threads |
| Integrate ACS chat with Teams DLP policies | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/chat-sdk/data-loss-prevention |
| Integrate ACS chat with Azure AI translation | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/chat-sdk/translating-chats |
| Use Teams Shared Line Appearance with ACS | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/cte-calling-sdk/shared-line-appearance |
| Accept or decline Job Router offers via SDK | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/accept-decline-offer |
| Use Azure Functions as custom rules in Job Router | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/azure-function |
| Customize worker ranking for Job Router best-worker mode | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/customize-worker-scoring |
| Escalate jobs in Job Router using exception policies | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/escalate-job |
| Get estimated wait time and queue position via Job Router | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/estimated-wait-time |
| Classify jobs using Job Router SDKs | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/job-classification |
| Route jobs to preferred workers in Job Router | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/preferred-worker |
| Schedule jobs with Azure Communication Services Job Router | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/scheduled-jobs |
| Subscribe to Job Router events via Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/router-sdk/subscribe-events |
| Customize button bar actions in ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/button-injection |
| Integrate iOS CallKit with ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/callkit |
| Enable closed captions with ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/closed-captions |
| Inject custom user data models into ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/data-model |
| Handle events in Azure Communication Services UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/events |
| Set up one-to-one calling with ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/one-to-one-calling |
| Configure ACS UI Library to skip setup screen | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/skip-setup-screen |
| Integrate Android TelecomManager with ACS UI Library | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/telecommanager |
| Download WhatsApp media from Azure Communication events | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/download-media |
| Integrate WhatsApp text and media via Advanced Messages SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/get-started |
| Subscribe to WhatsApp Advanced Messaging events with Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/handle-advanced-messaging-events |
| Implement WhatsApp interactive messages using Advanced Messages | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/send-interactive-messages |
| Send WhatsApp reaction messages with Advanced Messages SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/send-reaction-messages |
| Send WhatsApp sticker messages via Advanced Messages SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/send-sticker-messages |
| Send WhatsApp template messages with Advanced Messages SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/send-template-messages |
| Create chat threads with ACS Chat SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/get-started |
| Connect ACS chat to Microsoft Teams meetings | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/meeting-interop |
| Integrate Azure OpenAI bot with ACS chat | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/openai-chat-bot-integration |
| Integrate Azure Bot Service bots into ACS chat | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/quickstart-botframework-integration |
| Use ACS Chat SDK in React Native apps | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/react-native |
| Manage email sender addresses using ACS Management SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/add-multiple-senders-mgmt-sdks |
| Handle Azure email events with Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/handle-email-events |
| Manage email suppression lists via Management SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/manage-suppression-list-management-sdks |
| Hydrate Azure EmailClient with existing messageId | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/hydrate-email-client-with-message-id |
| Poll Azure Email send status using SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/manually-poll-for-email-status |
| Send Azure Email messages with file attachments via SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/send-email-with-attachments |
| Send Azure Email messages with inline attachments via SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/send-email-with-inline-attachments |
| Use the Azure Email object model to build send payloads | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/use-email-object-model-for-payload |
| Send email via SMTP to Azure Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-smtp/send-email-smtp |
| Send email with SMTP and XOAUTH2 in .NET | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-smtp/send-email-smtp-oauth |
| Create and exchange access tokens for Teams users with ACS | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/manage-teams-identity |
| Create Azure Communication Rooms via SDK or API | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/rooms/get-started-rooms |
| Join room calls using web and mobile Calling SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/rooms/join-rooms-call |
| Manage room calls with Calling and Call Automation SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/rooms/manage-rooms-call |
| Create and route jobs with Job Router SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/router/get-started-router |
| Integrate Azure OpenAI with ACS Job Router for worker matching | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/router/job-router-azure-openai-integration |
| Handle ACS SMS and delivery events with Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/sms/handle-sms-events |
| Receive and process ACS SMS via Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/sms/receive-sms |
| Send SMS with Azure Communication Services SDKs | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/sms/send |
| Implement emergency PSTN calling with ACS | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/telephony/emergency-calling |
| Use JavaScript SDK to look up phone operator info | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/telephony/number-lookup |
| Enable PSTN calling in apps with ACS Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/telephony/pstn-call |
| Access Teams Phone via Azure Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensibility-access-teams-phone |
| Answer Teams Phone calls with Call Automation | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensibility-answer-teams-calls |
| Place outbound Teams Phone calls with Call Automation | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensibility-server-outbound-call |
| Use Teams Phone Extensibility REST API | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/tpe/teams-phone-extensiblity-rest-api |
| Integrate Adaptive Cards into ACS chat UI | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/ui-library/get-started-chat-adaptive-card |
| Integrate ACS chat UI library composites | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/ui-library/get-started-chat-ui-library |
| Integrate ACS UI Library composites into applications | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/ui-library/get-started-composites |
| Combine Calling and Chat SDKs in Android apps | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-android-calling-chat-sdk |
| Integrate ACS Data Channel messaging in calling apps | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-data-channel |
| Implement raw audio and video with ACS Unity SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-raw-media-access |
| Connect ACS users to Teams Auto Attendant | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-teams-auto-attendant |
| Connect ACS users to Teams Call Queue | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-teams-call-queue |
| Place interop calls between ACS and Teams users | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-teams-interop-group-calls |
| Add background blur and replacement in ACS video | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-video-effects |
| Run ACS WebJS calling in Android WebView | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-webview |
| Add closed captions to ACS calling applications | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-with-closed-captions |
| Integrate Azure Communication Services Real Time Text | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-with-real-time-text |
| Add 1:1 video calling using JavaScript Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-with-video-calling |
| Implement custom Teams voice and video calling client | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-with-voice-video-calling-custom-teams-client |
| Integrate voice calling into apps with Calling SDK | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/getting-started-with-calling |
| Handle Azure Communication Services calling events via Event Grid | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/handle-calling-events |
| Build AI-powered virtual assistants with Call Automation | https://learn.microsoft.com/en-us/azure/communication-services/samples/call-automation-ai |
| Integrate Call Automation with Azure OpenAI voice models | https://learn.microsoft.com/en-us/azure/communication-services/samples/call-automation-azure-openai-sample |
| Understand and customize ACS Group Chat Hero sample | https://learn.microsoft.com/en-us/azure/communication-services/samples/chat-hero-sample |
| Detect sensitive email content using Azure AI | https://learn.microsoft.com/en-us/azure/communication-services/samples/email-detect-sensitive-content |
| Automate Azure Email resources with PowerShell | https://learn.microsoft.com/en-us/azure/communication-services/samples/email-resource-management |
| Connect Copilot Studio agents to Azure Communication Services voice | https://learn.microsoft.com/en-us/azure/communication-services/samples/integrate-azure-communication-services-with-copilot-studio |
| Configure web push notifications for ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/samples/web-calling-push-notifications-sample |
| Configure ACS chat push notifications on iOS | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/add-chat-push-notifications |
| Add AR video filters with ACS and DeepAR | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/add-video-augmented-reality-tutorial |
| Send ACS VOIP push notifications via Event Grid and Notification Hubs | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/add-voip-push-notifications-event-grid |
| Enable ACS audio noise suppression and echo removal | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/audio-quality-enhancements/add-noise-supression |
| Use ACS UI JS bundles with Teams voice apps | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/calling-widget/calling-widget-js-tutorial |
| Build ACS UI calling widget for Teams queues | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/calling-widget/calling-widget-tutorial |
| Embed ACS chat into custom Microsoft Teams app | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/chat-app-teams-embed |
| Enable file attachment interoperability with Teams | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/chat-interop/meeting-interop-features-file-attachment |
| Enable inline image interoperability with Teams | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/chat-interop/meeting-interop-features-inline-image |
| Collect user feedback with Azure Communication Services UI library | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/collecting-user-feedback/collecting-user-feedback |
| Implement Azure Communication Services End of Call Survey | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/end-of-call-survey-tutorial |
| Implement ACS chat file sharing with Blob Storage | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/file-sharing-tutorial-acs-chat |
| Enable file sharing in ACS–Teams interop chat | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/file-sharing-tutorial-interop-chat |
| Add inline image support to Teams interop chat | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/inline-image-tutorial-interop-chat |
| Retrieve Azure Communication Services Calling SDK log files | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/log-file-retrieval-tutorial |
| Integrate ACS SMS with Azure URL Shortener | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/sms-url-shortener |
| Build a trusted token service for Communication Services with Azure Functions | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/trusted-service-tutorial |
| Automate pre- and post-visit flows for Teams appointments | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/virtual-visits/extend-teams/before-and-after-appointment |
| Integrate custom scheduling with Teams Virtual appointments | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/virtual-visits/extend-teams/schedule |
| Attach custom diagnostic tags to ACS client telemetry | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/voice-video-calling/diagnostic-options-tag |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use ACS chat metrics in Azure Monitor | https://learn.microsoft.com/en-us/azure/communication-services/concepts/analytics/chat-metrics |
| Understand Azure email metric definitions and usage | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email-metrics |
| Supported MIME types for Azure Email attachments | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-attachment-allowed-mime-types |
| Request quota increases for ACS email domains | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-quota-increase |
| Known issues and limitations for Teams external users | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/limitations |
| Understand feature support for Teams external users in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/meeting-capabilities |
| Phone number eligibility and limits for Argentina in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-argentina |
| Phone number eligibility and limits for Australia in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-australia |
| Phone number eligibility and limits for Austria in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-austria |
| Phone number eligibility and limits for Belgium in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-belgium |
| Phone number eligibility and limits for Brazil in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-brazil |
| Phone number eligibility and limits for Canada in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-canada |
| Phone number eligibility and limits for Chile in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-chile |
| Phone number eligibility and limits for China in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-china |
| Phone number eligibility and limits for Colombia in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-colombia |
| Phone number eligibility and limits for Czech Republic in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-czech-republic |
| Phone number eligibility and limits for Denmark in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-denmark |
| Check Estonia phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-estonia |
| Check Finland phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-finland |
| Check France phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-france |
| Check Germany phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-germany |
| Check Hong Kong phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-hong-kong |
| Check Indonesia phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-indonesia |
| Check Ireland phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-ireland |
| Check Israel phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-israel |
| Check Italy phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-italy |
| Check Japan phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-japan |
| Check Latvia phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-latvia |
| Check Lithuania phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-lithuania |
| Check Luxembourg phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-luxembourg |
| Check Malaysia phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-malaysia |
| Check Mexico phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-mexico |
| Check Netherlands phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-netherlands |
| Check New Zealand phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-new-zealand |
| Check Norway phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-norway |
| Check Philippines phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-philippines |
| Check Poland phone number availability and restrictions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-poland |
| Check Azure phone number rules for Portugal | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-portugal |
| Check Azure phone number rules for Saudi Arabia | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-saudi-arabia |
| Check Azure phone number rules for Singapore | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-singapore |
| Check Azure phone number rules for Slovakia | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-slovakia |
| Check Azure phone number rules for Slovenia | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-slovenia |
| Check Azure phone number rules for South Africa | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-south-africa |
| Check Azure phone number rules for South Korea | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-south-korea |
| Check Azure phone number rules for Spain | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-spain |
| Check Azure phone number rules for Sweden | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-sweden |
| Check Azure phone number rules for Switzerland | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-switzerland |
| Check Azure phone number rules for Taiwan | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-taiwan |
| Check Azure phone number rules for Thailand | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-thailand |
| Check Azure phone number rules for United Arab Emirates | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-united-arab-emirates |
| Check Azure phone number rules for United Kingdom | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-united-kingdom |
| Check Azure phone number rules for United States | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/phone-number-management-for-united-states |
| Check phone number availability and eligibility by country | https://learn.microsoft.com/en-us/azure/communication-services/concepts/numbers/sub-eligibility-number-capability |
| Understand Azure Communication Services PSTN pricing rules | https://learn.microsoft.com/en-us/azure/communication-services/concepts/pstn-pricing |
| Interpret Azure Job Router metrics definitions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/router/metrics |
| Review Azure Communication Services API limits and quotas | https://learn.microsoft.com/en-us/azure/communication-services/concepts/service-limits |
| Implement ACS emergency calling by supported region | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/emergency-calling-concept |
| Review Azure direct routing telephony limitations | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/known-limitations-acs-telephony |
| Understand ACS toll-free calling limitations by region | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/toll-free-calling |
| Use and manage ACS trial and verified phone numbers | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/trial-phone-numbers-faq |
| Review Calling SDK platform support and feature limits | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/calling-sdk-features |
| Configure Music Mode audio quality in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/music-mode |
| Handle Azure Email sending tier limit exceptions | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-advanced/throw-exception-when-tier-limit-reached |
| Get and manage Azure Communication Services trial phone numbers | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/telephony/get-trial-phone-number |
| Handle Azure Communication Services token expiration in calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/call-setup-issues/invalid-or-expired-tokens |
| ACS limits for concurrent incoming video subscriptions | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/reaching-max-number-of-active-video-subscriptions |

### Security
| Topic | URL |
|-------|-----|
| Understand data transfer and terms for ACS WhatsApp | https://learn.microsoft.com/en-us/azure/communication-services/concepts/advanced-messaging/whatsapp/whatsapp-terms-of-service |
| Choose and configure authentication methods for Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/concepts/authentication |
| Understand ACS call flow topologies and encryption | https://learn.microsoft.com/en-us/azure/communication-services/concepts/detailed-call-flows |
| Apply sender authentication best practices in Azure email | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-authentication-best-practice |
| Configure email domains and sender authentication | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-domain-and-sender-authentication |
| Configure authentication for apps with Microsoft 365 users | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/custom-teams-endpoint-authentication-overview |
| Configure closed captions in ACS–Teams interop scenarios | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/enable-closed-captions |
| Enable and configure Teams interoperability for ACS apps | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/enable-interoperability-teams |
| Security model for Teams external users with ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/security |
| Configure Teams admin controls for ACS external users | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/teams-administration |
| Configure Microsoft Entra API permissions for Teams communication | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/teams-user/azure-ad-api-permissions |
| Use Rooms API for secure, structured meetings | https://learn.microsoft.com/en-us/azure/communication-services/concepts/rooms/room-concept |
| Configure caller identity and CNAM for ACS telephony | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/how-to-manage-your-calling-identity |
| Secure Call Automation webhook and Event Grid endpoints | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/call-automation/secure-webhook-endpoint |
| Track and manage Teams meeting and room roles | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/calling-sdk/manage-role-assignment |
| Enable and use managed identity with Azure Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/managed-identity |
| Configure SMTP authentication for Azure Email sending | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/email/send-email-smtp/smtp-authentication |
| Configure Entra ID authentication for Communication Services clients | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/identity/microsoft-entra-id-authentication-integration |
| Sign Azure Communication Services HTTP requests with HMAC | https://learn.microsoft.com/en-us/azure/communication-services/tutorials/hmac-header-tutorial |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure Email custom domain configuration issues | https://learn.microsoft.com/en-us/azure/communication-services/concepts/email/email-domain-configuration-troubleshooting |
| Monitor logs and metrics for Teams external users | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/guest/monitor-logs-metrics |
| Troubleshoot common Teams Phone extensibility issues | https://learn.microsoft.com/en-us/azure/communication-services/concepts/interop/tpe/teams-phone-extensibility-troubleshooting |
| Resolve common Azure SMS issues and questions | https://learn.microsoft.com/en-us/azure/communication-services/concepts/sms/sms-faq |
| Monitor and troubleshoot Azure direct routing components | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/monitoring-troubleshooting-telephony/monitor-direct-routing |
| Resolve outbound call failures in Azure direct routing | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/monitoring-troubleshooting-telephony/troubleshoot-outbound-calls |
| Fix TLS certificate and SIP OPTIONS issues in direct routing | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/monitoring-troubleshooting-telephony/troubleshoot-tls-certificate-sip-options |
| Diagnose Azure Communication Services PSTN call failures | https://learn.microsoft.com/en-us/azure/communication-services/concepts/telephony/troubleshooting-pstn-call-failures |
| Collect diagnostics to troubleshoot Azure Communication Services | https://learn.microsoft.com/en-us/azure/communication-services/concepts/troubleshooting-info |
| Diagnose call quality issues with ACS Call Diagnostics | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/call-diagnostics |
| Diagnose call quality issues with ACS Call Diagnostics | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/call-diagnostics |
| Diagnose call issues using User Facing Diagnostics in ACS | https://learn.microsoft.com/en-us/azure/communication-services/concepts/voice-video-calling/user-facing-diagnostics |
| Troubleshoot Azure Communication Services UI Library calls | https://learn.microsoft.com/en-us/azure/communication-services/how-tos/ui-library-sdk/troubleshooting |
| Troubleshoot Azure-linked WhatsApp Business accounts | https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/advanced-messaging/whatsapp/whatsapp-business-account-faq |
| Diagnose audio delay issues in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/delay-issue |
| Resolve echo problems in ACS audio calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/echo-issue |
| Fix low incoming audio volume in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/incoming-audio-low-volume |
| Diagnose one-way audio from faulty microphones in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/microphone-issue |
| Fix one-way audio when microphone permission is denied | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/microphone-permission |
| Handle temporary one-way audio from network reconnection in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/network-issue |
| Investigate poor audio quality in ACS voice calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/poor-quality |
| Diagnose one-way audio from speaker issues in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/audio-issues/speaker-issue |
| Fix ACS calls ending with 410/3112 network errors | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/call-setup-issues/call-ends-with-410-3112 |
| Troubleshoot slow call setup in ACS WebJS calling | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/call-setup-issues/call-setup-takes-too-long |
| Fix failed CallAgent creation in ACS WebJS SDK | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/call-setup-issues/failed-to-create-call-agent |
| Resolve missing incoming call notifications in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/call-setup-issues/no-incoming-call-notifications |
| Troubleshoot slow askDevicePermission responses in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/device-issues/ask-device-permission-api-takes-too-long |
| Troubleshoot missing microphone list in ACS DeviceManager | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/device-issues/no-enumerated-microphone-list |
| Fix missing speaker list with ACS getSpeakers API | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/device-issues/no-enumerated-speaker-list |
| Resolve missing device permission prompts in ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/device-issues/no-permission-prompt |
| Apply general troubleshooting strategies for ACS calling issues | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/general-troubleshooting-strategies/overview |
| Interpret Azure Communication Services calling error codes and messages | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/general-troubleshooting-strategies/understanding-error-codes |
| Collect verbose browser logs for ACS troubleshooting | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/how-to-collect-browser-verbose-log |
| Collect ACS call information for issue diagnosis | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/how-to-collect-call-info |
| Collect ACS WebJS client logs using @azure/logger | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/how-to-collect-client-logs |
| Capture diagnostic audio recordings for ACS call issues | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/how-to-collect-diagnostic-audio-recordings |
| Gather Windows audio event logs for ACS audio issues | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/how-to-collect-windows-audio-event-log |
| Resolve cameraFreeze issues in ACS video calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/camera-freeze |
| Resolve cameraPermissionDenied in ACS applications | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/camera-permission-denied |
| Fix cameraStartFailed errors in ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/camera-start-failed |
| Handle cameraStartTimedOut in ACS video setup | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/camera-start-timed-out |
| Investigate cameraStoppedUnexpectedly in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/camera-stopped-unexpectedly |
| Resolve capturerStartFailed for ACS screen sharing | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/capturer-start-failed |
| Diagnose capturerStoppedUnexpectedly in ACS sharing | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/capturer-stopped-unexpectedly |
| Investigate microphoneMuteUnexpectedly events in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/microphone-mute-unexpectedly |
| Troubleshoot microphoneNotFunctioning in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/microphone-not-functioning |
| Address microphonePermissionDenied in ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/microphone-permission-denied |
| Diagnose networkReceiveQuality issues in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/network-receive-quality |
| Interpret networkReconnect UFD and ICE failures in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/network-reconnect |
| Interpret networkRelaysNotReachable UFD in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/network-relays-not-reachable |
| Diagnose networkSendQuality issues in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/network-send-quality |
| Fix noMicrophoneDevicesEnumerated issues in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/no-microphone-devices-enumerated |
| Interpret noNetwork user-facing diagnostics in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/no-network |
| Resolve noSpeakerDevicesEnumerated in ACS calling | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/no-speaker-devices-enumerated |
| Fix screenshareRecordingDisabled on macOS for ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/screenshare-recording-disabled |
| Handle speakingWhileMicrophoneIsMuted alerts in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/references/ufd/speaking-while-microphone-is-muted |
| Resolve call end response codes in ACS workloads | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/troubleshooting-codes |
| Resolve ACS errors when disposing video renderer during subscription | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/application-disposes-video-renderer |
| Troubleshoot ACS createView timeout video errors | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/create-view-timeout |
| Mitigate poor video quality from bad network in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/network-poor |
| Handle remote video becoming unavailable during ACS subscription | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/remote-video-becomes-unavailable |
| Handle unavailable video subscription errors in ACS | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/subscribing-video-not-available |
| Diagnose frozen sender video in ACS calls | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/video-is-frozen |
| Address high CPU impact on ACS video quality | https://learn.microsoft.com/en-us/azure/communication-services/resources/troubleshooting/voice-video-calling/video-issues/video-sender-has-high-cpu-load |

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
