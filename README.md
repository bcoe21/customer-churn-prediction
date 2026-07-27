# Customer Churn Prediction Model

## Overview
Logistic regression model predicting which telecom customers are at 
risk of churning, achieving 80.8% accuracy on unseen test data. 
Identifies key churn drivers to enable proactive retention strategies.

## Tools Used
- **Python** (pandas, scikit-learn, matplotlib, seaborn) — data 
  cleaning, feature engineering, model building, and visualization
- **scikit-learn** — logistic regression, train/test split, 
  StandardScaler, model evaluation metrics

## Key Findings
1. **80.8% model accuracy** on 1,409 unseen customer records — 
   correctly identified 212 of 374 at-risk customers
2. **Contract type creates a 15x churn difference** — month-to-month 
   customers churn at 42.7% vs just 2.8% for two-year contracts
3. **First year is the critical retention window** — customers in 
   months 0-12 churn at 47.7% vs 6.6% for customers past 5 years
4. **Fiber optic internet is the top churn risk factor** — premium 
   service customers are most likely to leave despite higher spend
5. **Tenure is the strongest churn protector** — the longer a 
   customer stays the dramatically less likely they are to leave

## Business Recommendations
1. Prioritize retention efforts in the first 12 months — highest 
   risk window where nearly half of customers churn
2. Incentivize contract upgrades — converting month-to-month to 
   one-year contracts cuts churn risk by 73%
3. Investigate fiber optic pricing and satisfaction — highest churn 
   risk service may indicate a pricing or quality problem

## Project Structure
- `customer-churn-prediction.ipynb` — full analysis and model notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — original dataset

## Data Source
IBM Telco Customer Churn dataset via Kaggle — 7,043 customer records, 
21 variables, binary churn target variable
