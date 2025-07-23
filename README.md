# 🌀 0G Labs Auto Swap Bot (Jaine App Airdrop Farming)

Bot automates token swaps on the 0G Labs network, designed specifically to interact with [Jaine App](https://test.jaine.app/) and push transactions on-chain to maximize airdrop participation.

<img width="1307" height="830" alt="image" src="https://github.com/user-attachments/assets/7aa3fce1-fdaf-40fc-b141-a60159af89ef" />

## 🎯 Purpose

This script performs randomized token swaps between:

- **BTC → USDT**
- **BTC → ETH**

It simulates organic, human-like usage activity across multiple wallets, helping farm potential **airdrop points** on the Jaine platform — which rewards active users.

## ⚙️ Features

- 🔁 Daily automated swaps (34–56 tx daily)
- 🔄 Random swap types (BTC → USDT or BTC → ETH)
- 🎲 Random amount per swap (0.000001 – 0.00001 BTC)
- ⏱️ Random delay between swaps (3–12 minutes)
- 👥 Supports **multi-wallet** operation via `.env`
- ✅ Automatically checks & sends `approve()` if needed

## 📦 Installation

### 1. Clone this repository:
```bash
git clone https://github.com/tihorsliced/auto-swap-test-jaine-app-0g-labs.git
```
```bash
cd auto-swap-test-jaine-app-0g-labs
```
### 2. Install dependencies:
```bash
npm install
```
### 3. Create a .env file:
```bash
nano .env
```
Input your privatekey
```bash
ACCOUNT_1_ADDRESS=0xYourAddressHere
ACCOUNT_1_PRIVATE_KEY=0xYourPrivateKeyHere

ACCOUNT_2_ADDRESS=0xAnotherAddress
ACCOUNT_2_PRIVATE_KEY=0xAnotherPrivateKey
```
You can add as many accounts as needed (ACCOUNT_3_..., etc).

### 4 Running the Bot
To run the script:
```bash
node index.js
```

- It starts immediately, performs 34–56 swaps for the day, then sleeps for 24 hours.

- Each transaction is pushed on-chain via 0G RPC and targets the Jaine App router contract.

- You will see printed logs for each swap, including transaction hash, token direction, and block number.

## 📌 About Jaine App
Jaine is a testnet DeFi protocol on 0G Labs, currently tracking swap activity and interaction frequency.
This bot helps simulate real usage to accumulate airdrop eligibility.

## ⚠️ Notes
- Ensure your test wallets are funded with test BTC, USDT, ETH on 0G Labs.
- This is for testnet and airdrop farming purposes only.

# 
#0GLabs #JaineApp #AirdropHunter #AirdropFarming #TestnetFarming #DeFiBot 
#PythonDeFi #AutoSwap #WalletAutomation #OnchainActivity #Web3Tools 
#CryptoAutomation #EthereumBot #DeFiTestnet #FarmingBot

