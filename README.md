# 🧮 Options Backtesting – Seller Strategy with SL Modification

This project implements an intraday options selling strategy using historical data (BankNIFTY/NIFTY).  
Key highlights include dynamic stop-loss modification after entry based on % change from open price.

## 🚀 Strategy Logic

- Entry Time: **09:16 AM**
- Instrument: **ATM CE/PE**
- Side: **SELL**
- Stop Loss: **40%**
- SL Update: If option premium drops 10% from open, SL is updated accordingly

## 📊 Features

- PnL summary with trade logs
- Strategy visualization (line chart)
- Customizable entry/SL logic
- Handles real-time data in future version

## 🗃️ Files

| File | Description |
|------|-------------|
| `strategy_backtest.py` | Main backtesting logic |
| `data/sample_data.pkl` | Sample OHLC+OI data |
| `sample_output/backtest_results.png` | Visual output of performance |
| `notebooks/strategy_walkthrough.ipynb` | Jupyter breakdown of strategy |

## 📦 Tech Stack

- Python, Pandas, Matplotlib
- Pickle, datetime, numpy

## 📌 Sample Output

![Backtest Results](sample_output/backtest_results.png)

---

## 📬 Contact

Harshit Chawla  
[LinkedIn](https://www.linkedin.com/in/harsh56/) • [Email](mailto:hrshtchwl@gmail.com)
