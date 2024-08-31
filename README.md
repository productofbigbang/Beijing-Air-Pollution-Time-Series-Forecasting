

# Air Pollution Forecasting

This project focuses on forecasting air pollution levels using various time series analysis and machine learning techniques.

## Overview

The project analyzes a dataset of air pollution measurements along with related meteorological factors. It implements and compares several forecasting models:

- Simple Exponential Smoothing
- Autoregression (AR)
- Moving Average (MA)
- ARIMA
- SARIMA
- LSTM (Long Short-Term Memory) neural network

## Dataset

The dataset (`air_pollution.csv`) contains daily measurements of:

- Pollution levels
- Dew point
- Temperature
- Pressure
- Wind speed
- Snow
- Rain

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn
- tensorflow
- pmdarima

## Key Features

- Data preprocessing and exploratory data analysis
- Time series decomposition and stationarity testing
- Implementation of various forecasting models
- Model comparison using RMSE (Root Mean Square Error)
- Visualization of predictions vs. actual values

## Usage

1. Ensure all required libraries are installed
2. Load the dataset and run the preprocessing steps
3. Execute each model section to generate forecasts
4. Compare model performances using RMSE values and visualizations

## Results

The project compares the performance of different models:

- Simple Exponential Smoothing RMSE: 74.51
- Autoregression (AR) RMSE: 64.65
- Moving Average (MA) RMSE: 64.98
- ARIMA RMSE: 64.61
- SARIMA RMSE: 71.38
- LSTM RMSE: 24.92

The LSTM model appears to perform best, achieving the lowest RMSE of 24.92.

## Future Work

- Fine-tune model hyperparameters
- Explore ensemble methods
- Incorporate additional relevant features
- Implement real-time forecasting capabilities

