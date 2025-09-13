# finance-data-analysis

# Overview

This project performs a comparative analysis of stock data for **Tata Consultancy Services (TCS)** and **Reliance Industries** using Python and the `yfinance` library. The objective is to explore trends, understand historical performance, and apply basic descriptive statistics to derive actionable insights from stock market data.

# Tools & Technologies
- **Language:** Python
- **Libraries:** yfinance, pandas, matplotlib, seaborn
- **Platform:** Jupyter Notebook
- **Data Source:** Yahoo Finance API via `yfinance`
  
# Data Timeline
- **Start Date:** January 1, 2020
- **End Date:** July 24, 2025 (future-projected data from Yahoo Finance)

# Project Workflow

# Data Collection
- Fetched historical daily stock data for:
  - **TCS (TCS.NS)**
  - **Reliance (RELIANCE.NS)**
- Used `yfinance` to download adjusted stock data, including Open, High, Low, Close, and Volume.

# Data Preprocessing
- Checked for missing values
- Summarized dataset using `.describe()` and `.info()`

# Exploratory Data Analysis (EDA)
- Line plots for stock price trends
- Volume comparison over time
- Volatility comparison between TCS and Reliance
- Descriptive statistics comparison
