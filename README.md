# Gustpack ($GPACK) 🎒⚡

> **Covered-call options market for Solana tokens.** Lock tokens, pick your strike and expiry, earn upfront SOL premium.

[![Solana](https://img.shields.io/badge/Solana-DeFi-9945FF?style=flat-square&logo=solana)](https://solana.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 📖 Overview

- **Brand**: Gustpack
- **Token Ticker**: `$GPACK`
- **Network / Ecosystem**: Solana & pump.fun
- **Contract Address (CA)**: Coming Soon on pump.fun
- **Official Links**:
  - Website: [https://gustpack.fun](https://gustpack.fun)
  - X (Twitter): [https://x.com/gustpack](https://x.com/gustpack)

---

## ⚡ Key Highlights

- **Upfront SOL Yield**: Earn SOL immediately when a buyer fills your option offer.
- **Automated Settlement**: Physical delivery upon exercise on-chain or collateral reclaim upon expiration.
- **Revenue Vault**: 30% of all protocol service fees are pooled and distributed time-weighted to staked **$GPACK** holders.
- **Buy & Burn**: 20% of protocol service fees automatically buy back **$GPACK** on the open market and burn it permanently.
- **Community Governance**: $GPACK holders vote on upcoming asset listings and platform parameters.

---

## 🛠️ Architecture & Protocol Mechanics

| Metric / Parameter | Value |
| --- | --- |
| **Program ID** | `CHhWwsszpmf8vzwqEA5Divj2D9ZWKetADFHu9jKDFdsa` |
| **Token Ticker** | `$GPACK` |
| **Protocol Service Fee** | 3.0% of premium on fill / 0.1% on exercise |
| **Revenue Vault Split** | 30% of daily service fees |
| **Dev Buy & Burn Split** | 20% of daily service fees |
| **Contract Types** | Physical delivery covered calls |

- Pure static client application with interactive options payoff visualizer.
- Ready for zero-config Vercel deployment with `/api/gust` proxy rewrites (`vercel.json`).

---

## ⚖️ License

Distributed under the MIT License.
