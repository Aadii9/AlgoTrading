#  Momentum-Based Algorithmic Trading for Bitcoin

This repository contains Python scripts and notebooks for developing and testing momentum-based algorithmic trading strategies on Bitcoin. The goal is to build a robust and modular system that evolves from classical technical indicators to advanced deep learning models.

##  Project Overview

The idea is simple: capture **momentum** in Bitcoin price movements using various methods, starting from technical indicators like Bollinger Bands and gradually integrating more sophisticated tools like LSTM neural networks.

###  Completed Modules
- **Bollinger Bands Strategy**: Entry/exit rules based on price deviations from the moving average.

###  Coming Soon
- LSTM-based trend prediction
- Moving Average Convergence Divergence (MACD)
- RSI + Bollinger Band hybrid strategy
- Walk-forward validation framework
- Streamlit dashboard (for interactive visualization)

---

## 📊 Data Source

- [CoinGecko API](https://www.coingecko.com/en/api) – for historical BTC price and volume data.

---

## 🛠️ Tech Stack

- **Python 3.10+**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `torch`/`tensorflow` (for ML models)
- `requests` (API fetching)
- `jupyter` notebooks for experiments

---


