# Crypto Prediction Platform

## Project Overview

This project is designed to predict cryptocurrency prices using machine learning models, including Prophet, XGBoost, ARIMA, LSTM, and Random Forest. It aims to assist traders and investors in making more informed decisions by forecasting the future price movements of cryptocurrencies.

## Technology Stack

- **Python**: Core programming language for model development and data processing.
- **BigQuery**: Data storage and querying for large datasets.
- **Pandas**: Data manipulation and analysis.
- **Machine Learning**: Implementation of various predictive models.
- **Looker Studio**: Data visualization and reporting.

## Models Used

- **Prophet**: A forecasting tool developed by Facebook, used for time-series prediction.
- **XGBoost**: A gradient boosting framework designed for speed and performance, especially with structured/tabular data.
- **ARIMA (AutoRegressive Integrated Moving Average)**: A classical statistical method for time-series forecasting.
- **LSTM (Long Short-Term Memory)**: A type of recurrent neural network (RNN) used to predict time-series data, especially for sequential patterns.
- **Random Forest**: A robust ensemble learning method used for classification and regression tasks, here applied to predict price trends.

## Data

The dataset used for training the models includes historical cryptocurrency prices, which are retrieved from reliable data sources like [insert data source name, e.g., CoinGecko, Binance]. The data is preprocessed and stored in BigQuery for efficient querying and model training.

## Installation Guide

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/crypto-prediction.git
As a group project, we analyzed crypto prices and macroeconomic indicators with Python to help investors make informed decisions. We used Prophet Model, XGBoost Model, SARIMA, LSTM, and Random Forest. We created an interactive Looker Studio dashboard.

Result:

Prophet was the most optimistic model, capturing long-term trends. The MAPE for SARIMA was 32.92%.

✅ SARIMA is very effective when working with time series: The model captures the seasonal patterns and trends in the data, making it reliable for time series forecasting.

✅ It can be used for forecasting trend lines: SARIMA excels in predicting the underlying trend in the time series, which is crucial for long-term forecasting.

✅ Comparing errors in predictions for highly volatile assets requires further tuning: While SARIMA can be useful, highly volatile assets like cryptocurrencies might require fine-tuning of the model’s parameters for more accurate forecasts.
