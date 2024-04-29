# ARIMA Time Series Analysis for Cryptocurrency Volume Prediction

## Overview
This Python script uses the ARIMA (AutoRegressive Integrated Moving Average) model to analyze time series data of cryptocurrency trading volume and predict future values. It includes data loading, preprocessing, checking for stationarity, model fitting, prediction, evaluation, and printing of model performance metrics.

## Features
- **Data Loading and Preprocessing**: The script loads the dataset containing cryptocurrency trading volume, converts the date-time column to a datetime object, and sets it as the index.
- **Stationarity Check**: It performs the Augmented Dickey-Fuller test to check for stationarity in the time series data.
- **ACF and PACF Plotting**: The script plots the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) to determine the parameters for the ARIMA model.
- **ARIMA Model Fitting**: It fits an ARIMA model to the time series data with specified order parameters.
- **Prediction**: The script predicts the next value in the time series and calculates the Mean Absolute Error (MAE) between the predicted and actual values.
- **Model Performance Metrics**: It prints the Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) to assess the goodness-of-fit of the model.

## Usage
1. **Data Preparation**: Prepare a CSV file containing time series data of cryptocurrency trading volume.
2. **Data Loading**: Update the script to load your dataset and select the relevant column ('volume_true').
3. **ARIMA Model Configuration**: Adjust the ARIMA model order parameters (p, d, q) based on ACF and PACF plots.
4. **Model Fitting**: Run the script to fit the ARIMA model to the data and evaluate its performance.
5. **Prediction**: Specify the timestamp for which you want to make a prediction and run the script to forecast the next value.
6. **Model Evaluation**: Assess the model's performance using the Mean Absolute Error (MAE) and print AIC and BIC values.

## Dependencies
- pandas: Data manipulation library for handling time series data.
- numpy: Numerical computing library for array manipulation.
- statsmodels: Python module for conducting statistical tests and modeling time series data.
- scikit-learn: Machine learning library for evaluating model performance.
- matplotlib: Plotting library for data visualization.

## Note
- Ensure that your dataset contains a date-time column and the target variable ('volume_true').
- Experiment with different ARIMA model parameters to optimize model performance.
- This script is designed for analyzing and predicting cryptocurrency trading volume but can be adapted for other time series analysis tasks.

## Contact
For any inquiries or support, please contact [arman13m99@gmail.com].

