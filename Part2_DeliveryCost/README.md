# Cost Per Order (CPO) Prediction Analysis
## Overview

This project analyzes operational delivery data to identify key drivers of cost per order (CPO) and builds models to predict future costs across stores.

## Key Insights
Distance is the strongest driver of CPO (~0.74 correlation)
Delivery fee is highly dependent on distance (~0.93 correlation)
Basket size has a weak negative relationship with CPO
Significant variation in cost efficiency across stores
Some stores consistently incur higher operational costs

## Model & Prediction
Models:
Linear Regression
Random Forest Regressor

## Features:
Store code, distance, basket size, time features

## Performance
Random Forest:
MAE: 0.12
R²: 0.95
Linear Regression:
MAE: 0.32
R²: 0.66

Random Forest significantly outperformed Linear Regression.

## Recommendations
Optimize delivery routes to reduce distance-related costs
Encourage larger basket sizes to improve efficiency
Investigate high-cost stores and replicate best practices from efficient ones
Use predictive models for cost planning and budgeting


## Tools
Python (Pandas, Scikit-learn)
Data Analysis and Machine Learning
