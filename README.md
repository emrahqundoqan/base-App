# 🎮 Base Fun dApp

**Daily rewards, games and XP system on the Base blockchain.**

[![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=flat&logo=coinbase)](https://base.org)
[![Farcaster](https://img.shields.io/badge/Farcaster-Mini%20App-8465E6?style=flat)](https://farcaster.xyz)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat)](#license)

---

## 🌐 Live App

**[basefun-app.vercel.app](https://basefun-app.vercel.app)**

Also accessible via Farcaster and Base App as a Mini App.

---

## 📖 About

Base Fun dApp is a gaming and rewards platform built on Base Mainnet. Users earn XP and level up by completing daily check-ins, sending messages, and playing various onchain games. All transactions are executed on the Base blockchain.

---

## ✨ Features

### 📅 Daily Check-In
- Check in every day to earn **+10 XP**
- Maintain your daily streak
- Fee: **0.00001 ETH**

### ☀️ GM / GN
- Send **Good Morning** or **Good Night** to the community
- Earn **+5 XP** per message
- Fee: **0.00001 ETH**

### 🎮 Games

#### 🟡 Pic-Man
- Classic Pac-Man experience with a Base theme
- **21 levels**, new map and color theme every 3 levels
- Earn XP by completing levels
- Collect star pellets to earn **+1 life**
- Reach 10,000 points to earn **+1 life**
- Ghost eating streak: 200 → 400 → 800 → 1600 points
- A 5th ghost appears from level 7
- Continue from the level you died on

#### 🎲 Dice Game
- Roll two dice — doubles earn **Bonus XP**
- Fee: **0.00005 ETH**

#### 🎡 Lucky Wheel
- Spin the 16-segment wheel and earn XP (5 – 100 XP)
- Fee: **0.00005 ETH**

#### 🔢 Number Guess
- Pick a number between 1 and 10
- Guess correctly: **+100 XP** — wrong guess: XP equal to your chosen number
- Fee: **0.00001 ETH**

---

### 👤 Profile
- View wallet address and current level
- Detailed XP breakdown by source
- Earned badges
- Last 10 transactions with date and time

### 🔑 Admin Panel
- View all contract balances
- Withdraw ETH in one click
- *(Visible only to the owner address)*

---

## 🏆 XP Level System

| Level | Required XP |
|-------|------------|
| 🥉 Bronze | 0 – 999 XP |
| 🥈 Silver | 1,000 – 4,999 XP |
| 🥇 Gold | 5,000 – 9,999 XP |
| 💎 Platinum | 10,000 – 49,999 XP |
| 👑 Diamond | 50,000+ XP |

---

## 📜 Smart Contracts (Base Mainnet)

| Contract | Address |
|----------|---------|
| Check-In | `0xb4e5E1C7D4b0e846645F49995024D570A0A6218c` |
| GM | `0xfDeb4a6C1f8a96D1817e29916047dEa53e70111E` |
| GN | `0x5A4F2A0C1134efBCe9a4Debc7B000007Cdb637B9` |
| Dice Game | `0xB1c153F5b8eB0AB275c4ed721606D814750EFea9` |
| Lucky Wheel | `0x39b91858e45C33Bd6407c27449fdC773EE288cdC` |
| Number Game | `0x0eDc71073B43AE60a4ff6e54b827534CbF3b66e5` |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **Solidity ^0.8.20** | Smart contracts |
| **ethers.js v6** | Blockchain connection |
| **Farcaster Frame SDK** | Mini App support |
| **EIP-6963** | Multi-wallet support |
| **HTML / CSS / JS** | Frontend (no framework) |
| **Vercel** | Hosting |
| **Base Mainnet** | L2 Blockchain |

---

## 🚀 Setup

This project is built with pure HTML/CSS/JS — no build tools required.

```bash
# Clone the repo
git clone https://github.com/username/base-app.git

# Enter the directory
cd base-app

# Open directly (no server needed)
open index.html
```

Or deploy to Vercel:

```bash
vercel deploy
```

---

## 🔗 Links

- 🌐 **App:** [basefun-app.vercel.app](https://basefun-app.vercel.app)
- 🟣 **Farcaster:** Accessible as a Mini App
- 🔵 **Base App:** Accessible as a Mini App
- 📊 **Basescan:** [View contracts](https://basescan.org)

---

## 📄 License

© 2025 Base Fun dApp. All rights reserved.

The source code of this software is shared for viewing purposes only.  
It may not be copied, modified, distributed, or used for commercial purposes without explicit permission.

---

*Built on Base. ⚡*
