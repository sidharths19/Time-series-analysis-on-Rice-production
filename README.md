# Rice-time-series-analysis
Time series analysis of rice production data with a focus on seasonal patterns (Kharif and Rabi) and forecasting using exponential smoothing methods in Python.

## 📌 Project Overview
This project analyzes rice production data using time series techniques.
The objective is to understand trends, seasonality, and forecast future production
using exponential smoothing methods.

## 📂 Dataset
- Source: UPag Portal(All India crop-wise production data)
- Frequency: Seasonal (Kharif & Rabi)
- Time period: 1966–2025

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Statsmodels

## 🔄 Project Workflow
1. Data cleaning and restructuring
2. Time index creation (season-wise)
3. Exploratory data analysis
4. Trend and seasonality visualization
5. Forecasting using 3 Exponential Smoothing

## 📈 Methods Used
- Time series decomposition
- Differencing
- Single / Double / Triple Exponential Smoothing

## ✅ Key Observations
- Rice production increase is mostly yield-driven not area driven 
- Impact of Green Revolution (1970-80), National food secuirity mission(2007), technology innovation and mechanisation is visible from the graph.
- Seasonal differencing is must if considering both season (kharif and Rabi)
- Holt winters method is succesfull in capturing trend and seasonality for predicting future values

## 🚀 How to Run
1. Clone the repository
2. Install required libraries
3. For Exponential Smoothing
     Run notebooks in the order:
      1. data preparation
      2. exponential smoothing
4. For converting series to stationary
     run in the order
      1. data preparation
      2. data visualisation
   
## 📌 Future Improvements
- ARIMA / SARIMA models
- Model comparison using RMSE
- State-wise analysis
