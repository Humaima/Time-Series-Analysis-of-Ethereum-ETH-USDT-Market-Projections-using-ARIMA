# Ethereum (ETH) Price Forecasting with ARIMA  

## **🔍 Overview**  
Time series analysis of ETH/USDT prices (2020-2023) using ARIMA to forecast trends.  

## **🚀 Key Features**  
- **Data**: Fetched from Yahoo Finance (`yfinance`).  
- **EDA**: Price trends, volatility, and stationarity checks.  
- **Model**: ARIMA(2,2,3) with **RMSE: 808.12**, **MAPE: 57.34%**.  
- **Forecast**: 30-day predictions with confidence intervals.  

## **⚙️ Setup**  
1. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  # pandas, numpy, yfinance, statsmodels
2. Run Jupyter notebook:
   ```bash
   jupyter notebook ETH_ARIMA_Forecasting.ipynb
## **📈 Results**
![image](https://github.com/user-attachments/assets/5c38d04b-ce03-45e4-bb24-03a217cb8007)
Fig 1: Dataset Overview
![image](https://github.com/user-attachments/assets/c31a7b41-68a3-420e-86d0-f3b2b56d28e9)
Fig 2: ETH Price Trends Graph
![image](https://github.com/user-attachments/assets/e137f772-9e0e-44c8-ba47-269e882ceb05)
Fig 3: Graph of Actual vs. Predicted Prices
![image](https://github.com/user-attachments/assets/a2640312-6551-4007-8b35-c1e7ad349b91)
Fig 4: 30-days Forecast of ETH/USDT

## **📌 Notes**
- **Limitation**: High MAPE due to crypto volatility.
- **Improvement**: Hybrid models (ARIMA-GARCH/LSTM) recommended.

## **📧 Contact: humaimaanwar123@gmail.com**

