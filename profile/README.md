# Accensa

Merchant back-office for x402 sellers — receipts, refunds,
and revenue reconciliation for services that sell to AI agents, across chains.

**[Live Dashboard](https://accensa-dashboard.vercel.app)** • **[Verify a Receipt](https://accensa-dashboard.vercel.app/verify)** • **[Documentation](https://accensa.github.io/accensa-app/)**

- [accensa-app](https://github.com/accensa/accensa-app) — merchant dashboard, indexer, and the `@accensa/sdk` TypeScript SDK
- [accensa-contracts](https://github.com/accensa/accensa-contracts) — Soroban contracts: on-chain receipt anchoring and a merchant refund vault
- [x402-facilitator-stellar](https://github.com/accensa/x402-facilitator-stellar) — conformance spike: a minimal x402 facilitator for Stellar, built on `@x402/stellar`
- [accensa-till](https://github.com/accensa/accensa-till) — the same seller-side back-office for x402 payments on NEAR, just getting started

Live on Stellar testnet. `ReceiptAnchor` and `RefundVault` contract IDs, and
the commands to invoke them yourself, are in
[DEPLOYMENTS.md](https://github.com/accensa/accensa-contracts/blob/main/DEPLOYMENTS.md)
— which also records that the deployed wasm is `0.1.0` while `main` is at `0.3.0`.

Status: v0.x — `accensa-app` v0.1.0 and `accensa-contracts` v0.2.0 are released — building toward v1.0.
