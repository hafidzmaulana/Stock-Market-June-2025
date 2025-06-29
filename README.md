
# Stock Market Analysis & Volatility Modeling (June 2025)

## Description
This project provides a comprehensive financial and volatility analysis of stock market data from June 2025. It explores key financial indicators, sector classifications, and risk assessments using price ranges and trading volumes. The goal is to support insights for investment strategy, risk profiling, and future stock recommendation systems.

---

## Dataset Overview

- **Source**: [Kaggle: pratyushpuri/stock-market-june-2025-dataset](https://www.kaggle.com/datasets/pratyushpuri/stock-market-june-2025-dataset)
- **Format**: CSV
- **Period**: June 2025 (Daily data)
- **Features**:
  - Date, Ticker, Sector
  - OHLC (Open, High, Low, Close)
  - Volume Traded, Market Cap
  - PE Ratio, Dividend Yield, EPS
  - 52-Week High/Low

---

## Objectives

- Perform **Financial Analysis**: P/E ratio, dividend yield
- Conduct **Technical Analysis**: Support and resistance levels
- Model **Volatility & Risk**: Based on price range and volume

---

## Key Analyses Performed

###  1. Financial Analysis
- P/E Ratio & Dividend Yield comparisons by sector
- Identify undervalued vs overvalued sectors

###  2. Technical Analysis
- Computation of support & resistance using 10-day rolling window
- Line charts for selected tickers

###  3. Volatility Modeling (Risk Assessment)
- Calculate daily volatility:  
  `Volatility = (High - Low) / Low * 100`
- Analyze average volatility and volume per ticker
- Visualize with scatter plot: **Volatility vs Volume**
- Identify most volatile tickers (top 10)

---

## Top 10 Most Volatile Stocks (June 2025)

| Ticker | Sector                 | Avg Volatility (%) | Avg Volume     |
|--------|------------------------|---------------------|----------------|
| MVG    | Financials             | 6.83                | 4,037,126      |
| HAY    | Utilities              | 6.76                | 12,423,800     |
| UVI    | Technology             | 6.75                | 3,886,906      |
| XVQ    | Materials              | 6.74                | 9,335,428      |
| BWK    | Consumer Discretionary | 6.69                | 6,721,266      |
| LVJ    | Financials             | 6.67                | 11,211,752     |
| MUK    | Industrials            | 6.66                | 14,728,577     |
| CWX    | Industrials            | 6.60                | 10,972,812     |
| WWY    | Utilities              | 6.59                | 2,944,997      |
| MRU    | Industrials            | 6.55                | 6,516,777      |

---

## Tools & Libraries Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Scikit-learn (for clustering, optional)
- Jupyter Notebook / Google Colab
