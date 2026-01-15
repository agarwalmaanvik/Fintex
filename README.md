# Fintex

## Project Overview
This repository contains a production-grade algorithmic trading system for **IRCON International** (IRCON.NS). The system uses a machine learning ensemble to predict directional price movements over a 5-day horizon and executes a volatility-adjusted strategy with strict risk controls.

## Repository Contents
- `notebook.ipynb`: The primary Jupyter Notebook containing the data pipeline, model training, and backtesting.
- `trade_journal.csv`: An automated audit log of every trade simulated during the backtest.
- `ircon.csv`: The primary dataset utilized (Nov-Dec 2025).

## Key Features
- **Soft-Voting Ensemble:** Combines non-linear (Random Forest) and linear (Logistic Regression) models for stable signal generation.
- **Dynamic Risk Management:** Implements ATR-based position sizing and a 1.5x ATR trailing stop-loss.
- **Capital Simulation:** Realistic backtest starting with an initial capital of **₹1,00,000**.
- **Audit Trail:** Automated generation of `trade_journal.csv` for every execution signal.

## Installation & Setup
1. **Environment:** Python 3.9+ 
2. **Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. **Clone the Repository:**
   ```bash
   git clone [https://github.com/agarwalmaanvik/Fintex.git](https://github.com/agarwalmaanvik/Fintex.git)
