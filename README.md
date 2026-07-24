# Wind Speed Forecasting for Wind Turbines Using Regression Techniques

Bachelor's thesis project developed for the Bachelor's Degree in Electronic and Computer Engineering at the University of Pavia.

## Project Overview

The aim of this project is to analyze and forecast wind speed measurements in a wind turbine using regression techniques.

The study focuses on the recalibration of wind speed measurements by exploiting weather forecast data collected at different heights. The objective is to develop a regression model capable of estimating turbine-level wind speed and improving forecasting accuracy.

## Data and Code Availability

The dataset and source code are not publicly available due to privacy and data ownership restrictions.

The repository contains a description of the methodology, results, and the final report of the project.

## Methodology

The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature engineering
- Analysis of wind speed and wind direction variables
- Regression model development
- Model evaluation and comparison

The following regression techniques were investigated:

- Least Squares (LS)
- Ridge Regression
- Lasso Regression

## Dataset and Variables

**Input features:**
- Forecasted wind speed and wind direction at different heights:
  - 10 m
  - 50 m
  - 80 m
  - 100 m

**Target output:**
- Wind speed measurements collected by the turbine anemometer.

## Results

The final Ridge Regression model achieved:

- RMSE: 1.56 m/s
- R²: 0.56
- NRMSE (normalized by range): 8%

The results show the effectiveness of regularized regression techniques in handling highly correlated meteorological variables.

## Tools

- MATLAB
- Statistical analysis
- Regression techniques
- Data visualization
