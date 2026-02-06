# 📈 Stock Price Modeling Using AR & MA Models

## 📌 Project Overview
This project focuses on modeling short-term stock price behavior using classical time series techniques such as Autoregressive (AR), Moving Average (MA), and ARMA models. Traditional trend-based methods often fail to capture temporal dependencies present in financial data. Hence, this project applies statistical time series models to analyze historical stock prices and generate reliable forecasts.

Tesla (TSLA) stock data is used for experimentation and model validation.

---

## 🎯 Objectives
- Analyze stock price movements using time series techniques
- Convert non-stationary stock prices into stationary returns
- Identify optimal lag values using ACF and PACF plots
- Build AR, MA, and ARMA models
- Compare models using AIC, BIC, and MSE
- Perform residual diagnostics
- Forecast future stock returns

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Scikit-learn

---

## 📂 Dataset
- Tesla (TSLA) historical stock prices
- Source: Yahoo Finance
- Columns include:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Load CSV dataset
- Handle dates and indexing
- Convert prices to returns
- Perform stationarity check using ADF test

### 2. Time Series Analysis
- ACF plot for MA lag identification
- PACF plot for AR lag identification

### 3. Model Building
- AR(p)
- MA(q)
- ARMA(p,q)

### 4. Model Evaluation
- AIC
- BIC
- Mean Squared Error (MSE)
- Residual diagnostics

### 5. Forecasting
- Train-test split
- Predict future returns
- Compare predicted vs actual values

---

## ▶️ How to Run

### Install dependencies
```bash
pip install -r requirements.txt
