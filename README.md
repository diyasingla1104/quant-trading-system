# Quantitative Trading Strategy System

## Project Overview
This project builds a complete quantitative trading system for the **spot market** using:
- Data acquisition
- Data cleaning
- Feature engineering
- Regime detection
- Strategy backtesting
- Machine learning
- Outlier analysis

## Project Structure
- `data/` : Raw CSV files
- `notebooks/` : Jupyter notebooks for each step
- `src/` : Python modules (utils, strategy, backtest, models)
- `models/` : Saved ML models
- `results/` : Output files (backtest results, trades)
- `plots/` : Visualizations
- `requirements.txt` : Required Python packages

## Installation
```bash
pip install -r requirements.txt

How to Run
Run notebooks in order from 1 to 7
Or run Python modules:
python src/main.py

Key Results Summary
Total Trades: 319
Outliers: 7 (2.19%)
Avg PnL (Outliers): 0.0084
Avg PnL (Normal): -0.0002
Model Accuracy: 73% (baseline)
