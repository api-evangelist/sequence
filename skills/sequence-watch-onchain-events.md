---
name: sequence-watch-onchain-events
description: Register an Indexer webhook and/or subscribe to balance-update streams to react to on-chain activity in real time.
api: Sequence Indexer
operations:
  - AddWebhookListener
  - GetAllWebhookListeners
  - SubscribeBalanceUpdates
auth: X-Access-Key (project access key) header
---

# Watch on-chain events with the Sequence Indexer

Webrpc endpoint base: `POST https://{chain}-indexer.sequence.app/rpc/Indexer/{Method}`.

## Register a webhook

1. Call `AddWebhookListener` with your callback URL and a filter (contract addresses /
   accounts / event types) to receive HTTP POST callbacks when matching activity is
   indexed.
2. Confirm registration with `GetAllWebhookListeners`.
3. Manage delivery with `ToggleWebhookListener`, `PauseAllWebhookListeners`, and
   `RemoveWebhookListener` as needed.

## Or subscribe to a push stream

- Use `SubscribeBalanceUpdates` to receive a server-push stream of balance changes for
  watched accounts (also `SubscribeReceipts`, `SubscribeEvents`). See
  `asyncapi/sequence-indexer-webhooks.yml`.

## Conventions & errors

- Deliveries and streams are describing the same event domains: receipts, contract
  events, and balance updates.
- Handle `ErrorRateLimited` (429) with backoff and `ErrorUnauthorized` (401) by checking
  the `X-Access-Key`. Catalog: `errors/sequence-problem-types.yml`.
