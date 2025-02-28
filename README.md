# Solana Wallet Tracking Bot


## About The Project

This is a Telegram bot that can track any Solana wallet in real time, providing relevant information of each transaction made in Pump.fun, Raydium, and Jupiter including transaction hash, tokens and amount swapped, price of the token in SOL, token market cap, and much more.

## Features

| Feature                                             | Description                                                   |
|-----------------------------------------------------|---------------------------------------------------------------|
| 📈 Real-time tracking of any transaction            | Track every Solana transaction as it happens.                 |
| 🔍 Detects Pump.fun, Raydium, and Jupiter transactions | Identify transactions across top Solana DEXes.                |
| 💰 Gets SOL price of the token swapped              | Displays token price in SOL at the time of the swap.          |
| 📊 Get token market cap at the time swapped         | Shows the market cap of the token at the time of transaction. |
| 💰 Gets token amount and supply percentage owned    | Calculates the amount and percentage owned by each wallet.    |
| 🤖 Quick buy links for tokens                       | Provides links to Solana trading bots for token purchases.    |
| 🔗 Quick chart links for tokens                     | Provides links to Photon, GMGN, and Dex Screener charts.      |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

| Technology      | Description                                  |
|-----------------|----------------------------------------------|
| 🌐 Node.JS     | JavaScript runtime built on Chrome’s V8 engine. |
| 📘 TypeScript  | Superset of JavaScript for type safety.      |
| 📊 Prisma & Pulse | ORM and real-time database logging system.  |
| 🪙 Solana Web3.js | Solana's JavaScript API for interacting with the blockchain. |


<!-- GETTING STARTED -->

## Getting Started

Follow these simple steps to set up Handi Cat locally on your machine.

### Prerequisites

- **Node version 14.x**

### Steps

+-------------------------------------------+  
| 1. Clone the repo                        |  
|    Command:                              |  
|    git clone https://github.com/DracoR22/handi-cat_wallet-tracker.git  |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 2. Install NPM Packages                  |  
|    Command:                              |  
|    pnpm install                           |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 3. Rename `.env.example` to `.env`        |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 4. Create a Free Database on Supabase    |  
|    Follow: [supabase.com](https://supabase.com) |
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 5. Paste Connection String in `.env`     |  
|    In Supabase Dashboard -> Database     |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 6. Setup Prisma Pulse for real-time Logs  |  
|    Guide: [Prisma Pulse Setup](https://medium.com/@dilsharahasanka/prisma-pulse-hands-on-guide-b220954b3245) |
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 7. Get your Prisma Pulse API Key and Add  |  
|    to the `.env` file                    |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 8. Create a Telegram Bot and Get BOT_TOKEN |  
|    Create Bot on: [BotFather](https://core.telegram.org/bots#botfather) |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 9. Run Database Migration Command         |  
|    Command:                              |  
|    pnpm db:migrate                        |  
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 10. Setup Solana RPC Provider in `solana.ts` |  
|    Modify NETWORKS in `src/providers/solana.ts` |
+-------------------------------------------+  
        |
        v
+-------------------------------------------+  
| 11. Start the Bot                        |  
|    Command:                              |  
|    pnpm start                             |  
+-------------------------------------------+  


<!-- CONTACT -->

## Contact
  Telegram | [Dogewhiz](https://t.me/dogewhiz)                             |
