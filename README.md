# Gustpack ($GPACK) 🎒⚡

> **Covered-call options market for Solana tokens.** Lock tokens, pick your strike and expiry, earn upfront SOL premium.

[![Solana](https://img.shields.io/badge/Solana-DeFi-9945FF?style=flat-square&logo=solana)](https://solana.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 📖 Overview

**Gustpack** (`$GPACK`) provides a non-custodial covered-call protocol built natively for Solana. Token holders can monetize their bags by writing covered calls with fully customizable strike prices and expiration dates, receiving instant, upfront SOL premiums.

### Key Highlights
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

---

## 🚀 Running Locally

### Prerequisites
- Node.js (v18+)

### Getting Started
```bash
# Clone the repository
git clone https://github.com/WerelayAgent/gustpack.git
cd gustpack

# Start the local server with live API proxy
npm start
```

Open [http://localhost:3459](http://localhost:3459) to view the landing page, or [http://localhost:3459/app](http://localhost:3459/app) to explore the options app.

---

## 🌐 Deployment

The repository includes a ready-to-deploy `vercel.json` configured with clean URLs and live proxying for Solana chain/market introspection:

```bash
vercel --prod
```

---

## ⚖️ License

Distributed under the MIT License.
