# Primetrade.ai internship

# Trader Behavior Insights — Sentiment vs PnL Analysis  
_A Data Science Case Study by Priyambada Das_

This repository contains my submission for the **Junior Data Scientist – Trader Behavior Insights** assignment.  
The project analyzes whether daily market sentiment influences trading performance and evaluates if sentiment can be used as a predictive signal for PnL or trader behavior.

---

## 📁 Project Structure

``` ds_priyambada/
```│
├── notebook_1.ipynb # Data cleaning, merging, daily summary creation
├── notebook_2.ipynb # Visualizations, modeling, backtesting
│
├── csv_files/
│ ├── historical_data.csv
│ ├── fear_greed_index.csv
│ ├── daily_trade_sentiment_summary.csv
│ ├── daily_trade_sentiment_summary_v2.csv
│ └── toy_strategy_sentiment.csv
│
├── outputs/
│ ├── pnl_vs_sentiment.png
│ ├── boxplot_sentiment_pnl.png
│ ├── lag_correlation.png
│ ├── correlation_heatmap.png
│ ├── feature_importance.png
│ ├── smoothed_trends.png
│ └── toy_backtest_sentiment.png
│
└── ds_report.pdf # Final written report
```


---

## 🎯 Objective

The core question driving this project:

**Does daily market sentiment (Fear–Greed Index) influence or predict daily trading PnL?**

To explore this, the analysis includes:

- Data cleaning & preprocessing  
- Daily aggregation of trading behavior  
- Sentiment–PnL visual analysis  
- Lag correlation testing  
- Feature importance modeling  
- A simple rule-based sentiment trading strategy  

---

## 🛠️ Notebooks Overview

### 📌 Notebook 1 — Data Preparation & Core EDA
- Cleaning and transforming raw trade data  
- Merging sentiment classification  
- Creating daily metrics (total_pnl, avg_pnl, win_rate, trade_count)  
- Generating the main summary dataset  
- Plotting PnL vs sentiment  
- Boxplot of PnL distribution by sentiment  

### 📌 Notebook 2 — Advanced Analysis & Strategy Evaluation
- Smoothed trends (7-day moving averages)  
- Correlation heatmap (PnL, sentiment, volatility, trade count)  
- Lag correlation analysis (−30 to +30 days)  
- RandomForest feature importance visualization  
- Toy sentiment-based backtest strategy  

---

## 📊 Key Insights

- Sentiment does **not** strongly correlate with daily PnL.  
- Lag analysis showed **no predictive relationship** between sentiment and PnL.  
- RandomForest modeling revealed that **trade-related metrics** (trade count, average PnL, volatility) explain PnL far more than sentiment.  
- A simple sentiment-based rule **did not outperform** a baseline buy-and-hold strategy.  
- Sentiment should be treated as a **contextual or supplementary feature**, not a standalone signal.

---

## 📄 Report

A complete explanation of methodology, visualizations, and insights is available in:

**👉 ds_report.pdf**

---

## 🌐 Blog Article (Medium)

Full narrative write-up of the entire analysis:

**👉 (https://medium.com/@priyamdas197/does-market-sentiment-really-influence-trading-performance-2de2188e0496)**

---


---

## 👤 Author

**Priyambada Das**  


