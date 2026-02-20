<div align="center">

**English** | [中文](README.zh.md)

</div>

# CONFLUX ARENA

**Web3 Quest & Gamification Platform on Conflux eSpace**

[![Live](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)](https://confluxarena.org)
[![Conflux eSpace](https://img.shields.io/badge/Network-Conflux%20eSpace-00BFFF?style=flat-square)](https://confluxnetwork.org)

---

## About

Conflux Arena is a Web3 platform on [Conflux eSpace](https://confluxnetwork.org) where users complete quests, earn XP, climb tier-based leaderboards (Bronze to Diamond), and claim gasless NFT rewards. Projects use it to launch verifiable on-chain engagement campaigns — no bots, no fake activity.

The platform also includes demo trading, price predictions, and an AI-powered assistant — all running on one codebase.

---

## Products

| Product | Description | Link |
|:--------|:------------|:-----|
| **Quest Arena** | 30+ quest types with on-chain verification | [/arena](https://confluxarena.org/arena) |
| **Demo Trading** | CFX/USDT0 simulator, up to 50x leverage, weekly competitions | [/trading](https://confluxarena.org/trading) |
| **Predictions** | Weekly CFX price prediction game with prize pools | [/predictions](https://confluxarena.org/predictions) |
| **NFT Rewards** | Gasless ERC-721 claims with ECDSA signatures | [/nft](https://confluxarena.org/nft) |
| **Learn & Earn** | Blockchain education with XP rewards | [/learn](https://confluxarena.org/learn) |
| **Docs** | Full platform documentation for users and projects | [/docs](https://confluxarena.org/docs) |

---

## Quest System

- **30+ quest types** — social (Twitter, Telegram, Discord), DeFi (swap, hold, stake, LP), NFT, quiz, referral
- **On-chain verification** — DeFi and NFT quests verified via RPC and ConfluxScan, no manual review
- **Quest gating** — access control by token balance, NFT ownership, level, or staking position
- **Campaigns** — group quests into campaigns with shared progress tracking
- **AI quest editor** — generate quests from natural language descriptions
- **Webhook & API** — projects integrate via webhooks and API keys for automated verification

## NFT & Rewards

- **Gasless minting** — platform sponsors gas fees for NFT claims
- **ECDSA signatures** — backend-signed claims verified by smart contract
- **Tier system** — Bronze, Silver, Gold, Diamond with escalating rewards
- **Batch payments** — CFX + any ERC-20 token on eSpace (USDT0, AxCNH, USDT, USDC, PPI, etc.) via smart contract
- **Referral program** — earn XP for inviting users who complete quests

## Trading & Predictions

- **Demo trading** — CFX/USDT0 pair, $1,000 virtual balance, long/short positions, TP/SL orders, weekly competitions
- **Up to 50x leverage** — with automatic liquidation at maintenance margin
- **Price predictions** — LONG/SHORT on CFX/USDT0 price, 1h to 1w timeframes, XP rewards
- **Leaderboards** — separate rankings for trading PnL, prediction accuracy, quest XP

## Platform

- **Multi-wallet** — MetaMask, Fluent, OKX, WalletConnect (500+ wallets), EIP-6963 discovery
- **AI assistant** — Claude-powered chat widget with FAQ, notifications, and activity feed
- **Telegram bot** — community moderation, anti-spam, account linking, quest notifications
- **Anti-fraud** — duplicate detection, cross-wallet proof matching, IP analysis, bot scoring
- **Project dashboard** — analytics, quest management, NFT collections, team roles, payment tools

---

## Smart Contracts

| Contract | Description |
|:---------|:------------|
| ArenaProjectNFT v1/v2 | ERC-721 with ECDSA claim, paid minting, mint periods |
| ArenaProjectNFTFactory v1/v2 | Deploy NFT collections per project |
| ArenaBatchPayment v2 | Multi-token batch rewards (CFX + ERC-20) |

---

## Ecosystem

| Repository | Description |
|:-----------|:------------|
| **[confluxarena](https://github.com/confluxarena/confluxarena)** | Quest platform, trading, predictions |
| **[payfi-escrow](https://github.com/confluxarena/payfi-escrow)** | Multichain B2B escrow protocol — stablecoin commerce with dispute resolution |

---

## Built With

`PHP 8.4` · `PostgreSQL 16` · `Solidity` · `Vite 5` · `Tailwind CSS` · `ethers.js 6` · `Redis` · `Cloudflare` · `Node.js 20` · `Claude AI`

---

## Roadmap

| Phase | Status | Highlights |
|:------|:-------|:-----------|
| Phase 1 | Completed | Core platform, social quests (Twitter, Telegram, Discord), XP & tier system, multi-wallet (8 wallets, EIP-6963) |
| Phase 2 | Completed | DeFi quests, on-chain verification, token holdings, quest gating, anti-fraud system, testimonials |
| Phase 3 | Completed | NFT badges, analytics, referrals, project dashboard, campaigns, batch payments (CFX + ERC-20), AI assistant, predictions, demo trading, Telegram bot, webhook API |
| Phase 4 | Q2 2026+ | ARENA token, token-based rewards, staking, KOL leaderboard, PayFi Escrow (B2B stablecoin commerce), multi-chain (Ethereum, Arbitrum, Base), public API & SDK |
| Phase 5 | Future | NFT marketplace, DAO governance, cross-chain quest verification, advanced quest types, AI quest generation, fiat on/off-ramp |

---

## Links

| | |
|:--|:--|
| **Website** | [confluxarena.org](https://confluxarena.org) |
| **Twitter** | [@CONFLUX_ARENA](https://x.com/CONFLUX_ARENA) |
| **Telegram** | [@confluxarena](https://t.me/confluxarena) |
| **Medium** | [@confluxarena](https://medium.com/@confluxarena) |
| **YouTube** | [@CONFLUX_ARENA](https://www.youtube.com/@CONFLUX_ARENA) |
| **Email** | hello@confluxarena.org |

