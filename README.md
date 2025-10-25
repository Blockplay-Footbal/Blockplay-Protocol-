# ⚽ BlockPlay Protocol

> “From the streets to the chain — football betting, reimagined.”

BlockPlay is a **peer-to-peer football betting protocol** built on **Polygon** and **Avalanche Subnet**, powered by Bitcoin, stablecoins, and the native token **$PLAY**.  
It’s fast, transparent, non-custodial — where fans become the house, and community becomes the heartbeat.

---

## 🧩 Core Features

| Layer | Description |
|-------|--------------|
| 🏗 **Polygon Layer** | Main settlement layer for bets, staking, lending & borrowing pools |
| 🧊 **Avalanche Subnet** | Handles **KYC/AML verification**, compliance logic & audit trails |
| 💸 **P2P Betting** | Users create and match bets directly — no intermediaries |
| 💰 **Pool Betting** | Collective pools auto-distribute winnings via smart contracts |
| 💎 **Staking / Borrowing / Lending** | Earn yield on stablecoins or $PLAY tokens |
| 🧠 **AI Analyzer** | Detects fraud, provides odds insights, and powers customer support |
| 🧭 **DAO Governance** | $PLAY holders govern rules, odds algorithms, and treasury allocation |
| ❤️ **Charity Mechanism** | 5% of supply + fee fraction goes to football infrastructure & talent development |

---

## ⚖️ Tokenomics

| Allocation | Percentage |
|-------------|-------------|
| Seed & Investors | **10%** |
| Ecosystem & Rewards | **30%** |
| Treasury & DAO | **25%** |
| Team & Advisors | **15%** |
| Community Staking & Liquidity | **15%** |
| Charity (Football & Talent Fund) | **5%** |

> Fees: 0.5% on bets + 0.5% on winnings  
> A fraction auto-routes to community charities.

---

## 🛠 Tech Stack

- **Smart Contracts:** Solidity (Polygon + Avalanche C-Chain)
- **Data Indexing:** The Graph Subgraph
- **AI Layer:** Python / TensorFlow microservice for odds analysis & fraud detection
- **Frontend:** React + Tailwind (coming soon)
- **Wallets:** MetaMask, WalletConnect, OKX, TrustWallet
- **Tokens Supported:** BTC, USDT, USDC, DAI, $PLAY

---

## ⚙️ Setup Instructions

```bash
# 1. Clone repo
git clone https://github.com/<YOUR_USERNAME>/blockplay-protocol.git
cd blockplay-protocol

# 2. Install dependencies
npm install

# 3. Compile smart contracts
npx hardhat compile

# 4. Deploy to Polygon testnet
npx hardhat run scripts/deploy.js --network polygonMumbai

# 5. (Optional) Deploy Avalanche Subnet compliance module
cd avalanche-subnet
npm install
npx hardhat run scripts/deploy.js --network fuji
