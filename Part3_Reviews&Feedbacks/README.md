Customer Feedback & Sentiment Analysis
Overview

This project analyzes customer reviews to identify policy violations, understand sentiment trends, and explore relationships between customer feedback and operational issues.

Key Insights
Most frequent complaints:
Rude service
Slow service

Customer sentiment is largely positive but highly polarized

Locations with higher negative sentiment tend to have more policy violations
Certain cities show consistently higher complaint rates

Analysis & Modeling
Sentiment Analysis:
Tool: VADER
Categories: Positive, Neutral, Negative

Predictive Analysis:
Model: Linear Regression
Goal: Estimate policy violations based on negative sentiment
Performance
MAE: 73.42
R²: 0.27

Indicates a moderate relationship between negative sentiment and policy violations.

Recommendations
Improve service quality, especially reducing slow and rude service
Focus on high-complaint locations with targeted interventions
Monitor customer sentiment continuously for early issue detection
Use feedback data to guide operational improvements

Tools
Python (Pandas, NLTK, spaCy, VADER)
NLP and Data Analysis