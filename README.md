# Stock Price Modeling Using AR and MA Models

## 📌 Project Overview
Financial time series data such as stock prices exhibit strong temporal dependencies that cannot be effectively captured using simple trend-based analysis. This project focuses on modeling short-term stock price movements using **Autoregressive (AR)** and **Moving Average (MA)** models.

The objective is to understand the behavior of stock prices by leveraging historical values and past forecast errors, and to evaluate model performance using standard statistical diagnostics.

---

## 🎯 Objectives
- To analyze stock price time series data
- To understand and implement AR and MA models
- To select optimal lag values using ACF and PACF plots
- To evaluate model performance using AIC, BIC, and residual diagnostics
- To build a strong foundation for advanced forecasting models such as ARMA and ARIMA

---

## 🧠 Models Used
- **Autoregressive (AR) Model**
- **Moving Average (MA) Model**

Lag selection is performed using:
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)

---

## 🗂️ Dataset Description
- **Source:** Synthetic stock price dataset
- **Columns:**
  - `Date` – Trading date
  - `Close` – Closing stock price
- **Frequency:** Daily
- **Missing Values:** None

---

## ⚙️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

## 📈 Methodology
1. Load and preprocess the stock price dataset
2. Visualize time series behavior
3. Analyze stationarity and correlations
4. Plot ACF and PACF to determine lag order
5. Fit AR and MA models
6. Compare models using AIC and BIC
7. Perform residual diagnostics
8. Interpret results and conclusions

---

## ✅ Results
- AR and MA models successfully captured short-term dependencies
- Optimal lag selection improved model performance
- Residual diagnostics confirmed model adequacy
- The project demonstrates the effectiveness of classical time series models in financial analysis

---

## 🔍 Conclusion
This project highlights the importance of time series modeling in financial analytics. AR and MA models provide a solid statistical framework for understanding stock price movements and serve as a foundation for more advanced forecasting techniques.

---




