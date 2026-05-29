# kaiTracker
> A unified crypto portfolio tracker and trading dashboard  built for traders who are tired of switching between five different apps just to manage their positions.

**Final Year Thesis Project  Graded A (Excellent) | Kyiv Aviation Institute, 2025**

---

## The Problem

As a crypto trader, managing your portfolio across multiple chains and exchanges is a nightmare:
- Your BTC is on Binance, your ETH is in a hardware wallet, your SOL is on a DEX
- You're checking CoinGecko for prices, Etherscan for wallet balances, and your exchange app for open orders — all separately
- There's no single place to see your full picture, place orders, and track performance

Existing services : 


**kaiTracker is being built to fix that.**

---

## Vision

A single dashboard where traders can:

- **Track portfolio value** across multiple wallets and exchanges in real time
- **View live market prices** without leaving the app
- **Place buy/sell orders** directly from the portfolio view
- **Connect multiple chains** — EVM, Solana, and more
- **Link exchange accounts** — Binance, OKX, and others via API
- **Analyze performance** — P&L, allocation breakdown, historical charts

---

## Current State

> This project is a work in progress. Core backend architecture is implemented; trading and multi-chain features are under development.

**What's built:**
- User authentication and identity management (ASP.NET Core Identity)
- Database models and EF Core migrations
- MVC architecture with Controllers, Services, and Views
- API model layer for external data integration
- Frontend views with HTML/CSS/JS

**What's planned:**
- Multi-wallet connection (MetaMask, WalletConnect)
- Exchange API integration (Binance, OKX)
- Order placement and management
- Portfolio analytics and real time charts

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | ASP.NET Core MVC (.NET 8) |
| Language | C# |
| Database | Entity Framework Core + Migrations |
| Authentication | ASP.NET Core Identity |
| Frontend | Flowbite, HTML, CSS, JavaScript |
| Architecture | MVC + Service Layer pattern |

---

## Architecture


---

## Getting Started

### Prerequisites
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- SQL Server or SQLite

### Installation

```bash
git clone https://github.com/beez6239/kaiTracker.git
cd kaiTracker
dotnet restore
dotnet ef database update
dotnet run
```

---

## Why This Project Matters

Most crypto portfolio tools are either:
- **Too simple** : just price tracking, no trading
- **Exchange-locked** : only works with one exchange
- **Non-custodial only** : ignores CEX balances entirely

kaiTracker aims to bridge that gap combining on-chain wallet tracking with CEX API integration and order management in one unified interface, built by a trader who actually uses these tools daily.

---

## License

MIT © 2025 Robert
