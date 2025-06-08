# alpha-engine
A backtesting system for SMA trading strategy with risk metrics and transaction costs.
# Alpha-Engine 🧠📈

**Systematic Backtesting Engine for SMA Strategy | AAPL 5-Year Historical Analysis**

---

## 📊 Overview

**Alpha-Engine** is a fully functional backtesting engine designed to evaluate systematic trading strategies using historical market data. This project focuses on a **Simple Moving Average (SMA) Crossover Strategy** and includes realistic market frictions such as transaction costs.

The engine was developed entirely in Python using `pandas`, `NumPy`, and `yfinance`.

---

## 💼 Project Background

This project was independently developed as part of my self-learning journey into quantitative finance. Although time series analysis and vectorised computing are part of my third-year university curriculum, I proactively taught myself these topics to build this tool ahead of schedule.

The engine was tested on **5 years of Apple Inc. (AAPL) stock data** from 2020 to 2023.

---

## ⚙️ Strategy Implemented

### Simple Moving Average (SMA) Crossover
- **Buy signal**: When fast SMA crosses above the slow SMA
- **Sell signal**: When fast SMA crosses below the slow SMA
- Position signals are shifted forward by one period to simulate realistic execution.

---

## 📈 Performance Metrics

The engine computes key performance indicators:

- **Cumulative Market Return**
- **Cumulative Strategy Return (Net of Costs)**
- **Sharpe Ratio**: –0.35  
- **Max Drawdown**: –69.41%
- **Transaction Cost Model**: Flat 0.1% per trade

---

## 📁 Files Included

- `alphaengine.py` – Main Python code for data collection, strategy logic, and backtesting
- `AlphaEngineReport.docx` – Full technical documentation with mathematical explanations
- `README.md` – This file

---

## 🧠 Skills Demonstrated

- Time Series Analysis  
- Strategy Backtesting  
- Vectorised Financial Computation  
- Performance and Risk Evaluation  
- Transaction Cost Modeling  
- Python for Quantitative Research

---

## 🚀 How to Run

1. Install requirements:
   ```bash
   pip install pandas numpy yfinance matplotlib.pyplot
