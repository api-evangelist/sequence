---
name: sequence-read-token-balances
description: Read an EVM wallet's native and token (ERC-20/721/1155) balances across a chain using the Sequence Indexer.
api: Sequence Indexer
operations:
  - GetNativeTokenBalance
  - GetTokenBalancesSummary
  - GetTokenBalancesDetails
auth: X-Access-Key (project access key) header
---

# Read token balances with the Sequence Indexer

All calls are webrpc: `POST https://{chain}-indexer.sequence.app/rpc/Indexer/{Method}`
with an `X-Access-Key` header and a JSON body. Pick the chain host (e.g.
`mainnet-indexer.sequence.app`, `polygon-indexer.sequence.app`,
`base-indexer.sequence.app`).

## Steps

1. Get the native (gas-token) balance with `GetNativeTokenBalance`, passing
   `{ "accountAddress": "0x..." }`.
2. Get a rollup of all token holdings with `GetTokenBalancesSummary`, passing the
   account address and an optional `filter`. This returns one entry per contract.
3. For a specific contract's per-token detail (individual ERC-1155/721 token IDs), call
   `GetTokenBalancesDetails` with the `contractAddress` and account.
4. Paginate list results with the shared `page` object: pass `page.pageSize` and follow
   `page.more` / `page.after` to continue.

## Conventions & errors

- Every request is a POST; there are no query-string resources (see
  `conventions/sequence-conventions.yml`).
- On `429` you received `ErrorRateLimited` (code 2005) — back off; limits scale with the
  project tier/MAUs. On `401` (`ErrorUnauthorized`, code 1000) the access key is missing
  or wrong. Full catalog: `errors/sequence-problem-types.yml`.
