# UDACITY-CAPSTONE-PROJECT


# Introduction
This repository provides a step by step analysis and forecasting model of aggregated data of retail store sales data.

Within the provided notebook we will first prepare the data so that they can be used by any forecasting model. We will then evaluate the performance of different forecasting models, starting with classic statistical SARIMA models up to Linear Regression and tree based models. For data processing, training and testing of the models a complete Time_Series_Model class will be provided which allows to qickly evaluate any specific model for time series.

# Dataset
The dataset covers includes more than 2 years of sales data of over 1000 retail stores. The complete dataset can be downloaded here:

https://drive.google.com/file/d/15_hqs9AVnEz8wNXY1rO4Dqn16nQTzEcL/view?usp=sharing

# Required Python modules
The notebook was created with Python 3.7

In order to execute all function in the provided notebook the following libraries are required:

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
