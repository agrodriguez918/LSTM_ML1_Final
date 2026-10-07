# LSTM_ML1_Final
Time-series forecasting project using LSTM neural networks to model F500 company trends in the stock market, with preprocessing, sequence generation, and model evaluation.


# Overview

This project demonstrates the use of Long Short-Term Memory (LSTM) neural networks as well as AutoRegressive Integrated Moving Average (ARIMA) for time-series forecasting. 

The project was inspired by a forecasting problem encountered during educational data analytics work and demonstrated the process of using historical operational data to identify trends and generate future predictions

The public version of this project uses non-proprietary data and does not contain confidential information. 

# Objective

The objective of the project is to develop a forecasting model capable of learning patterns from historical time series data and using those patterns to predict future values. 

The workflow focuses on : 

- Preparing time series data
- Identifying historical trends
- Creating sequences for neural network training
- Developing an LSTM model
- Comparing predictions against observed values
- Evaluating forecasting performance

# Modeling Workflow

Historical Data -> Data Cleaning -> Exploratory Analysis -> Feature Preparation -> Sequence Generation -> Baseline Forecast -> LSTM Model -> Training -> Forecasting -> Model Evaluation

# Why LSTM? 

LSTM networks are a type of recurrent neural network designed to learn patterns across sequential data. They are particularly useful for time series problems where previous observations may contain information that helps predict future observations. 

In this project, the LSTM model is evaluated against simpler forecasting approaches to determine whether additional complexity provides meaningful improvements. 

# Model Development 

The modeling process includes : 
1. Sorting observations chronologically. 
2. Cleaning and preparing the historical time series. 
3. Scaling numerical inputs when appropriate.
4. Creating rolling input sequences.
5. Splitting data using a time aware methodology.
6. Training the two models.
7. Generating predictions for future observations.
8. Comparing predictions against actual values.

# Baseline Comparison

A baseline model is included to provide a reference point for evaluating the models. 

Potential baseline approaches include : 
- Naive forecasting
- Moving averages
- Linear regression

Comparing against the baseline helps determine whether the additional complexity of the models provides meaningful predictive value. For this project I used both moving averages and linear regression.

#Evaluation

Model performance is evaluated using forecasting metrics such as : 

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
Visual comparisons between predicted and observed values are also used to evaluate model behavior.

# Results

The final results section will compare the LSTM and ARIMA models against the selected baseline models and evaluate its ability to capture historical trends and predict future observations. 

Example visualizations include : 
- Actual vs. predicted values
- Training and validation loss
- Forecast horizon
- Model error over time



