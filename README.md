# Airline Passenger Forecasting using SARIMA

## Overview
This project focuses on forecasting airline passenger demand using classical time-series forecasting techniques. The workflow includes Exploratory Data Analysis (EDA), stationarity testing, differencing, autocorrelation analysis, SARIMA modeling, and forecast evaluation.

The objective was to understand temporal patterns such as trend and seasonality and build a forecasting model capable of predicting future passenger counts accurately.

---

## Problem Statement
Forecast future airline passenger traffic using historical monthly passenger data while capturing:
- Long-term trends
- Seasonal behavior
- Temporal dependencies
- Variance changes over time

---

## Dataset
- Airline Passenger Dataset
- Monthly passenger counts from 1949 to 1960

---

## Concepts Implemented

### Exploratory Data Analysis (EDA)
- Trend analysis
- Seasonality detection
- Variance observation
- Rolling mean and rolling standard deviation

### Statistical Analysis
- Augmented Dickey-Fuller (ADF) Test
- Stationarity analysis
- Log transformation
- First differencing
- Seasonal differencing

### Time-Series Concepts
- Lag features
- Autocorrelation (ACF)
- Partial Autocorrelation (PACF)

### Forecasting Models
- ARIMA
- SARIMA

### Model Evaluation
- RMSE (Root Mean Squared Error)
- Residual analysis
- Forecast vs Actual comparison

---

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

---

## Key Learnings
- Understanding trend and seasonality in time-series data
- Why stationarity is important for ARIMA-family models
- Difference between ARIMA and SARIMA
- Importance of residual diagnostics
- Preventing data leakage using time-based train-test splitting

---

## Results
The SARIMA model successfully captured the seasonal structure of the dataset and generated forecasts closely aligned with actual passenger trends.

---

## Future Improvements
- Hyperparameter tuning
- Prophet and LSTM comparison
- Multivariate forecasting
- Production deployment using FastAPI
