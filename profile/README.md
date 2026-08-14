# Accensa

Merchant back-office for x402 sellers on Stellar — receipts, refunds,
and revenue reconciliation for services that sell to AI agents.

**[Live Dashboard](https://accensa-dashboard.vercel.app)** • **[Verify a Receipt](https://accensa-dashboard.vercel.app/verify)** • **[Documentation](https://accensa.github.io/accensa-app/)**

- [accensa-app](https://github.com/accensa/accensa-app) — merchant dashboard, indexer, and the `@accensa/sdk` TypeScript SDK
- [accensa-contracts](https://github.com/accensa/accensa-contracts) — Soroban contracts: on-chain receipt anchoring and a merchant refund vault
- [x402-facilitator-stellar](https://github.com/accensa/x402-facilitator-stellar) — an x402 facilitator for Stellar with Bazaar discovery support

Deployed on Stellar testnet. `ReceiptAnchor` and `RefundVault` contract IDs, and
the commands to invoke them yourself, are in
[DEPLOYMENTS.md](https://github.com/accensa/accensa-contracts/blob/main/DEPLOYMENTS.md).

Status: pre-release, building toward v1.0 release.
