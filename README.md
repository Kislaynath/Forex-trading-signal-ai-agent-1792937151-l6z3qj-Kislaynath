## Forex Trading Signal AI Agent

An AI-assisted quantitative Forex analysis project combining technical indicators, machine learning, reinforcement learning, risk analytics, and Power BI business intelligence.

## 📌 Project Overview

This project explores a research prototype for analyzing Forex market data and generating rule-based trading signals. It integrates exploratory data analysis, technical indicators, backtesting, predictive modeling, risk measurement, and interactive business intelligence dashboards.

The current dataset contains approximately 500 hourly EUR/USD observations. Results are experimental and limited by the dataset's size and coverage.

## 🎯 Objectives

- Analyze Forex price movements and market behavior.
- Generate BUY, SELL, and HOLD signals using technical indicators.
- Explore machine learning approaches for market prediction.
- Implement reinforcement learning trading-environment experiments.
- Evaluate risk using Value at Risk (VaR), Conditional Value at Risk (CVaR), and Monte Carlo simulation.
- Present analytical results through Power BI and an R Shiny prototype.

## 🛠️ Technology Stack

# - Programming: Python, R
# - Data analysis: Pandas, NumPy, tidyverse
# - Machine learning: Scikit-learn, Random Forest, XGBoost, LSTM
# - Reinforcement learning: PPO, DQN
# - Risk analytics: Historical VaR, Parametric VaR, Monte Carlo VaR, CVaR
# - Visualization: Matplotlib, Seaborn, ggplot2
# - Business intelligence: Microsoft Power BI, DAX, DAX Studio
# - Validation: Excel

## ⚙️ Key Features

## 1. Exploratory Data Analysis

- Forex price and volume analysis
- Data-quality checks
- Time-based market exploration

## 2. Technical Signal Generation

The rule-based signal engine combines:

- Simple Moving Average (SMA)
- Exponential Moving Average (EMA)
- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)
- Bollinger Bands
- Ichimoku indicators
- Average True Range (ATR)

The configured engine classifies observations as BUY, SELL, or HOLD according to a weighted indicator score.

## 3. Backtesting

A backtesting component explores historical strategy behavior. Backtest results should be interpreted cautiously because transaction costs, execution assumptions, and the limited dataset can affect performance.

## 4. Machine Learning

The project explores Random Forest, XGBoost, and LSTM approaches, with time-series validation and feature-analysis techniques.

## 5. Reinforcement Learning

PPO and DQN experiments explore how an agent might make decisions within a trading environment. These experiments are research prototypes, not evidence of a production-ready autonomous trading system.

## 6. Risk Management

- Historical Value at Risk (VaR)
- Parametric VaR
- Monte Carlo VaR
- Conditional Value at Risk (CVaR)
- Kelly and Half-Kelly position-sizing concepts

## 7. Business Intelligence

The Power BI report includes six analytical pages:

1. Signal Overview
2. Risk Management
3. Pair Analysis
4. Session Heatmap
5. Monte Carlo & VaR
6. Strategy Comparison

The project also includes DAX measures, DAX Studio validation queries, Excel validation files, and an R Shiny dashboard prototype.

## 📊 Dataset and Signal Summary

The current signal-engine output contains 500 observations:

Signal| Count
BUY| 246
SELL| 143
HOLD| 111
Total| 500

These counts describe the generated signals; they do not demonstrate trading profitability or predictive accuracy.

## 📁 Repository Contents

File| Description
"Project_2_dashboard.pbix"| Power BI dashboard
"Forex_Trading_Signal_AI_Agent_Report.pdf"| Final project report
"Excel_Validation.xlsx"| Excel validation workbook
"bond_portfolio_data.csv"| Bond portfolio data
"monte_carlo_scenarios.csv"| Monte Carlo scenario data
"yield_curve_history.csv"| Yield curve history
"Query1.dax"| DAX query
"README.md"| Project documentation

## Additional diagnostic files are included in the repository.

## 🚀 Getting Started

1. Clone or download this repository.
2. Install Python and the required packages for the relevant analysis notebooks or scripts.
3. Review the project report for methodology and implementation details.
4. Open "Project_2_dashboard.pbix" using Microsoft Power BI Desktop.
5. If Power BI requests data-source paths, update them to match your local environment.

A complete reproducible setup requires the corresponding source code, dependency list, and dataset files.

## ⚠️ Limitations

- The current dataset covers approximately 500 hourly EUR/USD observations.
- The dataset does not support reliable multi-pair comparison or broad market generalization.
- Experimental model results should not be interpreted as proof of future predictive performance.
- Backtesting and reinforcement learning results depend on their implementation and evaluation assumptions.
- This project is a research and educational prototype, not a financial advisory service or live trading system.

## 🔮 Future Improvements

- Expand the dataset across multiple currency pairs and market regimes.
- Add a reproducible Python environment and dependency file.
- Strengthen walk-forward validation and out-of-sample testing.
- Improve transaction-cost, slippage, and position-management assumptions.
- Add automated tests and reproducible model evaluation.
- Improve dashboard documentation and deployment.

## 👨‍💻 Author

## Kishlay Nath Tiwari

## Integrated B.Sc. IT — Software & Mobile Application Development

📄 Disclaimer

This project is intended for educational and research purposes only. It does not constitute financial advice or a recommendation to buy or sell any financial instrument. Historical and simulated results do not guarantee future performance.
