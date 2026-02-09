 Stock Price Modeling Using AR and MA Models

1. Project Overview
This project focuses on modeling short-term stock price behavior using classical time series techniques, specifically Autoregressive (AR) and Moving Average (MA) models. Financial time series data often exhibit temporal dependencies that traditional trend-based methods fail to capture. AR and MA models leverage historical price values and past error terms to analyze and forecast stock price movements effectively.
The project demonstrates the complete workflow of time series modeling, including data preprocessing, stationarity testing, lag selection, model building, and performance evaluation.


2. Problem Statement
Traditional statistical and trend-based approaches are inadequate for modeling stock price data due to its time-dependent and stochastic nature. Improper lag selection can lead to overfitting or weak predictive performance. Therefore, there is a need for robust time series models that:
- Capture temporal dependencies
- Utilize historical information efficiently
- Provide diagnostic measures to evaluate model quality

This project addresses these challenges using AR and MA models.


3. Objectives
The main objectives of this project are:
- To understand the fundamentals of time series analysis
- To analyze stock price data using AR and MA models
- To select optimal lag values using ACF and PACF plots
- To evaluate model performance using AIC, BIC, and residual diagnostics
- To perform short-term forecasting of stock prices


4. Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  
- Scikit-learn  
- Jupyter Notebook  


 5. Dataset Description
The dataset used in this project consists of historical daily stock closing prices. It contains the following columns:
- **Date**: Trading date  
- **Close**: Closing stock price  

The dataset is stored in CSV format and is placed inside the `data/` directory.


