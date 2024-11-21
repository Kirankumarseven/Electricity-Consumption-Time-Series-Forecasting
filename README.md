# Electricity Consumption Forecasting for February 2017
## Project Overview
This project aims to forecast the electricity consumption for the first three days (72 hours) of February 2017 for PowerConsumption_Zone1, based on historical data from January 2017. The goal is to predict future electricity consumption, helping optimize energy supply planning. To achieve this, we train two different models—Linear Regression and Facebook Prophet—and compare their performance in terms of accuracy and reliability.

## Dataset
The dataset used in this project contains historical electricity consumption data for PowerConsumption_Zone1. Key features of the dataset include:

Datetime: Timestamp for each observation
PowerConsumption_Zone1: Electricity consumption (kWh) for Zone 1

## Key Steps
Data Exploration and Preprocessing:

Line charts and decomposition techniques are used to explore the electricity consumption patterns in January 2017.
Identify seasonality, trends, and outliers within the data.
Clean and preprocess the data (handling missing values, scaling, etc.).
Model Training:

Linear Regression: Train a Linear Regression model on the data from January 2017 to predict electricity consumption for the first 72 hours of February 2017.
Facebook Prophet: Train a Facebook Prophet model, a time-series forecasting model that can capture daily, weekly, and yearly seasonality, to predict future consumption.
Model Evaluation:

Both models' predictions are compared to actual consumption datausing visual plots (predicted vs. actual values).
Accuracy is measured using Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).
