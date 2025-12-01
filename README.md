<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Prowzi/X402PESA/main/assets/banner-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Prowzi/X402PESA/main/assets/banner-light.png">
  <img alt="X402PESA - Global Payments via x402 Protocol" src="https://raw.githubusercontent.com/Prowzi/X402PESA/main/assets/banner-dark.png" width="100%">
</picture>

<div align="center">

# 🌍 X402PESA

### **Global Payments. Fully Onchain. Chain Agnostic.**

[![License: MIT](https://img.shields.io/badge/License-MIT-F9B23D.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![x402 Protocol](https://img.shields.io/badge/Powered_by-x402_Protocol-1BE0A2?style=for-the-badge)](https://x402.org)
[![Twitter Follow](https://img.shields.io/twitter/follow/x402pesa?style=for-the-badge&logo=x&color=000000&labelColor=000000)](https://x.com/x402pesa)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-1BE0A2.svg?style=for-the-badge)](http://makeapullrequest.com)

<br />

**💸 Send money anywhere • ⚡ Sub-second finality • 🔗 Any blockchain**

<br />

[🚀 **Get Early Access**](https://x402pesa.com/waitlist) &nbsp;•&nbsp; [📖 Docs](https://docs.x402pesa.com) &nbsp;•&nbsp; [💬 Discord](https://discord.gg/x402pesa) &nbsp;•&nbsp; [🐦 Twitter](https://x.com/x402pesa)

<br />

---

</div>

<br />

## 🎯 What is X402PESA?

**X402PESA** is a next-generation payment rail that brings the simplicity of mobile money to the power of blockchain. Built on the **[x402 protocol](https://x402.org)**, it enables instant, near-zero-fee payments that work across any chain, anywhere in the world.

> *"HTTP has status code 402 - Payment Required. It was reserved for future use in 1997. The future is now."*

<br />

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║     💸 TRADITIONAL PAYMENTS              ⚡ X402PESA                         ║
║     ════════════════════                 ════════                            ║
║                                                                              ║
║     📊 2-5% fees                         📊 0.01% fees                       ║
║     ⏳ 1-3 days                          ⚡ < 1 second                        ║
║     🌍 Regional only                     🌐 Worldwide                        ║
║     🏦 Centralized                       🔗 Fully onchain                    ║
║     📱 Single platform                   ⛓️  Chain agnostic                   ║
║     👤 Humans only                       🤖 Agent-ready                      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<br />

## ✨ Features

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Lightning Fast

Transactions settle in **under 1 second**.

No waiting. No pending states. No uncertainty. Just instant confirmation.

</td>
<td width="33%" valign="top">

### 💰 Near-Zero Fees

Pay just **0.01%** per transaction.

That's $0.05 on a $500 transfer. Keep more of your money where it belongs.

</td>
<td width="33%" valign="top">

### 🌐 Chain Agnostic

Works across **any blockchain**.

Ethereum, Solana, Base, Arbitrum, Polygon — one interface for all chains.

</td>
</tr>
<tr>
<td width="33%" valign="top">

### 🔐 Fully Onchain

Every transaction is **cryptographically signed** and permanently verifiable.

No trust required. Ever.

</td>
<td width="33%" valign="top">

### 🤖 Agent-Ready

Built for the **x402 protocol**.

AI agents and machines can pay just like humans — enabling the agentic economy.

</td>
<td width="33%" valign="top">

### 📱 Simple UX

Feels like M-PESA or Venmo.

**No seed phrases**. No gas management. No crypto complexity.

</td>
</tr>
</table>

<br />

## 📊 Fee Comparison Calculator

See how much you save with X402PESA:

| Amount Sent | Traditional Mobile Money | Bank Wire | Credit Card | **X402PESA** | **You Save** |
|:-----------:|:------------------------:|:---------:|:-----------:|:------------:|:------------:|
| **$10** | $0.50 (5%) | $25+ | $0.60 | **$0.001** | 🟢 **99%+** |
| **$100** | $3.00 (3%) | $25+ | $3.50 | **$0.01** | 🟢 **99%+** |
| **$1,000** | $15.00 (1.5%) | $35+ | $35.00 | **$0.10** | 🟢 **99%+** |
| **$10,000** | $100.00 (1%) | $50+ | $350.00 | **$1.00** | 🟢 **98%+** |
| **$100,000** | $500.00 | $75+ | $3,500.00 | **$10.00** | 🟢 **98%+** |

<br />

## 🏗️ Architecture

```
                                   ┌────────────────────────┐
                                   │     X402PESA Apps      │
                                   │  ┌──────┐  ┌────────┐  │
                                   │  │ Web  │  │ Mobile │  │
                                   │  └──────┘  └────────┘  │
                                   └───────────┬────────────┘
                                               │
                    ┌──────────────────────────┴──────────────────────────┐
                    │                                                      │
                    │              🔷 x402 Protocol Layer 🔷               │
                    │                                                      │
                    │  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌────────┐  │
                    │  │ Payment  │ │ Identity │ │ Routing  │ │ Bridge │  │
                    │  │ Engine   │ │ Service  │ │ Service  │ │Service │  │
                    │  └──────────┘ └──────────┘ └──────────┘ └────────┘  │
                    │                                                      │
                    └──────────────────────────┬──────────────────────────┘
                                               │
          ┌────────────────┬───────────────────┼───────────────────┬────────────────┐
          │                │                   │                   │                │
          ▼                ▼                   ▼                   ▼                ▼
    ┌──────────┐    ┌──────────┐        ┌──────────┐        ┌──────────┐    ┌──────────┐
    │ Ethereum │    │  Solana  │        │   Base   │        │ Arbitrum │    │  + More  │
    │ Mainnet  │    │ Mainnet  │        │    L2    │        │   One    │    │  Chains  │
    └──────────┘    └──────────┘        └──────────┘        └──────────┘    └──────────┘
```

<br />

## 🌐 The x402 Protocol

X402PESA is built on **x402** — an open protocol for programmable payments on the internet.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                                                                                 │
│   📡 HTTP 402: Payment Required                                                 │
│   ═══════════════════════════════                                               │
│                                                                                 │
│   Reserved in HTTP/1.1 (1997) for "future use"                                  │
│   Finally realized with blockchain technology                                   │
│                                                                                 │
│   ┌─────────────────────────────────────────────────────────────────────────┐   │
│   │                                                                         │   │
│   │   1. CLIENT ──── Request Resource ────────────────────► SERVER          │   │
│   │                                                                         │   │
│   │   2. SERVER ──── 402 Payment Required ────────────────► CLIENT          │   │
│   │                  (includes payment details)                             │   │
│   │                                                                         │   │
│   │   3. CLIENT ──── Signed Payment ──────────────────────► CHAIN           │   │
│   │                                                                         │   │
│   │   4. CHAIN ───── Confirmation (< 1 sec) ──────────────► SERVER          │   │
│   │                                                                         │   │
│   │   5. SERVER ──── Resource Delivered ──────────────────► CLIENT          │   │
│   │                                                                         │   │
│   └─────────────────────────────────────────────────────────────────────────┘   │
│                                                                                 │
│   Use Cases:                                                                    │
│   • 🤖 AI agents paying for API calls automatically                            │
│   • 💳 Micropayments for content (pay per article, not subscriptions)          │
│   • 🔄 Streaming payments (per byte, per second, per query)                    │
│   • 🌐 Cross-border instant settlement                                         │
│   • 🎮 In-game economies and digital goods                                     │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

<br />

## 🚀 Quick Start

### Prerequisites

- **Node.js** 18+
- **pnpm** (recommended) or npm
- **PostgreSQL** database

### Installation

```bash
# Clone the repository
git clone https://github.com/Prowzi/X402PESA.git
cd X402PESA/x402pesa-landing

# Install dependencies (we use pnpm for speed)
pnpm install

# Set up environment variables
cp .env.example .env
# Edit .env with your DATABASE_URL

# Initialize database
pnpm prisma generate
pnpm prisma db push

# Start development server
pnpm dev
```

🎉 Visit **http://localhost:3000** to see the app!

<br />

## 🛠️ Tech Stack

<div align="center">

| Layer | Technologies |
|:-----:|:------------|
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Styling** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Deployment** | ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Protocol** | ![x402](https://img.shields.io/badge/x402_Protocol-1BE0A2?style=flat-square&logoColor=white) |

</div>

<br />

## 📁 Project Structure

```
x402pesa-landing/
│
├── 📂 components/              # React UI components
│   ├── Layout.tsx              # Main layout (header, footer, meta)
│   ├── FeeSlider.tsx           # Interactive fee comparison slider
│   ├── HowItWorksTabs.tsx      # Tabbed explanation section
│   ├── ScreenShowcase.tsx      # App screenshots carousel
│   └── X402Unlocks.tsx         # Protocol features section
│
├── 📂 lib/                     # Utilities & helpers
│   ├── fees.ts                 # Fee calculation logic
│   ├── i18n.ts                 # Internationalization (EN/SW)
│   └── prisma.ts               # Database client singleton
│
├── 📂 pages/                   # Next.js pages & API routes
│   ├── index.tsx               # Landing page
│   ├── waitlist.tsx            # Waitlist signup form
│   ├── _app.tsx                # App wrapper
│   └── api/
│       └── waitlist.ts         # POST /api/waitlist endpoint
│
├── 📂 prisma/
│   └── schema.prisma           # Database schema
│
├── 📂 styles/
│   └── globals.css             # Global styles, animations, Tailwind
│
├── 📂 public/                  # Static assets
│
├── .env.example                # Environment template
├── tailwind.config.js          # Tailwind configuration
├── tsconfig.json               # TypeScript configuration
└── package.json                # Dependencies & scripts
```

<br />

## 🎯 Roadmap

<table>
<tr>
<td align="center" width="25%">

### 🏁 Q4 2024
**Foundation**

✅ Landing page
✅ Waitlist system
✅ Core architecture
✅ Chain agnostic design
✅ x402 protocol integration

</td>
<td align="center" width="25%">

### 🔨 Q1 2025
**Alpha**

⬜ Wallet integration
⬜ First chain (Base)
⬜ Developer SDK
⬜ Private beta launch
⬜ Security audit

</td>
<td align="center" width="25%">

### 🧪 Q2 2025
**Beta**

⬜ Multi-chain support
⬜ iOS & Android apps
⬜ Merchant dashboard
⬜ Public beta
⬜ Fiat on/off ramps

</td>
<td align="center" width="25%">

### 🚀 Q3 2025
**Launch**

⬜ Production release
⬜ Agent marketplace
⬜ Enterprise APIs
⬜ Global expansion
⬜ More chains

</td>
</tr>
</table>

<br />

## 🤝 Contributing

We 💚 contributions! Here's how you can help:

| Type | Description |
|------|-------------|
| 🐛 **Bug Reports** | Found a bug? [Open an issue](https://github.com/Prowzi/X402PESA/issues/new) |
| 💡 **Feature Ideas** | Have an idea? [Start a discussion](https://github.com/Prowzi/X402PESA/discussions) |
| 📖 **Documentation** | Help us improve docs |
| 🔧 **Code** | Submit a pull request |

### Development Setup

```bash
# Fork and clone
git clone https://github.com/YOUR_USERNAME/X402PESA.git
cd X402PESA/x402pesa-landing

# Install & run
pnpm install
pnpm dev

# Make changes, then submit a PR!
```

<br />

## 📜 License

X402PESA is open source software licensed under the [MIT License](LICENSE).

<br />

## 🔗 Links & Resources

<div align="center">

| | | |
|:---:|:---:|:---:|
| 🌐 [**Website**](https://x402pesa.com) | 📖 [**Docs**](https://docs.x402pesa.com) | 🔗 [**x402 Protocol**](https://x402.org) |
| 🐦 [**Twitter**](https://x.com/x402pesa) | 💬 [**Discord**](https://discord.gg/x402pesa) | 📧 [**Email**](mailto:hello@x402pesa.com) |

</div>

<br />

---

<div align="center">

<br />

### 🌍 **Built for the World**

**Fully Onchain** &nbsp;•&nbsp; **Chain Agnostic** &nbsp;•&nbsp; **Worldwide**

<br />

<sub>Made with 💚 by the X402PESA team</sub>

<sub>© 2024-2025 X402PESA &nbsp;•&nbsp; Powered by x402 Protocol</sub>

<br />

⭐ **Star this repo** if you believe in the future of global payments!

</div>
