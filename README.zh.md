<div align="center">

[English](README.md) | **中文**

</div>

# CONFLUX ARENA

**基于 Conflux eSpace 的 Web3 任务与游戏化平台**

[![Live](https://img.shields.io/badge/状态-在线-brightgreen?style=flat-square)](https://confluxarena.org)
[![Conflux eSpace](https://img.shields.io/badge/网络-Conflux%20eSpace-00BFFF?style=flat-square)](https://confluxnetwork.org)

---

## 关于

Conflux Arena 是基于 [Conflux eSpace](https://confluxnetwork.org) 的 Web3 平台。用户完成任务、赚取经验值、通过等级排行榜（青铜到钻石）竞争，并领取免 Gas 的 NFT 奖励。项目方可发布可验证的链上互动活动——杜绝机器人和虚假活动。

平台还包含模拟交易、价格预测和 AI 智能助手——全部运行在同一套代码库中。

---

## 产品

| 产品 | 描述 | 链接 |
|:-----|:-----|:-----|
| **任务竞技场** | 30+ 种任务类型，链上验证 | [/arena](https://confluxarena.org/arena) |
| **模拟交易** | CFX/USDT0 交易模拟器，最高 50 倍杠杆 | [/trading](https://confluxarena.org/trading) |
| **价格预测** | 每周 CFX 价格预测游戏，设有奖金池 | [/predictions](https://confluxarena.org/predictions) |
| **NFT 奖励** | 免 Gas 的 ERC-721 领取，ECDSA 签名验证 | [/nft](https://confluxarena.org/nft) |
| **学习赚取** | 区块链教育，XP 奖励 | [/learn](https://confluxarena.org/learn) |
| **文档** | 面向用户和项目方的完整平台文档 | [/docs](https://confluxarena.org/docs) |

---

## 任务系统

- **30+ 种任务类型** — 社交（Twitter、Telegram、Discord）、DeFi（swap、hold、stake、LP）、NFT、问答、推荐
- **链上验证** — DeFi 和 NFT 任务通过 RPC 和 ConfluxScan 直接验证，无需人工审核
- **任务门控** — 按代币余额、NFT 持有、等级或质押仓位控制访问
- **活动系统** — 将任务组合为活动，共享进度追踪
- **AI 任务编辑器** — 通过自然语言描述生成任务
- **Webhook 和 API** — 项目方通过 Webhook 和 API 密钥集成自动验证

## NFT 和奖励

- **免 Gas 铸造** — 平台赞助 NFT 领取的 Gas 费用
- **ECDSA 签名** — 后端签名，智能合约验证
- **等级系统** — 青铜、白银、黄金、钻石，奖励逐级递增
- **批量支付** — CFX + eSpace 上任意 ERC-20 代币（USDT0、AxCNH、USDT、USDC、PPI 等）通过智能合约发放
- **推荐计划** — 邀请完成任务的用户可获得 XP 奖励

## 交易与预测

- **模拟交易** — CFX/USDT0 交易对，$1,000 虚拟余额，多空仓位，止盈止损，每周竞赛
- **最高 50 倍杠杆** — 维持保证金自动清算
- **价格预测** — CFX/USDT0 价格多空预测，1 小时到 1 周时间范围，XP 奖励
- **排行榜** — 交易盈亏、预测准确度、任务 XP 独立排名

## 平台

- **多钱包支持** — MetaMask、Fluent、OKX、WalletConnect（500+ 钱包）、EIP-6963 发现协议
- **AI 助手** — Claude 驱动的聊天组件，FAQ、通知和动态推送
- **Telegram 机器人** — 社区管理、反垃圾、账号绑定、任务通知
- **反欺诈系统** — 重复检测、跨钱包证明匹配、IP 分析、机器人评分
- **项目仪表板** — 数据分析、任务管理、NFT 集合、团队角色、支付工具

---

## 智能合约

| 合约 | 描述 |
|:-----|:-----|
| ArenaProjectNFT v1/v2 | ERC-721，ECDSA 领取，付费铸造，铸造周期 |
| ArenaProjectNFTFactory v1/v2 | 为每个项目部署 NFT 集合 |
| ArenaBatchPayment v2 | 多代币批量奖励（CFX + ERC-20） |

---

## 生态系统

| 仓库 | 描述 |
|:-----|:-----|
| **[confluxarena](https://github.com/confluxarena/confluxarena)** | 任务平台、交易、预测 |
| **[x402-boilerplate](https://github.com/confluxarena/x402-boilerplate)** | x402 协议 — 基于链上 USDT0 结算的付费 AI API |

---

## 技术栈

`PHP 8.4` · `PostgreSQL 16` · `Solidity` · `Vite 5` · `Tailwind CSS` · `ethers.js 6` · `Redis` · `Cloudflare` · `Node.js 20` · `Claude AI`

---

## 路线图

| 阶段 | 状态 | 亮点 |
|:-----|:-----|:-----|
| 第一阶段 | 已完成 | 核心平台、社交任务、多钱包 |
| 第二阶段 | 已完成 | DeFi 任务、链上验证、代币持有 |
| 第三阶段 | 已完成 | NFT 徽章、数据分析、推荐、AI 助手、预测 |
| 第四阶段 | 2026 年第二季度+ | ARENA 代币、质押、KOL 排行榜 |
| 第五阶段 | 未来 | NFT 市场、DAO 治理、跨链 |

---

## 链接

| | |
|:--|:--|
| **官网** | [confluxarena.org](https://confluxarena.org) |
| **Twitter** | [@CONFLUX_ARENA](https://x.com/CONFLUX_ARENA) |
| **Telegram** | [@confluxarena](https://t.me/confluxarena) |
| **Medium** | [@confluxarena](https://medium.com/@confluxarena) |
| **YouTube** | [@CONFLUX_ARENA](https://www.youtube.com/@CONFLUX_ARENA) |
| **邮箱** | hello@confluxarena.org |

