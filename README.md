Overview
This repository contains the implementation and analysis of a project that forecasts Walmart's quarterly revenue using time series forecasting techniques. The project evaluates three distinct models: ARIMA, LSTM, and a hybrid ARIMA-LSTM model, comparing their effectiveness using multiple metrics such as RMSE, MAE, and MAPE.

Objectives
Accurately forecast Walmart's revenue for the next six quarters (Q3 2023 to Q4 2024).
Compare the performance of ARIMA, LSTM, and a hybrid ARIMA-LSTM model.
Demonstrate how combining traditional statistical models with neural networks can enhance predictive accuracy.
Analyze the impact of exogenous variables such as GDP, unemployment rate, and industrial production on revenue forecasting.

Key Features
Data Preparation:
Cleaning, normalization, and integration of exogenous variables.
Forecasting exogenous variables using ARIMA to extend the dataset.

ARIMA Modelling:
Identified and captured linear trends and seasonality in the data.
Used ACF and PACF plots to determine model parameters.

LSTM Modelling:
Designed to capture non-linear dependencies and long-term temporal patterns.
Utilized a multi-layer architecture with dropout layers for robust training.

Hybrid Modelling:
Combined ARIMA's linear trend capabilities with LSTM's non-linear pattern recognition.
Forecasted residuals from ARIMA using LSTM to refine predictions.

Evaluation Metrics:
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
Mean Absolute Percentage Error (MAPE)

Results:
The hybrid model outperformed both ARIMA and LSTM, achieving the lowest error rates across all metrics.
The hybrid approach demonstrated the benefits of integrating statistical and machine learning methods.
