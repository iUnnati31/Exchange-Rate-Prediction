# Time Series Forecasting: Exchange Rate Prediction

## Overview
This repository contains code and documentation for a time series forecasting analysis of exchange rates. The analysis compares the performance of two models: ARIMA (AutoRegressive Integrated Moving Average) and Simple Exponential Smoothing (SES). The goal is to forecast exchange rates accurately using historical data.

## Data
The dataset used for this analysis contains daily exchange rate values from January 1, 1990, to October 10, 2010. Each data point includes a date and the corresponding exchange rate value.

## Analysis Steps
* Data Preprocessing: Cleaned the data, handled missing values, and ensured consistency in date formats.
* Exploratory Data Analysis: Visualized the data to understand trends, seasonality, and any patterns.
* Model Selection: Chose two models for comparison: ARIMA and Simple Exponential Smoothing (SES).
* Parameter Optimization: Tuned the parameters for each model using techniques like grid search or AIC.
* Model Fitting and Evaluation: Fit the models to the data and evaluated their performance using metrics like MAE, RMSE, and MAPE.
* Model Comparison: Compared the performance of ARIMA and SES models based on error metrics and insights from diagnostics.

## Requirements
* Python 3
* Jupyter Notebook
* Libraries: pandas, numpy, matplotlib, statsmodels, scikit-learn
  
## Results
* Both models performed similarly in terms of accuracy, with SES slightly outperforming ARIMA in terms of MAPE.
* The choice between models depends on the data characteristics and trade-offs between complexity and interpretability.

## Contributor 
Unnati Agarwal




