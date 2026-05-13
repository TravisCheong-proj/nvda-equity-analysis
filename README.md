# NVDA vs AAPL Equity Risk Analysis

## Overview
A 5-year comparative analysis of NVIDIA (NVDA) and Apple (AAPL) stock performance 
using the S&P 500 dataset (2013–2018). Combines technical analysis, machine learning, 
and institutional risk metrics to evaluate risk-adjusted returns.

## Key Findings
- NVDA delivered 1,749% total return vs AAPL's 135% over the same period
- NVDA Sharpe Ratio: 1.76 vs AAPL's 0.77 — superior risk-adjusted performance
- NVDA Max Drawdown: -25% vs AAPL's -32%
- Random Forest classifier (ROC-AUC: 0.51) confirmed technical indicators alone 
  have no statistically significant predictive power — consistent with EMH

## Tools & Techniques
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Feature engineering: RSI, Bollinger Bands, MA20/50, Rolling Volatility
- ML: Random Forest Classifier, Confusion Matrix, ROC-AUC evaluation
- Risk metrics: Sharpe Ratio, Value at Risk (95%), Max Drawdown
- Visualisation: Power BI interactive dashboard
