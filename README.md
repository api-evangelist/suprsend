# SuprSend (suprsend)

SuprSend is a notification infrastructure platform that enables engineering teams to build, manage, and scale multi-channel notifications through a single unified API. It supports delivery across email, SMS, push notifications, in-app inbox, WhatsApp, Slack, and Microsoft Teams without requiring separate integrations for each channel. The platform provides workflow orchestration, template management, user preference management, smart channel routing with vendor fallback, and real-time delivery logs.

APIs.json: https://raw.githubusercontent.com/api-evangelist/suprsend/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=suprsend-api-evangelist&utm_content=repo

## Tags

- Notifications
- Multi-Channel
- Email
- SMS
- Push Notifications
- In-App Inbox
- WhatsApp
- Slack
- Notification Infrastructure
- Workflow Automation
- Template Management

## APIs

### SuprSend REST API

The SuprSend REST API allows developers to programmatically trigger notification workflows, manage users and subscribers, send broadcast notifications, and access delivery logs. Authentication uses workspace key and secret credentials.

- **Human URL:** https://docs.suprsend.com/reference/overview
- **Base URL:** https://hub.suprsend.com

### SuprSend Management API

The SuprSend Management API provides programmatic control over workspace assets including workflows, templates, and other SuprSend configuration resources. It uses service tokens for authentication.

- **Human URL:** https://docs.suprsend.com/docs/developer/overview
- **Base URL:** https://hub.suprsend.com

## Plans, Rate Limits, and FinOps

| Resource | File |
|---|---|
| Plans & Pricing | [plans/suprsend-plans-pricing.yml](plans/suprsend-plans-pricing.yml) |
| Rate Limits | [rate-limits/suprsend-rate-limits.yml](rate-limits/suprsend-rate-limits.yml) |
| FinOps | [finops/suprsend-finops.yml](finops/suprsend-finops.yml) |

**Pricing Summary:** Freemium model. Free plan includes 10,000 notifications/month. Essentials at $110/month (50K notifications, $2/1K overage). Business at $275/month (50K notifications, $5/1K overage). Enterprise custom pricing available.

**Rate Limits:** No hard numeric rate limit is publicly documented. Maximum 100 recipients per single workflow trigger call. Fair-use policy enforced with proactive outreach for anomalous traffic.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|---|---|
| Website | https://www.suprsend.com/ |
| Documentation | https://docs.suprsend.com/docs |
| GitHub Organization | https://github.com/suprsend |
| LinkedIn | https://www.linkedin.com/company/suprsend/ |
| X (Twitter) | https://x.com/suprsend |
| Blog | https://www.suprsend.com/blog |
| Changelog | https://docs.suprsend.com/changelog |
| Pricing | https://www.suprsend.com/pricing |
| Status Page | https://status.suprsend.com/ |

## Maintainers

- **Kin Lane** - kin@apievangelist.com
