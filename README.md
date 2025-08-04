# Supply Chain Stockout Risk Analysis

This project presents an interactive Power BI dashboard designed to monitor supply chain performance and identify products at risk of stockout, based on machine learning predictions.

## Objective
Provide business stakeholders with visibility into:
- Key supply metrics (costs, order volume, lead time)
- Stockout risk identification using ML predictions
- Product-level risk trends and contributing factors

## Dataset
Based on the ["High Dimensional Supply Chain Inventory Dataset"](https://www.kaggle.com/datasets/ziya07/high-dimensional-supply-chain-inventory-dataset) from Kaggle. Features were engineered for machine learning purposes and include:
- Inventory level
- Demand forecast
- Coverage days
- Promotion flags
- Risk probability (predicted)
- Stockout risk flag (binary classification)

##  Machine Learning
Model: XGBoost classifier  
Techniques used:
- SMOTE for class imbalance
- 5-fold cross-validation  
Output: Stockout_Risk_Flag + Risk_Probability

## Dashboard Features (Power BI)
- KPIs: Total products at risk, average lead time, coverage days
- Trend line: Stockout risk over time
- Breakdown by SKU, lead time, and promotion status
- Supplier and region-level supply insights
- Filtering by SKU and Month

## Tools & Tech
- Python (XGBoost, pandas, scikit-learn)
- Power BI
- GitHub

## Insights
- Only ~0.79% of products are currently at risk, concentrated on specific SKUs with long lead times
- Promotional products show a slightly higher risk level
- March and April exhibit the highest risk peaks

## Author
Giovanni Chiostri 
LinkedIn: www.linkedin.com/in/giovanni-chiostri-655070166
GitHub: https://github.com/entongionn
