# Safe (Gnosis Safe)

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
