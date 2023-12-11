# Maverick Stores Sales Time Series Forecasting Project

## Overview

Maverick, a rapidly expanding retail firm, aims to open 30 new stores annually. Accurate first-year sales forecasts for these new stores are crucial for effective financial planning and resource allocation. The project's success hinges on the accuracy of sales metrics forecasts and the Return on Investment (ROI) aligning closely with the forecasted ROI.

## Project Scope

This project involves developing a sophisticated time series forecasting model in Python, integrating qualitative data from recent store openings, network-wide seasonality patterns, and various sales metrics. The primary goal is to generate daily-level forecasts to support strategic decision-making and operational planning.

## Data Analysis and Exploration

### Exploratory Data Analysis (EDA)

- Comprehensive examination of time series and qualitative data sets.
- Key steps included initial data exploration, descriptive statistics, handling missing values, and outlier detection.
- Insights into sales patterns, including inside sales, food service sales, and fuel sales (diesel and unleaded), were gained using correlation plots, histograms, bar graphs, seasonal decomposition, stationarity tests, autocorrelation, etc.

### Data Preparation

- Merging of the time series dataset with the qualitative dataset.
- Application of techniques like label encoding to convert categorical variables into numerical formats.

## Model Development

### Machine Learning Models

- Deployment of various machine learning algorithms for predicting daily sales metrics.
- Models included XGBoost, Prophet, Linear Regression, Random Forest, and SARIMA.
- Focus on forecasting different target variables: Total Inside Sales, Total Food Sales, Diesel Sales, and Unleaded Sales.

### Model Selection and Evaluation

- Rigorous testing and evaluation of models using cross-validation techniques.
- Selection criteria based on the accuracy of sales forecasts using RMSE and the ability to match the projected ROI.
- XGBoost turned out to be the model with the best forecasting power.

## Conclusion

This project harnesses machine learning to forecast sales for Maverick's new store openings, offering valuable insights into sales patterns and guiding financial and operational decisions for the company's expansion.
