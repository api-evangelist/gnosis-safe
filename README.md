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

Safe (formerly Gnosis Safe) provides multi-signature smart contract wallets for managing digital assets on EVM-compatible blockchains. The Safe Transaction Service is a REST API that tracks transactions submitted to Safe smart contracts, enabling off-chain collection of signatures, owner notification of pending transactions, delegate management, on-chain message signing, and token/NFT balance retrieval across 40+ supported networks including Mainnet, Arbitrum, Optimism, Polygon, Base, Gnosis Chain, zkSync, and testnets. The Safe{Core} SDK (API Kit) provides a TypeScript client for the Transaction Service. Authentication uses JWT API keys with tiered plans ranging from a free Builder tier to high-throughput Scale plans.

**Areas:** Multisig · Smart Contract · Ethereum · Web3 · Blockchain · DeFi · SAFe · Gnosis · Wallets

## Safe (Gnosis Safe) on APIs.io

Everything profiled for Safe (Gnosis Safe) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gnosis-safe/](https://apis.io/providers/gnosis-safe/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Safe Delegates API](https://apis.io/apis/gnosis-safe/delegates/) — Endpoints for managing delegate relationships on a Safe. Delegates are addresses authorized by Safe owners to propose transactions without being full…
- [Safe Messages API](https://apis.io/apis/gnosis-safe/messages/) — Endpoints for off-chain message signing via Safe smart accounts. Allows creating signed messages for a Safe, retrieving existing messages by their hash, and…
- [Safe 4337 User Operations API](https://apis.io/apis/gnosis-safe/4337/) — Endpoints supporting ERC-4337 account abstraction user operations for Safe smart accounts. Allows listing, retrieving, and managing ERC-4337 user operations…
- [Safe API Kit (TypeScript SDK)](https://apis.io/apis/gnosis-safe/api-kit/) — Official TypeScript client SDK for the Safe Transaction Service API. Wraps all Transaction Service endpoints with typed methods for proposing transactions,…
- [Safe (Gnosis Safe) about API](https://apis.io/apis/gnosis-safe/gnosis-safe-about-api/) — The about API from Safe (Gnosis Safe) — 6 operation(s) for about.
- [Safe (Gnosis Safe) analytics API](https://apis.io/apis/gnosis-safe/gnosis-safe-analytics-api/) — The analytics API from Safe (Gnosis Safe) — 1 operation(s) for analytics.
- [Safe (Gnosis Safe) Contracts API](https://apis.io/apis/gnosis-safe/gnosis-safe-contracts-api/) — The contracts API from Safe (Gnosis Safe) — 2 operation(s) for contracts.
- [Safe (Gnosis Safe) Data Decoder API](https://apis.io/apis/gnosis-safe/gnosis-safe-data-decoder-api/) — The data-decoder API from Safe (Gnosis Safe) — 1 operation(s) for data-decoder.
- [Safe (Gnosis Safe) Delegates API](https://apis.io/apis/gnosis-safe/gnosis-safe-delegates-api/) — The delegates API from Safe (Gnosis Safe) — 5 operation(s) for delegates.
- [Safe (Gnosis Safe) Messages API](https://apis.io/apis/gnosis-safe/gnosis-safe-messages-api/) — The messages API from Safe (Gnosis Safe) — 3 operation(s) for messages.
- [Safe (Gnosis Safe) Modules API](https://apis.io/apis/gnosis-safe/gnosis-safe-modules-api/) — The modules API from Safe (Gnosis Safe) — 2 operation(s) for modules.
- [Safe (Gnosis Safe) Owners API](https://apis.io/apis/gnosis-safe/gnosis-safe-owners-api/) — The owners API from Safe (Gnosis Safe) — 2 operation(s) for owners.
- [Safe (Gnosis Safe) Safes API](https://apis.io/apis/gnosis-safe/gnosis-safe-safes-api/) — The safes API from Safe (Gnosis Safe) — 6 operation(s) for safes.
- [Safe (Gnosis Safe) Tokens API](https://apis.io/apis/gnosis-safe/gnosis-safe-tokens-api/) — The tokens API from Safe (Gnosis Safe) — 3 operation(s) for tokens.
- [Safe (Gnosis Safe) Transactions API](https://apis.io/apis/gnosis-safe/gnosis-safe-transactions-api/) — The transactions API from Safe (Gnosis Safe) — 13 operation(s) for transactions.
- [Safe (Gnosis Safe) Tx Service API](https://apis.io/apis/gnosis-safe/gnosis-safe-tx-service-api/) — The Tx Service API from Safe (Gnosis Safe) — 5 operation(s) for tx service.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gnosis Safe Agentic Access](https://apis.io/agentic-access/gnosis-safe/gnosis-safe-agentic-access/)

#### JSON Schema (65)

The data models the API reads and writes.

- [AllTransactionsSchema](https://apis.io/schemas/gnosis-safe/AllTransactionsSchema/)
- [AllTransactionsSchemaSerializerV2](https://apis.io/schemas/gnosis-safe/AllTransactionsSchemaSerializerV2/)
- [CodeErrorResponse](https://apis.io/schemas/gnosis-safe/CodeErrorResponse/)
- [Contract](https://apis.io/schemas/gnosis-safe/Contract/)
- [ContractAbi](https://apis.io/schemas/gnosis-safe/ContractAbi/)
- [DataDecoder](https://apis.io/schemas/gnosis-safe/DataDecoder/)
- [Delegate](https://apis.io/schemas/gnosis-safe/Delegate/)
- [DelegateSerializerV2](https://apis.io/schemas/gnosis-safe/DelegateSerializerV2/)
- [Erc20Info](https://apis.io/schemas/gnosis-safe/Erc20Info/)
- [EthereumTxWithTransfersResponse](https://apis.io/schemas/gnosis-safe/EthereumTxWithTransfersResponse/)
- [IndexingStatus](https://apis.io/schemas/gnosis-safe/IndexingStatus/)
- [MasterCopyResponse](https://apis.io/schemas/gnosis-safe/MasterCopyResponse/)
- [ModulesResponse](https://apis.io/schemas/gnosis-safe/ModulesResponse/)
- [OwnerResponse](https://apis.io/schemas/gnosis-safe/OwnerResponse/)
- [PaginatedAllTransactionsSchemaList](https://apis.io/schemas/gnosis-safe/PaginatedAllTransactionsSchemaList/)
- [PaginatedAllTransactionsSchemaSerializerV2List](https://apis.io/schemas/gnosis-safe/PaginatedAllTransactionsSchemaSerializerV2List/)
- [PaginatedContractList](https://apis.io/schemas/gnosis-safe/PaginatedContractList/)
- [PaginatedSafeCollectibleResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeCollectibleResponseList/)
- [PaginatedSafeDelegateResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeDelegateResponseList/)
- [PaginatedSafeExportTransactionList](https://apis.io/schemas/gnosis-safe/PaginatedSafeExportTransactionList/)
- [PaginatedSafeLastStatusList](https://apis.io/schemas/gnosis-safe/PaginatedSafeLastStatusList/)
- [PaginatedSafeMessageResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeMessageResponseList/)
- [PaginatedSafeModuleTransactionResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeModuleTransactionResponseList/)
- [PaginatedSafeMultisigConfirmationResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeMultisigConfirmationResponseList/)
- [PaginatedSafeMultisigTransactionResponseList](https://apis.io/schemas/gnosis-safe/PaginatedSafeMultisigTransactionResponseList/)
- …and 40 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Gnosis Safe Api Context](https://apis.io/jsonld/gnosis-safe/gnosis-safe-api/)
- [Gnosis Safe Context](https://apis.io/jsonld/gnosis-safe/gnosis-safe-context/)

#### Examples (60)

Example requests and responses.

- [About_Deployments_List](https://apis.io/examples/gnosis-safe/about_deployments_list/)
- [About_Ethereum_Rpc_Retrieve](https://apis.io/examples/gnosis-safe/about_ethereum_rpc_retrieve/)
- [About_Ethereum_Tracing_Rpc_Retrieve](https://apis.io/examples/gnosis-safe/about_ethereum_tracing_rpc_retrieve/)
- [About_Indexing_Retrieve](https://apis.io/examples/gnosis-safe/about_indexing_retrieve/)
- [About_Retrieve](https://apis.io/examples/gnosis-safe/about_retrieve/)
- [About_Singletons_List](https://apis.io/examples/gnosis-safe/about_singletons_list/)
- [Analytics_Multisig_Transactions_By_Origin_Retrieve](https://apis.io/examples/gnosis-safe/analytics_multisig_transactions_by_origin_retrieve/)
- [Contracts_List](https://apis.io/examples/gnosis-safe/contracts_list/)
- [Contracts_Retrieve](https://apis.io/examples/gnosis-safe/contracts_retrieve/)
- [Data_Decoder_Create](https://apis.io/examples/gnosis-safe/data_decoder_create/)
- [Delegates_Create](https://apis.io/examples/gnosis-safe/delegates_create/)
- [Delegates_Create_2](https://apis.io/examples/gnosis-safe/delegates_create_2/)
- [Delegates_Destroy](https://apis.io/examples/gnosis-safe/delegates_destroy/)
- [Delegates_Destroy_2](https://apis.io/examples/gnosis-safe/delegates_destroy_2/)
- [Delegates_List](https://apis.io/examples/gnosis-safe/delegates_list/)
- [Delegates_List_2](https://apis.io/examples/gnosis-safe/delegates_list_2/)
- [Messages_Retrieve](https://apis.io/examples/gnosis-safe/messages_retrieve/)
- [Messages_Signatures_Create](https://apis.io/examples/gnosis-safe/messages_signatures_create/)
- [Module_Transaction_Retrieve](https://apis.io/examples/gnosis-safe/module_transaction_retrieve/)
- [Modules_Safes_List](https://apis.io/examples/gnosis-safe/modules_safes_list/)
- [Modules_Safes_Retrieve](https://apis.io/examples/gnosis-safe/modules_safes_retrieve/)
- [Multisig_Transactions_Confirmations_Create](https://apis.io/examples/gnosis-safe/multisig_transactions_confirmations_create/)
- [Multisig_Transactions_Confirmations_List](https://apis.io/examples/gnosis-safe/multisig_transactions_confirmations_list/)
- [Multisig_Transactions_Destroy](https://apis.io/examples/gnosis-safe/multisig_transactions_destroy/)
- [Multisig_Transactions_Destroy_2](https://apis.io/examples/gnosis-safe/multisig_transactions_destroy_2/)
- …and 35 more published on APIs.io

#### Collections (12)

Postman and Open Collection request collections.

- [Safe Transaction Service 4337 API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-4337-api/)
- [Safe Transaction Service 4337 about API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-about-api/)
- [Safe Transaction Service 4337 analytics API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-analytics-api/)
- [Safe Transaction Service 4337 contracts API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-contracts-api/)
- [Safe Transaction Service 4337 data-decoder API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-data-decoder-api/)
- [Safe Transaction Service 4337 delegates API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-delegates-api/)
- [Safe Transaction Service 4337 messages API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-messages-api/)
- [Safe Transaction Service 4337 modules API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-modules-api/)
- [Safe Transaction Service 4337 owners API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-owners-api/)
- [Safe Transaction Service 4337 safes API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-safes-api/)
- [Safe Transaction Service 4337 tokens API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-tokens-api/)
- [Safe Transaction Service 4337 transactions API](https://apis.io/collections/gnosis-safe/open-gnosis-safe-transactions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Safe (Gnosis Safe) — jsonschema rules](https://apis.io/rules/gnosis-safe/gnosis-safe-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Gnosis Safe Authentication](https://apis.io/security/gnosis-safe/gnosis-safe-authentication/)
- [Gnosis Safe Domain Security](https://apis.io/security/gnosis-safe/gnosis-safe-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Gnosis Safe Plans Pricing](https://apis.io/plans/gnosis-safe/gnosis-safe-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Gnosis Safe Rate Limits](https://apis.io/rate-limits/gnosis-safe/gnosis-safe-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Gnosis Safe Finops](https://apis.io/finops/gnosis-safe/gnosis-safe-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://safe.global/)
- [Documentation](https://docs.safe.global/)
- [Blog](https://safe.global/blog)

## API Evangelist rating

**Kin Score 32.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 48.5 |
| Contract governance | 9.8 |
| Operational transparency | 28.9 |
| Developer ergonomics | 35.7 |
| Access clarity | 7.9 |

**Agent readiness 23.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gnosis-safe/](https://apis.io/providers/gnosis-safe/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Safe (Gnosis Safe): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gnosis-safe/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
