Order Management & Refund Forecasting Analysis
Overview

This project analyzes order data to identify causes of cancellations, bad ratings, and customer refunds, and builds a model to forecast future refunds.

Key Insights
~85% of orders are problematic (bad ratings or cancellations)
Refunds are strongly driven by wrong or missing products (~0.80 correlation)
Major cancellation causes:
Product unavailability
Store technical issues
Bad ratings show monthly fluctuations (peak in May)
Certain locations consistently underperform
Model & Forecasting
Model: Random Forest Regressor
Features:
Orders, basket size, cancellations, bad ratings
Time features and lag variables
Performance:
MAE: 7.92
RMSE: 13.29

Forecasts refunds for the next 5 weeks per store.

Recommendations
Improve order accuracy (reduce wrong/missing items)
Fix inventory issues to reduce cancellations
Investigate underperforming locations
Use forecasts for proactive cost management
Tools
Python (Pandas, Scikit-learn)
Data Analysis and Machine Learning
