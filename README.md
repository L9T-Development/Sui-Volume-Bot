# Sui-Volume-Bot

A bot built to track and manage transaction volume on the Sui blockchain(Cetus pool). This lightweight and efficient tool monitors activity, analyzes data, and can be an essential asset for developers working within the Sui blockchain ecosystem.

---

## Features

- **Real-Time Tracking**: Monitors transaction volume on the Sui blockchain in real-time.
- **Data Insights**: Collects and organizes transaction data for analysis.
- **Custom Alerts**: Sends alerts based on user-defined thresholds or events.
- **Easy Deployment**: Simple and intuitive setup process for all users.
- **Open Source**: Entirely free and modifiable under the repository.

---

## Prerequisites

Before using the bot, ensure the following tools/requirements are met:

- Node.js installed (version >= 14.0.0).
- A Sui blockchain network connection.
- API keys (as required by the Sui blockchain).
- Access to a compatible hosting environment (locally or in the cloud).

---

## Contact
For questions or suggestions, please reach out via the repository or telegram: [Telegram](https://t.me/shiny0103).

## Usage

- Once the bot is running, it will start tracking transaction volume on the Sui blockchain.
- Users can customize the bot's behavior by editing the configuration file located in the config directory.
- Alerts and logs will populate in the terminal or can be stored locally (based on configuration).

## 📋 Environment Variables

The bot uses the following environment variables. Rename the `.env.copy` file to `.env` and set the necessary variables.

```env
PRIVATE_KEY=

NETWORK=mainnet

RPC_ENDPOINT=https://rpc.ankr.com/sui/<RPC_API_KEY>
RPC_WEBSOCKET_ENDPOINT=wss://rpc.ankr.com/sui/ws/<RPC_API_KEY>

DISTRIBUTE_INTERVAL_MAX=30  # seconds
DISTRIBUTE_INTERVAL_MIN=20  # seconds

BUY_INTERVAL_MAX=10    # seconds
BUY_INTERVAL_MIN=5     # seconds

SWAP_AMOUNT_MAX=0.5   # SUI 
SWAP_AMOUNT_MIN=0.1   # SUI 

POOL_ID=0x1de5cc16141c21923bfca33db9bb6c604de5760e4498e75ecdfcf80d62fb5818
```

#  🚀 Usage
### 1. Clone the repository
```
git clone https://github.com/0xTan1319/Sui-Volume-Bot.git
cd Sui-Volume-Bot
```
### 2. Install dependencies
```
npm install
```
### 3. Configure the environment variables

Rename the .env.copy file to .env and set RPC and WSS, main keypair's secret key and other variables.

### 4. Run the bot

```
npm start
```


### 5. Gather the funds from distributed wallets

```
npm run gather
```
