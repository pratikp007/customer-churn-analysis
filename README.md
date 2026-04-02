# Customer Churn Analysis

## Project Overview
Analyzed 7,043 telecom customers to identify 
key drivers of customer churn using Python and SQL.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- SQL (SQLite)
- Data Visualization

## Key Findings
1. Overall churn rate is 26.5%
2. Month-to-month customers churn at 42.7%
3. Annual contract customers churn at only 11%
4. Month-to-month customers churn 3x more than annual
5. High charges + low tenure = highest risk customers

## Business Recommendation
Convert month-to-month customers to annual contracts
to reduce churn by up to 3x — directly applicable
to banking customer retention strategy!

## Charts
- churn_rate.png — Overall churn pie chart
- contract_churn.png — Churn by contract type
- charges_distribution.png — Monthly charges analysis
- tenure_churn.png — Tenure vs churn analysis

## How to Run
pip install pandas matplotlib seaborn
jupyter notebook churn_analysis.ipynb

## Dataset
IBM Telco Customer Churn — 7,043 rows, 21 columns
