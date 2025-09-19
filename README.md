# Comparative Stock Performance Analysis: TCS vs. Reliance

This repository contains a Python-based analysis of the historical stock performance of two major companies listed on the National Stock Exchange of India (NSE): Tata Consultancy Services (TCS) and Reliance Industries. The project leverages the `yfinance` library to fetch live stock data and uses `pandas` and `matplotlib` for time-series analysis and visualization.

## Project Goal

The primary objective of this project is to download, analyze, and visualize historical stock data to compare the performance, volatility, and trends of TCS and Reliance. This involves:

  * Fetching historical market data from Yahoo Finance.
  * Analyzing key indicators such as closing price and trading volume.
  * Calculating and visualizing technical indicators like moving averages and daily returns.
  * Determining the correlation between the two stocks.

## Analysis and Key Findings

The analysis was conducted in the `finance_data_analysis.ipynb` Jupyter Notebook. The core steps and insights are outlined below.

### 1\. Historical Price and Volume Trends

  * **Closing Price:** The historical closing prices of both stocks were plotted over a specified date range to visualize their long-term growth and performance trajectories.
  * **Trading Volume:** An analysis of the daily trading volume was conducted to understand investor interest and the liquidity of the stocks over time.

### 2\. Technical Analysis

  * **Moving Averages (MA):** 50-day and 100-day moving averages were calculated and plotted against the closing price. This helps in smoothing out price fluctuations and identifying long-term trends and potential buy/sell signals.
      \* **Daily Returns & Volatility:** The daily percentage change in stock price was calculated to analyze the volatility. Histograms of the daily returns were plotted to show the distribution and risk profile of each stock. TCS, being an IT stock, might show different volatility patterns compared to the conglomerate structure of Reliance.

### 3\. Comparative Analysis

  * **Performance Comparison:** By plotting the closing prices and daily returns on the same axes, the analysis directly compares which stock offered better returns or exhibited higher volatility during specific periods.
  * **Correlation:** A heatmap was generated to visualize the correlation between the closing prices of TCS and Reliance. This indicates how likely the two stocks are to move in the same direction, which is a key consideration for portfolio diversification.

## Technologies Used

  * **Language:** Python
  * **Data Acquisition:** yfinance
  * **Data Manipulation & Analysis:** Pandas
  * **Data Visualization:** Matplotlib, Seaborn
  * **IDE:** Google Colab

