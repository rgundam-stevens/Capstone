# Studying the Properties of Prices, Yields, and Volatility

This project explores the relationship between macroeconomic indicators and asset returns using advanced statistical techniques.  
It analyzes daily, weekly, and monthly data for key assets: **BTC (Bitcoin)**, **SPY (S&P 500 ETF)**, and **TLT (Treasury Bond ETF)**, alongside macroeconomic indicators such as **Inflation**, **GDP**, **Fed Funds Rate**, and **Unemployment Rate**.

---

## 📊 Project Overview

- Downloaded financial data from **Yahoo Finance** and macroeconomic data from **FRED**.
- Cleaned and preprocessed time series for missing values and stationarity.
- Performed exploratory data analysis (EDA), including:
  - Statistical summaries
  - Boxplots
  - Rolling volatilities
  - Correlations
- Conducted **outlier detection** using Z-scores.
- Analyzed **stationarity** of time series using **ADF tests**.
- Built models such as:
  - **Hidden Markov Models (HMM)** for regime detection
  - **Markov Switching Autoregressive (MSAR) Models**
  - **Vector Autoregression (VAR)** models
- Performed **Granger Causality Tests** to detect predictive relationships.

---

## 🛠️ Techniques Used

- Data Resampling and Imputation
- Hidden Markov Models (HMM)
- Markov Switching Models (MSAR)
- ADF Stationarity Tests
- Rolling Correlation and Volatility Analysis
- Granger Causality Analysis
- Vector Autoregression (VAR)
- Tail Risk Analysis (VaR & CVaR)

---

## 📦 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `yfinance`
- `pandas_datareader`
- `scipy`
- `statsmodels`
- `hmmlearn`
- `arch`
- `sklearn`
- `plotly`
- `dash`

---

## 📂 Project Files

| File | Description |
|:-----|:------------|
| `Capstone.ipynb` | Jupyter Notebook with full code, analysis, and visualizations |
| `market_data.xlsx` | Cleaned market data (SPY, TLT, BTC) |
| `macro_data.xlsx` | Cleaned macroeconomic data |

---

## 📈 Sample Visualizations

- Boxplots of daily prices
- Rolling 30-day volatility charts
- 90-day rolling correlations
- Hidden Markov regime switching plots
- Impulse Response Functions (IRFs) from VAR models

---

## 🚀 How to Run

1. Install the required packages:
   ```bash
   pip install numpy pandas matplotlib seaborn plotly dash yfinance statsmodels arch scikit-learn hmmlearn scipy pandas_datareader
   ```

2. Run `Capstone.ipynb` in a Jupyter environment (Google Colab / JupyterLab / VSCode).

---

## ✍️ Author

- **Your Name Here** *(optional)*

---

## 📌 Notes

- Some macroeconomic indicators like GDP have quarterly frequency and were resampled for consistency.
- The data used in this project spans from **April 2015** to **March 2025**.

---

> _This capstone demonstrates the application of time series modeling techniques to real-world financial and economic data._ 📊
