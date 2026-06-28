# Week 2 – Machine Learning Pipeline & Time Series Forecasting

## Overview

This project demonstrates a complete Machine Learning pipeline starting from data inspection and preprocessing through model development and ending with Time Series Forecasting. The analysis uses a Tesla Deliveries and Production dataset to predict estimated deliveries and forecast future trends.

---

## Objectives

* Inspect and understand the dataset.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Engineer features for machine learning.
* Train and evaluate regression models.
* Perform Time Series Analysis.
* Test stationarity using the Augmented Dickey-Fuller (ADF) Test.
* Forecast future deliveries using Exponential Smoothing.

---

## Dataset

The dataset contains information related to Tesla vehicle production and deliveries, including manufacturing, pricing, region, and estimated deliveries.

### Dataset Summary

* Total Records: **2,640**
* Numerical and categorical features
* No missing values
* No duplicate records

---

## Project Workflow

### 1. Dataset Inspection

* Loaded the dataset
* Examined data structure
* Verified data types
* Generated descriptive statistics

### 2. Data Cleaning

* Checked missing values
* Removed duplicate records
* Verified data consistency
* Confirmed correct data types

### 3. Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation analysis
* Scatter plots
* Box plots
* Category-wise visualizations

### 4. Feature Engineering

* Selected input and target variables
* Encoded categorical variables
* Prepared numerical features
* Created train-test split

### 5. Regression Modeling

Models implemented:

* Linear Regression
* Random Forest Regressor
* Optimized Random Forest (GridSearchCV)

Evaluation metrics include:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Time Series Forecasting

* Monthly aggregation of delivery data
* DateTime conversion
* Time series visualization
* Stationarity testing using the Augmented Dickey-Fuller (ADF) Test
* Forecasting future deliveries using Exponential Smoothing

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Statsmodels
* Jupyter Notebook


---

## Key Outcomes

* Successfully built an end-to-end Machine Learning pipeline.
* Performed comprehensive exploratory data analysis.
* Developed regression models for delivery prediction.
* Verified stationarity using the ADF Test.
* Applied Exponential Smoothing for future delivery forecasting.
* Documented each stage with visualizations and observations.

---

## Author

**Varad Parkhe**

M.Tech – Data Science and Analytics

