# 📈 Tesla Stock Price Forecasting & Volatility Analysis

This project explores the price dynamics and risk profile of **Tesla Inc. (TSLA)** using time-series forecasting and volatility modelling. It simulates the approach a **financial analyst or portfolio strategist** would take to understand, forecast, and act on the behaviour of a high-volatility stock.

---

## 📌 Objectives

- Forecast short-term Tesla stock prices using **ARIMA models**
- Model volatility clustering and risk dynamics using **GARCH(1,1)**
- Extract insights for **trading, risk management, and portfolio strategy**
- Demonstrate how **financial time-series models** inform decisions in high-growth, speculative assets

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy)
- Statsmodels (ARIMA)
- Arch (GARCH)
- Matplotlib, Seaborn
- Scikit-learn (StandardScaler)

---

## 🧪 Key Models Used

### 🔹 ARIMA (1,1,1)
- Captures short-term trends in log-scaled Tesla prices
- Well-suited to linear price evolution
- ❗Limitations: Assumes constant variance (unsuitable for TSLA volatility)

### 🔹 GARCH (1,1)
- Models time-varying volatility using past returns and shocks
- Captures volatility clustering — ideal for Tesla's high-risk profile
- Shows that **volatility is persistent but mean-reverting**

---

## 📊 Business Insights

- Tesla’s **explosive growth (2020–2021)** aligns with profitability, S&P 500 inclusion, and EV tailwinds.
- **ARIMA models** forecast price direction, but fail to reflect risk.
- **GARCH models** show how volatility spikes around earnings and macro shocks, then stabilises.
- Understanding both models helps analysts:
  - Time entries/exits
  - Set risk-adjusted positions
  - Prepare for volatility spikes

---


