# Bundie

**AI-powered DeFi yield optimization. One click.**

Bundie aggregates yield strategies across the Ethereum ecosystem and uses AI to recommend personalized yield bundles — so you can invest in multiple high-interest opportunities with a single transaction.

---

## The Problem

DeFi yield is fragmented across thousands of protocols and chains. Finding good opportunities means hours of manual research, complex multi-step transactions (bridging, swapping, approving), and constant monitoring. Most users either miss opportunities or take on risk they don't understand.

## The Solution

Bundie solves this with three things:

1. **AI-powered discovery** — Analyzes your wallet history, risk profile, and preferences to recommend strategies tailored to you
2. **Bundled investing** — Mix and match yields across protocols and chains into a single bundle, deployed in one click
3. **Cross-chain execution** — Handles bridging, routing, and approvals behind the scenes across Scroll, Arbitrum, Base, and more

---

## How It Works

### Your Personal Vault
When you sign up, Bundie creates a **personal smart-contract vault** on Scroll. This vault is non-custodial — your funds are always in your own contract, never pooled with other users.

### AI Analysis
Bundie's AI analyzes your on-chain history (transaction patterns, risk profile, position sizing) and recommends strategies across three risk tiers: **Conservative**, **Balanced**, and **Aggressive**. The AI is a research assistant — it recommends, you decide.

### Bundle & Deploy
Select strategies individually or let AI build a bundle for you. One transaction deposits across multiple protocols and chains. Receipt tokens track your share of each yield pool.

### Monitor & Rebalance
Track your positions in real-time. When market conditions change, Bundie surfaces rebalance suggestions — you choose whether to act.

---

## Features

- **AI Copilot** — Personalized strategy recommendations based on wallet analysis
- **Bundle Builder** — Mix and match yield strategies across protocols and chains
- **One-Click Deploy** — No more manual bridging, swapping, and approving
- **Cross-Chain** — Access opportunities on Scroll, Arbitrum, Base, and more via LayerZero
- **Risk-Rated** — Clear risk tiers from Stable to Growth
- **Non-Custodial** — Your funds live in your own smart contract vault
- **Social Investing** — Discover bundles from other users, copy or fork configurations
- **MCP Server** — Integrate Bundie with AI coding assistants (Claude, Cursor, etc.)

---

## Fee Structure

| Fee | Amount | Details |
|-----|--------|---------|
| **Management fee** | 3% annual | Deducted from yield, not as a lump sum |
| **Performance fee** | None | — |
| **Deposit/withdrawal** | None | — |
| **AI analysis** | None | — |
| **Gas fees** | ~$0.05–$0.15 | Scroll L2 gas, not paid to Bundie |

**30-day free trial** for new users. Bundie only earns when you earn.

---

## Architecture

Bundie is built as a modular protocol:

| Component | Description |
|-----------|-------------|
| **Contracts** | Solidity 0.8 — vaults, routers, bridges, fee manager (Foundry, 650+ tests) |
| **Web App** | Next.js 15, React 19, Privy auth, ZeroDev smart accounts |
| **AI Analyzer** | Wallet analysis, strategy recommendation, risk profiling |
| **Aggregator** | Multi-protocol yield discovery (Euler, Morpho, Yearn, Silo, Fluid, Ethena, Centrifuge, USX) |
| **TX Validator** | LayerZero cross-chain transaction verification |
| **MCP Server** | AI tool integration for Claude, Cursor, and other LLM clients |
| **Docs** | Fumadocs-powered documentation site |

---

## Security

- **Non-custodial** — Funds stay in user-owned smart contract vaults
- **Audited** — Smart contracts audited with 650+ tests including fuzz testing
- **Transparent** — All positions visible on-chain at all times
- **Access control** — Timelock upgrades, validator authorization, slippage protection

DeFi carries inherent risks including smart contract vulnerabilities, market volatility, and liquidity constraints. Always do your own research.

---

## Links

- **App**: [app.bundie.fi](https://app.bundie.fi)
- **Docs**: [docs.bundie.fi](https://docs.bundie.fi)
- **MCP Server**: [mcp.bundie.fi](https://mcp.bundie.fi)
- **Twitter**: [@Bundie__](https://x.com/Bundie__)

---

© 2026 Bundie. All rights reserved.
