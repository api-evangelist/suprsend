# SuprSend (suprsend)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
