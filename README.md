# Maverick Stores Sales Time Series Forecasting Project

## Summary of Business Problem and Project Objective

Maverick, a dynamic retail firm, plans to open 30 new stores each year. The business challenge lies in generating accurate first-year sales forecasts for these new stores to ensure effective financial planning and resource allocation. The project's objective is to develop a reliable forecasting model that can predict daily sales metrics, thereby aiding in strategic decision-making and operational planning.

## Solution to the Business Problem

The solution involves creating a sophisticated time series forecasting model using Python. This model integrates qualitative data from recent store openings and network-wide seasonality patterns. By employing various machine learning algorithms, such as XGBoost, Prophet, Linear Regression, Random Forest, and SARIMA, the model aims to provide accurate daily-level sales forecasts.

## The Business Value of the Solution

The forecasting model delivers significant business value by:
- Enabling precise financial planning for new store openings.
- Optimizing resource allocation based on predicted sales patterns.
- Providing a benchmark for assessing store performance against projected outcomes.
- Enhancing the company's ability to maintain its growth trajectory while making data-driven decisions.

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

## Difficulties Encountered Along the Way

During the project, the team faced several challenges:
- Managing and cleaning large datasets with diverse metrics.
- Integrating qualitative and time series data in a meaningful way.
- Selecting and tuning various machine learning models to improve forecast accuracy.
- Addressing the non-stationarity in sales data, which required sophisticated statistical techniques.

## What We Learned in the Project

Key learnings from the project include:
- The importance of thorough data exploration and preprocessing for model accuracy.
- Insights into the application of different machine learning algorithms for time series forecasting.
- The value of cross-validation in model selection and evaluation.
- Real-world application of data science in solving complex business problems.

## My Contributions
I worked on visualizing and interpreting the distribution of various features. I further analysed the First-Year sales and the top performing stores. I also visualized and interpreted the patterns that emerged in the analysis of First-Year sales and sales of the top performing stores. This included feature visualizations, Correlation analysis, feature and target distribution analysis, Time Series Decomposition (trend, seasonality, residuals), Autocorrelation analysis, Stationarity test and Decomposition comparison of top 5 stores. I also analyzed and visualized the effect of holidays on sales.

I performed descriptive and statistical analysis on the time-series and qualitative data. I treated missing values in the categorical data by creating new 'None' category . Moreover, I detected and treated the outliers for each target variable by using the IQR Method. I even performed the stationarity test for each target variable and created Autocorrelation plots for analysis. I performed feature engineering by creating new date features and also created lag and rolling features. Further, I encoded the categorical variables using One-Hot Encoding and split the data into train and test based on store ids. Finally, I trained, tested and performed forecasting using the XGBRegressor.
  
## Conclusion

This project harnesses machine learning to forecast sales for Maverick's new store openings, offering valuable insights into sales patterns and guiding financial and operational decisions for the company's expansion.


