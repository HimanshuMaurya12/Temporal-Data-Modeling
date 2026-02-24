# Temporal-Data-Modeling
A comprehensive repository exploring predictive modeling for temporal data. Includes statistical foundations (ARIMA, SARIMAX) and advanced Deep Learning implementations for time series forecasting.

# Applied Time Series Analysis & Forecasting

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Statsmodels](https://img.shields.io/badge/Library-Statsmodels-red)
![Deep Learning](https://img.shields.io/badge/Domain-Deep_Learning-orange)
![License](https://img.shields.io/badge/Code_License-MIT-green)

A structured collection of forecasting models and temporal data analysis techniques. This repository covers the mathematical foundations of time series analysis, moving from classical statistical methods to modern deep learning architectures.

## 📌 Project Overview
Forecasting future trends based on historical data is a critical component of predictive analytics in finance, economics, and system monitoring. This repository is divided into three core focus areas to demonstrate a complete progression of time series skills:

### 1. Statistical Foundations
Explores the fundamental properties of time series data and core autoregressive models.
* **Concepts Covered:** Trend extraction, Seasonality, Stationarity (Augmented Dickey-Fuller tests), Autocorrelation (ACF/PACF), and Differencing.
* **Models Implemented:** AR (Autoregressive), MA (Moving Average), ARMA, and ARIMA.

### 2. SARIMAX Airline Forecasting
An end-to-end case study utilizing the classic International Airline Passengers dataset. 
* **Implementation:** Decomposes the time series to handle complex seasonal trends.
* **Model:** Implements a Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors `SARIMAX(2, 1, 2)x(1, 1, [1], 12)`.

### 3. Deep Learning for Time Series
Transitions from statistical mathematics to neural network-based forecasting.
* **Implementation:** Benchmarks the performance of Deep Learning models on synthetic temporal datasets to handle non-linear forecasting challenges.

## 📁 Repository Structure
```text
├── SARIMAX-Airline-Forecasting/   # Real-world dataset forecasting
├── Deep-Learning-Time-Series/     # Neural network implementations
├── Statistical-Foundations/       # Core ARIMA/Math concepts
└── docs/                          # Detailed lab records and assignment PDFs
