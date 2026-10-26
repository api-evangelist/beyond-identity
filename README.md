# Beyond Identity (beyond-identity)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
