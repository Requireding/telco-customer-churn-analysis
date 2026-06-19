# Telecom Customer Churn Analysis 📊

## Overview
This project focuses on analyzing customer churn data for a telecommunications company. The goal of this analysis is to identify key drivers of customer attrition and provide actionable, data-driven recommendations to improve retention.

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, K-Means Clustering)

## Key Findings
1. **Contract Types:** Customers on month-to-month contracts have a significantly higher churn rate (42.7%) compared to those on 1-year (11.2%) or 2-year (2.8%) contracts.
2. **Tenure:** Churn risk is highest during the first few months of a customer's lifecycle.
3. **Services:** Customers with Fiber Optic internet service showed higher defection rates, primarily driven by competitor offers.
4. **Segmentation:** Through clustering, customers were categorized into actionable segments: 'Budget Loyal', 'High Risk New', and 'Loyal Premium'.

## Strategic Recommendations
* **Incentivize Contract Upgrades:** Target month-to-month users with early upgrades to 1-year contracts to lock in loyalty.
* **Proactive Onboarding:** Implement targeted rewards during the high-risk early tenure period (months 1-6).

## Files in this Repository
* `telco_customer_churn_analysis.ipynb` : The main Jupyter Notebook containing all EDA, visualizations, and predictive modeling.
* `Telco_customer_churn.xlsx` : The dataset used for the analysis.
