# 📈 Stock Price Analysis & Financial Indicators Project

A comprehensive **Exploratory Data Analysis (EDA) project** on historical stock prices of major companies using Python.  
This project analyzes **price trends, volatility, technical indicators, correlations, and market behavior** across multiple stocks.

---

## 🚀 Project Overview

This project performs deep financial data analysis on multiple companies including:

- 🍎 AAPL (Apple)
- 🚗 TSLA (Tesla)
- 🔍 GOOGL (Google)
- 💻 MSFT (Microsoft)
- 📦 AMZN (Amazon)
- 🏦 GS, JPM (Financial sector)
- 📊 IBM, GE, FB

It explores:
- Price movements
- Returns & volatility
- Technical indicators (RSI, MACD, ADX, CCI, ROC)
- Market correlation (S&P500, DJIA, QQQ)
- Trading volume behavior
- Trend analysis & momentum

---

## 📊 Key Features

### 📌 1. Descriptive Analysis
- Average closing prices
- Maximum stock prices
- Trading days per company

### 📌 2. Return Analysis
- Daily returns calculation
- Positive return frequency
- Stability comparison (standard deviation)

### 📌 3. Volatility Analysis
- Rolling volatility (20-day SD)
- High volatility detection
- Volatility trend comparison

### 📌 4. Technical Indicators
- RSI (Relative Strength Index)
- MACD signals
- ADX (Trend strength)
- CCI (Commodity Channel Index)
- ROC (Rate of Change)

### 📌 5. Market Behavior
- Correlation between companies
- Correlation with indices:
  - S&P 500
  - Dow Jones (DJIA)
  - NASDAQ (QQQ)

### 📌 6. Advanced Financial Insights
- Sharpe Ratio (risk-adjusted returns)
- Golden Cross detection (MA50 vs MA200)
- Recovery time after drawdowns
- Momentum persistence

---

## 🧠 Technologies Used

- 🐍 Python
- 📊 Pandas, NumPy
- 📉 Matplotlib, Seaborn
- 📓 Jupyter Notebook

---

## 📁 Project Structure

```

stock_price_prediction/
│
├── files/
│   ├── AAPL.csv
│   ├── TSLA.csv
│   ├── GOOGL.csv
│   └── ...
│
├── business.ipynb        # Main analysis notebook
├── README.md
└── requirements.txt

````

---

## ▶️ How to Run This Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/FazalElahi1/stock_price_prediction.git
cd stock_price_prediction
````

---

### 2️⃣ Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

---

### 3️⃣ Run notebook

```bash
jupyter notebook business.ipynb
```

---

## 📊 Sample Insights

* 📈 Tech stocks show stronger long-term upward trends than financial stocks
* ⚡ TSLA shows highest volatility among all companies
* 📊 MSFT and AAPL show strong correlation in price movement
* 📉 Volume has weak-to-moderate correlation with volatility
* 🧠 RSI and returns show weak predictive relationship overall market-wise

---

## 📌 Key Visualizations

* Stock price trends over time
* Moving averages (7-day, 30-day, 200-day)
* Correlation heatmaps
* Volume vs volatility analysis
* RSI vs Returns comparison
* MACD signal analysis
* Market index correlation

---

## 📈 Project Highlights

✔ Multi-stock comparison
✔ Technical indicator analysis
✔ Risk & return evaluation
✔ Market correlation study
✔ Advanced financial metrics

---

## 🚀 Future Improvements

* 🔥 Add LSTM / Deep Learning price prediction
* 🌐 Real-time stock API integration (Yahoo Finance / Alpha Vantage)
* 📊 Interactive dashboard (Streamlit / Plotly Dash)
* 📱 Web-based financial analytics tool
* ⚡ Portfolio optimization module

---

## 👨‍💻 Author

**Fazal Elahi**
📊 Data Science & Machine Learning Enthusiast
🔗 GitHub: [https://github.com/FazalElahi1](https://github.com/FazalElahi1)

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🚀 Share it

---

## 📄 License

This project is open-source and available under the MIT License.

```
