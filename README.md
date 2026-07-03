# Homethrive (homethrive)

Homethrive is a technology-enabled caregiving-support benefit that pairs a digital assistant (Homethrive "Dari") with human Care Guides to help family caregivers navigate backup care, aging, complex health, estate planning, and loss for their loved ones. It is sold to employers, health plans, financial institutions, ancillary insurers, brokers, and platform partners, and delivered to those sponsors' covered members.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/homethrive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/homethrive/refs/heads/main/apis.yml)

## API Status: No Public API

Homethrive does **not** publish a public or partner developer API. As of this review (2026-07-03) there is:

- No developer portal or API reference
- No OpenAPI, AsyncAPI, GraphQL, webhook, SSE, or WebSocket surface
- No SDK, CLI, or self-service sign-up for API credentials
- No public GitHub organization or open-source components

This is expected for the product. Homethrive is a **B2B2C, enterprise-gated benefit**: an employer or health plan buys it and offers it to their members. Individuals cannot self-provision it, and developers cannot self-provision access to it.

### How Homethrive actually integrates

Connectivity is handled privately during enterprise onboarding, not through a documented public API:

- **Eligibility file** — sponsors send member eligibility using an eligibility-file specification, typically over SFTP as batch CSV files.
- **Single Sign-On (SSO)** — members reach Homethrive's portal via SSO from the sponsor's benefits experience (for example an "Additional Benefits" tile in a health-plan portal).
- **Reporting** — Homethrive returns utilization and engagement data to the sponsor to measure clinical and financial outcomes.

These are contract-scoped integrations arranged during implementation. They are documented here honestly as an integration model, not as public API endpoints, and no endpoints have been modeled or fabricated.

## Tags

- Caregiving
- Family Caregivers
- Employee Benefits
- Health Plans
- Eldercare
- Backup Care
- Caregiver Support
- Digital Health
- B2B2C
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Pricing

Homethrive is sold through enterprise B2B contracts (per-employee-per-month or population-based pricing negotiated with the sponsoring employer or health plan). Pricing is not published, and there is no API pricing because there is no API product. Access for individuals is free at the point of use when it is offered through their employer or health plan.

## Common Properties

- [Website](https://homethrive.com)
- [LinkedIn](https://www.linkedin.com/company/homethrive-inc)
- [Blog](https://homethrive.com/blog/)
- [Sign Up (Eligible Members)](https://homethrive.com/eligible-members/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
