# UDACITY-CAPSTONE-PROJECT


# Project Summary
This repository provides a step by step analysis and forecasting model of aggregated data of retail store sales data. Target of this project is to provide a generic approach for data wrangling and forecast of time series. The provided functions and class can be easily used for any time series data set

Within the provided notebook we will first prepare the data so that they can be used by any forecasting model. We will then evaluate the performance of different forecasting models, starting with classic statistical SARIMA models up to Linear Regression and tree based models. For data processing, training and testing of the models a complete Time_Series_Model class will be provided which allows to qickly evaluate any specific model for time series.

After comparison different models with basic parameters, the best model is elected and further tuned to get better prediction results.

All the functions provided cover the forecasting of aggregated data. At the end of the Notebook you can find the preparation steps in order to perform individual forecasts for each retail store. This could be covered in a second phase of the project. 

# Dataset and Files
The dataset covers includes more than 2 years of sales data of over 1000 retail stores. The complete dataset can be downloaded here:

https://drive.google.com/file/d/15_hqs9AVnEz8wNXY1rO4Dqn16nQTzEcL/view?usp=sharing

The complete code is provided within on notebook and should run without any adjustments when the file is stored in the working directory.

# Required Python modules
The notebook was created with Python 3.7

In order to execute all function in the provided notebook the following modules have to be imported:

- from math import sqrt
- from warnings import catch_warnings
- from warnings import filterwarnings
- from statsmodels.tsa.statespace.sarimax import SARIMAX
- from sklearn.linear_model import LinearRegression
- from sklearn.ensemble import RandomForestRegressor
- import xgboost as xgb
- from math import sqrt
- from sklearn.metrics import mean_squared_error
- from sklearn.preprocessing import MinMaxScaler
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import pmdarima as pm
- from pmdarima import model_selection
- import matplotlib.dates as mdates
- from datetime import timedelta
- from tqdm import tqdm
- pd.options.mode.chained_assignment = None 


# Blog post on MEDIUM
You can find a summary of this project in my blog post on MEDIUM with the following link:

xxxxxxx
