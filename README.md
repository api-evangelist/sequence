# Sequence

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

Sequence is a web3 developer platform (0xsequence, now part of Polygon Labs) for building blockchain applications: smart-contract wallets, a universal crypto payments and swap layer, a real-time multi-chain Indexer with balances, token prices, contract events and webhooks, plus Metadata, Marketplace, Transactions (Relayer) and Analytics APIs. Its backend APIs are webrpc-generated (POST /rpc/{Service}/{Method}) authenticated with a project access key and secret JWT, and it ships first-party SDKs for TypeScript, Go, Unity, Unreal, Kotlin and Swift plus a CLI. Backed by a16z and Polychain.

**Areas:** Company · Web3 · Blockchain · Wallets · Payments · Cryptocurrency · Indexer · NFT · Developer Platform · Gaming

## Sequence on APIs.io

Everything profiled for Sequence is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sequence/](https://apis.io/providers/sequence/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Sequence Analytics API](https://apis.io/apis/sequence/sequence-analytics-api/) — The Analytics API from Sequence — 177 operation(s) for analytics.
- [Sequence Marketplace API](https://apis.io/apis/sequence/sequence-marketplace-api/) — The Marketplace API from Sequence — 34 operation(s) for marketplace.
- [Sequence Public API](https://apis.io/apis/sequence/sequence-public-api/) — Endpoints accessible by passing your project-access-key in the header. This is injected whenever you login automatically.
- [Sequence Rpc API](https://apis.io/apis/sequence/sequence-rpc-api/) — The Rpc API from Sequence — 32 operation(s) for rpc.
- [Sequence Secret API](https://apis.io/apis/sequence/sequence-secret-api/) — Endpoints that require a Sequence service token intended to be secret. You can manually generate one on Sequence Builder and pass it as a Bearer Token.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Sequence Indexer Webhooks](https://apis.io/asyncapis/sequence/sequence-indexer-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [sequence-mcp.yml](https://apis.io/servers/sequence/sequence-mcp-yml/)

#### Collections (5)

Postman and Open Collection request collections.

- [Api Analytics API](https://apis.io/collections/sequence/open-sequence-analytics-api/)
- [Api Analytics Marketplace API](https://apis.io/collections/sequence/open-sequence-marketplace-api/)
- [Api Analytics public API](https://apis.io/collections/sequence/open-sequence-public-api/)
- [Api Analytics Rpc API](https://apis.io/collections/sequence/open-sequence-rpc-api/)
- [Api Analytics secret API](https://apis.io/collections/sequence/open-sequence-secret-api/)

#### Overlays (7)

OpenAPI overlays, including conversational phrasing for each operation.

- [Sequence Analytics Overlay](https://apis.io/overlays/sequence/sequence-analytics-overlay/)
- [Sequence Builder Overlay](https://apis.io/overlays/sequence/sequence-builder-overlay/)
- [Sequence Indexer Overlay](https://apis.io/overlays/sequence/sequence-indexer-overlay/)
- [Sequence Infrastructure Overlay](https://apis.io/overlays/sequence/sequence-infrastructure-overlay/)
- [Sequence Marketplace Overlay](https://apis.io/overlays/sequence/sequence-marketplace-overlay/)
- [Sequence Metadata Overlay](https://apis.io/overlays/sequence/sequence-metadata-overlay/)
- [Sequence Transactions Overlay](https://apis.io/overlays/sequence/sequence-transactions-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Sequence Authentication](https://apis.io/security/sequence/sequence-authentication/)
- [Sequence Domain Security](https://apis.io/security/sequence/sequence-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sequence.xyz)
- [Documentation](https://docs.sequence.xyz)
- [API reference](https://docs.sequence.xyz/api-references/overview)
- [Pricing](https://sequence.xyz/pricing)
- [Sign up](https://sequence.build)
- [Support](https://support.sequence.xyz/en/)
- [Blog](https://sequence.xyz/blog)
- [GitHub](https://github.com/0xsequence)

## API Evangelist rating

**Kin Score 39.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 53.7 |
| Contract governance | 4.5 |
| Operational transparency | 42.1 |
| Developer ergonomics | 58.9 |
| Access clarity | 10.5 |

**Agent readiness 24.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sequence/](https://apis.io/providers/sequence/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sequence: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sequence/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
