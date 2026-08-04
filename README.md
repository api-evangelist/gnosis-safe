# Safe (Gnosis Safe)

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

Safe (formerly Gnosis Safe) is a multi-signature smart contract wallet platform for managing digital assets on EVM-compatible blockchains. The Safe Transaction Service provides a REST API for tracking, proposing, and confirming multisig transactions across 40+ supported networks.

**Developer Portal:** https://developer.safe.global/  
**Documentation:** https://docs.safe.global/  
**API Overview:** https://docs.safe.global/core-api/transaction-service-overview  
**GitHub:** https://github.com/safe-global  

## APIs

- **Safe Transaction Service API** — Core REST API for multisig transaction lifecycle management (propose, confirm, execute, retrieve) across all supported EVM chains. Base URL: `https://api.safe.global/tx-service/{chain}/api/v1/`
- **Safe Delegates API** — Create, list, and delete delegate addresses authorized to propose transactions on behalf of Safe owners.
- **Safe Messages API** — Off-chain EIP-191/EIP-712 message signing and retrieval for Safe smart accounts.
- **Safe 4337 User Operations API** — ERC-4337 account abstraction user operations support for gas-abstracted and sponsored transactions.
- **Safe API Kit** — Official TypeScript client SDK (`@safe-global/api-kit`) wrapping all Transaction Service endpoints.

## Plans

| Plan | Price | Monthly Quota | RPS | Webhooks |
|------|-------|--------------|-----|----------|
| Unauthenticated | Free | 5,000 | 2 | None |
| Builder | Free | 50,000 | 5 | None |
| Growth | EUR 199/month | 1,000,000 | 15 | 2 |
| Scale | EUR 499+/month | 3,000,000 | 50 | 10 |

Custom plans available above Scale thresholds: support@safe.global

## Artifacts

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/gnosis-safe-plans-pricing.yml` — API Commons Plans specification
- `rate-limits/gnosis-safe-rate-limits.yml` — API Commons Rate Limits specification
- `finops/gnosis-safe-finops.yml` — FinOps Framework / FOCUS-aligned cost model
