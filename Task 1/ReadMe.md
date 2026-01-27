# 📈 Task 1: ARIMA Stock Forecast (Streamlit + yfinance)

This project is a simple **Streamlit web app** that fetches live stock data using **yfinance** and generates a forecast using the **ARIMA model**.

You can enter any Yahoo Finance ticker (example: `RELIANCE.NS`, `^NSEI`, `AAPL`) and get:
- Historical closing price chart
- Historical prediction curve
- Future forecast for selected number of days
- Confidence interval band for forecast

---

## ✅ Features
- Live data fetching using **yfinance**
- ARIMA forecasting using **statsmodels**
- Adjustable ARIMA parameters: **p, d, q**
- Adjustable forecast horizon (3 to 14 days)
- Clean UI with sidebar inputs (ticker, history period, model params)

---

## 📂 File
- `app.py` → main Streamlit application  

---

## ⚙️ Requirements
- Python 3.9+
- Internet connection (for yfinance data)
 

```bash
pip install streamlit pandas yfinance matplotlib statsmodels

# 1) Install dependencies
pip install streamlit pandas yfinance matplotlib statsmodels

# 2) Run the Streamlit app
streamlit run app.py

# 3) Open the app in browser
# Streamlit will automatically open a local URL like:
# http://localhost:8501

# 4) Use the app
# - Enter a ticker in the sidebar (example: RELIANCE.NS / ^NSEI / AAPL)
# - Choose history period (6mo, 1y, 2y, 5y)
# - Set ARIMA parameters (p, d, q)
# - Select forecast days (3 to 14)
# - View charts and forecast output

# 5) Stop the app
# Press: CTRL + C
