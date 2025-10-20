# 💹 MACD Expert Advisor (MetaTrader 4)

This repository contains a custom-built **MACD Expert Advisor (EA)** for **MetaTrader 4 (MT4)** that automatically executes trades based on the **MACD Zero Line Crossover** strategy.  

The EA analyzes the MACD indicator and opens or closes trades when the MACD line crosses above or below the zero line — a well-known signal for bullish or bearish market momentum.

---

## ⚙️ Files Included

| File Name        | Description |
|------------------|-------------|
| `MACD EA.mq4`    | Source code file for the Expert Advisor (editable in MetaEditor). |
| `MACD EA.ex4`    | Compiled EA file (ready to be attached to MT4 charts). |

---

## 🚀 Features

- 📊 **Automatic Trading:** Opens and closes trades when MACD crosses the zero line.  
- ⚖️ **Trend Following:** Identifies bullish and bearish momentum automatically.  
- 🧠 **Customizable Inputs:** You can modify MACD parameters and trading lot sizes.  
- 💰 **Compatible with All Timeframes and Symbols.**  
- 🧩 **Simple Installation:** Just copy to your MT4 `Experts` folder and start trading.  

---

## 🛠️ Installation Guide

1. Open **MetaTrader 4**.  
2. Go to `File → Open Data Folder`.  
3. Navigate to:  MQL4 → Experts
4. Copy both files: 
MACD EA.mq4
MACD EA.ex4
5. Restart MT4 or refresh the **Navigator** panel.  
6. Drag **MACD EA** onto a chart.  
7. Enable **AutoTrading** (🔵 button on top of MT4).  

---

## ⚙️ EA Parameters (Example)

| Parameter | Description |
|------------|-------------|
| `LotSize` | Trade size per position |
| `TakeProfit` | Profit target in points |
| `StopLoss` | Stop loss in points |
| `MACDFastEMA` | Fast EMA period for MACD |
| `MACDSlowEMA` | Slow EMA period for MACD |
| `MACDSignalSMA` | Signal SMA period for MACD |

> You can modify these in the **Inputs** tab when attaching the EA to a chart.

---

## 🧠 Strategy Overview

- **Buy Signal:** MACD line crosses **above** the zero line → opens a **Buy** trade.  
- **Sell Signal:** MACD line crosses **below** the zero line → opens a **Sell** trade.  
- Optional filters (timeframe, spread, etc.) can be added for better performance.  

---

## 📈 Recommended Settings

| Symbol | Timeframe | Notes |
|---------|------------|-------|
| EURUSD  | H1 / H4 | Stable performance |
| GBPUSD  | H1 | Strong volatility response |
| USDJPY  | H1 | Good for backtesting |

> Always test the EA in **Strategy Tester** before using it on a live account.

---

## 🧪 Backtesting

To backtest:
1. In MT4, go to `View → Strategy Tester`.  
2. Select **MACD EA**.  
3. Choose a symbol (e.g., EURUSD) and timeframe.  
4. Run test and analyze performance metrics (profit factor, drawdown, etc.).  

---

## ⚠️ Disclaimer

This EA is provided **for educational and research purposes only**.  
Trading Forex involves significant risk of loss. Always test thoroughly before using on a live account.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and improve it.

---

## 👨‍💻 Author

Developed by **MahdiAttarzadeh**  
📬 Feel free to open issues or suggestions to improve performance.
