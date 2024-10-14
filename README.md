# TSLA Stock Price Forecasting with ARIMA Model

## Overview
This project focuses on forecasting the closing price of TSLA stock using an ARIMA (AutoRegressive Integrated Moving Average) model. It includes data preprocessing, exploratory data analysis, model fitting, and performance evaluation. The project also explores the challenges of using ARIMA for stock price prediction, particularly in the stock market where volatility is high. 

## Project Motivation
Stock market prices, particularly for high-profile stocks like TSLA, are difficult to predict due to a multitude of internal and external factors influencing price movements. The goal of this project is to apply time series forecasting using ARIMA to predict TSLA's closing price and evaluate the limitations and challenges encountered with such models in financial markets.

## Dataset
The dataset used for this project was sourced from Yahoo Finance, containing daily closing prices of TSLA stock. The time period covered is from **March 20, 2019** to **March 20, 2024**.

### Features:
- **Date**: Date of the stock price entry.
- **Close**: The closing price of TSLA on each date.

The data has been preprocessed to ensure cleanliness before model fitting, including handling missing values and scaling.

## Results
The ARIMA model was fitted to the TSLA stock data, but the forecast plot appeared as a straight line, indicating that the model struggled to capture the stock price volatility. The model’s metrics such as RMSE, MAE, and MAPE reflected suboptimal performance, pointing towards the need for alternative approaches or further model refinement.

| Metric  | Value  |
|---------|--------|
| **ME**  | -38.78 |
| **RMSE**| 48.88  |
| **MAE** | 39.97  |
| **MPE** | -18.90 |
| **MAPE**| 19.32% |

## Future Work
The following steps could improve the model and the project's scope:

- Investigating alternative time series models such as **SARIMA**, **GARCH**, or **LSTM** to capture stock market volatility.
- Incorporating external factors (e.g., financial indicators, news sentiment) that influence stock prices.
- Exploring hybrid models that combine machine learning techniques with traditional time series forecasting methods.

