

# 🤖 Solana Copy Trading Bot 🚀  

**Effortlessly replicate trades on the Solana blockchain with this Copy Trading Bot!**  
This bot listens for swap transactions on the **Raydium AMM V4 Pools**, analyzes token data, and executes corresponding buy/sell operations based on predefined market strategies. Built with **Solana Web3** and **Jupiter Aggregator**, this bot enables automated, real-time trading to maximize opportunities.

---

## ✨ **Features**  

- 🔎 **Transaction Monitoring**: Tracks all token swaps on **Raydium AMM V4 Pools**.  
- 🤝 **Wallet Integration**: Supports monitoring of specific wallets to replicate their trades.  
- 💰 **Automated Trading**: Executes swaps with **Jupiter Aggregator** for optimal trade routing.  
- 💡 **Customizable Strategies**: Adjust trading limits, amounts, and behaviors to match your goals.  
- 🌐 **Real-Time Updates**: Leverages WebSocket for instant transaction insights.  
- 📈 **Market Data Fetching**: Retrieves token prices and metadata for informed trading decisions.  

---

## ⚙️ **Getting Started**

### 1. **Clone the Repository**  
```bash
git clone https://github.com/your-repo/solana-copy-trading-bot.git
cd solana-copy-trading-bot
```

### 2. **Install Dependencies**  
Make sure you have **Node.js** installed, then run:  
```bash
npm install
```

### 3. **Set Up Environment Variables**  
Create a `.env` file in the root directory with the following variables:  
```env
PRIVATE_KEY=your_wallet_private_key
```

### 4. **Adjust Configurations**  
Update settings in the `constants.ts` and `consts.ts` files to match your trading strategy, including:  
- **RPC endpoints** (`RPC_ENDPOINT`, `RPC_WEBSOCKET_ENDPOINT`)  
- **Wallet address** (`TARGET_WALLET`)  
- **Maximum trade amounts** (`MAXIMUM_BUY_AMOUNT`)  

### 5. **Start the Bot**  
Run the bot with:  
```bash
npm start
```

---

## 🛠️ **How It Works**

1. 📡 **WebSocket Connection**: Listens for transactions in real-time on the Solana blockchain via WebSocket.  
2. 🧩 **Transaction Parsing**: Filters and analyzes swap transactions for relevant token trades.  
3. 📊 **Market Evaluation**: Fetches token prices, metadata, and supply data for decision-making.  
4. 🔄 **Automated Execution**: Executes trades through the **Jupiter Aggregator** based on predefined conditions.  
5. 🔗 **Transaction Logging**: Logs all executed trades, with links to transaction explorers like **Solscan**.  

---

## 🧑‍💻 **Example Logs**

```text
Swap : USDC - SOL  
Amount : 100 USDC - 5.2 SOL  
Amount in USD : 100 $ - 200 $  
Tx : https://solscan.io/tx/abcd1234efgh5678  
```

---

## 🌟 **Customization Options**

- Adjust token tracking strategies in `utils/swapOnlyAmm.ts`.  
- Modify WebSocket filtering logic for more advanced trade replication.  
- Implement additional trading strategies to expand functionality.

---

## 🛡️ **Disclaimer**

This bot is intended for educational and research purposes. Use at your own risk, and ensure compliance with applicable laws and regulations.  

---

## 🤝 **Connect with the Developer**  

Have questions or need support? Reach out!  
- **Telegram**: [@g0drlc](https://t.me/rab_nail)

---

## 🔓 **License**

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

**Happy Trading! 🚀**  
