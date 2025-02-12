# Sales-Forecasting

#Project 1-Sales Forecasting

## Overview
The main objective of this project (e.g., predicting sales based on historical data).
A brief explanation of the approaches used (VARMAX for multi-variable relationships, LSTM for complex time-series patterns).

i will predict with top 3 sales category on data set with LSTM and VARMAX. the sales category are, GROCERY with 5262681.66 total sales, BEVERAGES with 2533831.00 total sales, and CLEANING with 1667748.00 total sales

## Dataset
Data source.
Description of key features (date, sales, promotion, external variables).
Handling missing value and date.


## Tools & Technologies Used
Environment: Google Colab / Jupyter Notebook / Local Python Environment.
Modeling Tools:
VARMAX using statsmodels.tsa.statespace.varmax.VARMAX
LSTM using tensorflow.keras


## Data Preprocessing
Feature normalization / standardization.
Time transformations (lag features, differencing for VARMAX).
Splitting data into train and test sets.


## Model Development
VARMAX : Selecting optimal parameters (p, q), performance evaluation using MSE.
LSTM : Model architecture (number of layers, dropout, activation functions), hyperparameter with baynesian optimizer (optimizer, batch size, epochs)

## Model Evaluation & Comparison
Evaluation metrics: RMSE and MAE.
Visualization of predictions vs. actual values.
