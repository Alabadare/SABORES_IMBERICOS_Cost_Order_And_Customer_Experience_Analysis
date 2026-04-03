# SABORES_IMBERICOS_Cost_Order_And_Customer_Experience_Analysis-
This project combines order management, cost analysis, and customer feedback to identify operational inefficiencies and improve overall service performance.

## Order, Cost & Customer Experience Analysis

### Project Overview
This project combines order management, cost analysis, and customer feedback to identify operational inefficiencies and improve overall service performance.

### Objectives
* Identify causes of bad ratings and cancellations
* Analyze drivers of refunds and costs
* Understand customer feedback trends
* Build predictive models for refunds and cost per order (CPO)


### Key Insights
*  ~85% of orders are problematic (bad ratings or cancellations)
*  Refunds are mainly driven by wrong or missing products
*  High cancellations caused by:
    * Product unavailability
    * Store technical issues
*  Distance is the main driver of cost per order (CPO)
*  Significant performance differences across stores
*  Top complaints:
    * Slow service
    * Rude service
*  Refunds and CPO can be reliably predicted using ML models

### Core Problems Identified
* Poor order fulfillment process
* Inefficient inventory management
* High delivery/logistics costs
* Inconsistent store performance
* Weak customer experience management

### Methods Used
* Data Cleaning & Feature Engineering
* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Time-based Feature Creation
* Machine Learning Models:
    * Linear Regression
    * Random Forest Regressor
* Sentiment Analysis (VADER)

### Models Performance
Model	Task	Performance
Random Forest	Refund Prediction	Good accuracy (low error)
Random Forest	CPO Prediction	R² ≈ 0.95
Linear Regression	CPO Prediction	R² ≈ 0.66

### Recommendations
* Improve order accuracy (quality checks, staff training)
* Implement real-time inventory tracking
* Optimize delivery routes to reduce distance costs
* Standardize store operations using best practices
* Use predictive models for proactive decision-making
* Monitor customer feedback continuously
* Encourage larger basket sizes for better efficiency

### Conclusion
Most issues are internal and controllable. Improving operations will reduce costs, refunds, and complaints, while increasing efficiency and customer satisfaction.


 Tools & Technologies
* Python (Pandas, NumPy, Scikit-learn)
* SQL
* Matplotlib / Seaborn
* NLP (NLTK, spaCy, VADER)
>>>>>>> 6da92dd (Initial commit: Organized 3-part analysis project)
