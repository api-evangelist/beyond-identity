# Beyond Identity (beyond-identity)

Beyond Identity is a zero-trust passwordless authentication platform that eliminates passwords by binding credentials to physical devices using platform authenticators and cryptographic passkeys. The platform provides REST APIs for managing tenants, realms, identities, and device-bound credentials across workforce and customer identity use cases. Beyond Identity supports continuous risk assessment with device security signals, policy enforcement, and just-in-time access controls, with multi-region deployment spanning US, EU, and FedRAMP environments.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/beyond-identity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/beyond-identity/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=beyond-identity-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=beyond-identity-api-evangelist&utm_content=repo)

## Tags

- Authentication
- Passwordless
- Zero Trust
- Identity
- Passkeys
- MFA
- Device Security
- OAuth 2.0
- OIDC
- SCIM

## APIs

### Beyond Identity Secure Access API

The Beyond Identity Secure Access API provides resource-oriented REST endpoints for managing the full lifecycle of passwordless authentication infrastructure. Resources include tenants, realms, groups, identities, credentials, credential binding jobs, applications, authenticator configurations, identity providers, SSO configs, resource servers, roles, tokens, and SCIM user/group endpoints.

- Human URL: [https://developer.beyondidentity.com/api/v1](https://developer.beyondidentity.com/api/v1)
- Base URL: https://api-us.beyondidentity.com

### Beyond Identity Next Generation API

The Next Generation Beyond Identity API provides the latest version of the platform's REST endpoints including updated identity management, credential binding, continuous risk assessment, and policy enforcement capabilities.

- Human URL: [https://docs.beyondidentity.com/api/v1](https://docs.beyondidentity.com/api/v1)
- Base URL: https://api-us.beyondidentity.com

## Plans / Rate Limits / FinOps

| Resource | Path |
|---|---|
| Plans & Pricing | [plans/beyond-identity-plans-pricing.yml](plans/beyond-identity-plans-pricing.yml) |
| Rate Limits | [rate-limits/beyond-identity-rate-limits.yml](rate-limits/beyond-identity-rate-limits.yml) |
| FinOps | [finops/beyond-identity-finops.yml](finops/beyond-identity-finops.yml) |

Beyond Identity uses a custom enterprise quote model across three tiers: Authentication Essentials, Zero Trust Identity and Device, and Secure Access Complete. Optional add-ons include Device360, Secure DevOps, and RealityCheck. Rate limits apply to Workforce and SCIM APIs; a 429 response is returned when exceeded. Contact support for rate limit overrides.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|---|---|
| Website | [https://www.beyondidentity.com/](https://www.beyondidentity.com/) |
| Documentation | [https://developer.beyondidentity.com/docs/](https://developer.beyondidentity.com/docs/) |
| GitHub Organization | [https://github.com/gobeyondidentity](https://github.com/gobeyondidentity) |
| LinkedIn | [https://www.linkedin.com/company/beyond-identity-inc](https://www.linkedin.com/company/beyond-identity-inc) |
| X (Twitter) | [https://twitter.com/beyondidentity](https://twitter.com/beyondidentity) |
| Blog | [https://www.beyondidentity.com/blog](https://www.beyondidentity.com/blog) |
| Pricing | [https://www.beyondidentity.com/pricing](https://www.beyondidentity.com/pricing) |
| Status Page | [https://status.beyondidentity.com/](https://status.beyondidentity.com/) |
| Changelog | [https://docs.beyondidentity.com/docs/release-notes/release-notes-changelog](https://docs.beyondidentity.com/docs/release-notes/release-notes-changelog) |
| Support | [https://support.beyondidentity.com/](https://support.beyondidentity.com/) |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
