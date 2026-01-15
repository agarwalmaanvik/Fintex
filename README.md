# Fintex

## Project Overview
This repository contains a production-grade algorithmic trading system for **IRCON International** (IRCON.NS). The system uses a machine learning ensemble to predict directional price movements over a 5-day horizon and executes a volatility-adjusted strategy with strict risk controls.

## Repository Contents
- `finstreet_strategy.ipynb`: The primary Jupyter Notebook containing the data pipeline, model training, and backtesting.
- `trade_journal.csv`: An automated audit log of every trade simulated during the backtest.
- `ircon.csv`: The primary dataset utilized (Nov-Dec 2025).

## Installation & Setup
1. **Environment:** Python 3.9+ 
2. **Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
