# Customer Shopping Behavior Analysis

## Overview

This project is an end-to-end customer behavior analysis built to extract actionable business insights from transactional data. It demonstrates a complete analytics workflow using Python for data preparation, PostgreSQL for structured analysis, and Power BI for visualization and reporting.

The goal is to understand how customers purchase, what drives revenue, and how behavior differs across demographics, products, and subscription status.

## Dataset

* 3,900 customer purchase records
* 18 features covering demographics, purchase behavior, and product attributes
* Key fields include age, gender, category, purchase amount, discount usage, subscription status, shipping type, and review ratings

## Tools & Technologies

* Python (Pandas, NumPy)
* Jupyter Notebook
* PostgreSQL
* SQL
* Power BI

## Project Workflow

1. **Data Exploration & Cleaning (Python)**

   * Identified and handled missing values using category-based median imputation
   * Standardized column names (lowercase, underscores)
   * Engineered new features such as age groups and numeric purchase frequency

2. **Data Analysis (PostgreSQL & SQL)**

   * Imported cleaned data into PostgreSQL
   * Answered 10 business-critical questions related to revenue, discounts, subscriptions, and customer segmentation
   * Used SQL aggregations, joins, and window functions for analysis

3. **Data Visualization (Power BI)**

   * Connected PostgreSQL directly to Power BI
   * Built interactive dashboards showing revenue, customer segments, product performance, and key KPIs
   * Enabled filtering by age group, gender, category, subscription status, and shipping type

## Key Business Questions Answered

* Revenue comparison by gender and age group
* Spending behavior of subscribed vs. non-subscribed customers
* Impact of discounts on purchase amounts
* Top-performing products and categories
* Relationship between repeat purchases and subscription likelihood

## Business Impact

* Identifies high-value customer segments
* Supports targeted marketing and retention strategies
* Highlights products suitable for discount optimization
* Provides insights to improve subscription adoption and average order value

## Future Improvements

* Predictive modeling for churn and customer lifetime value
* Advanced cohort and retention analysis
* Automated data pipeline integration

## Author

Mani

---

This project is intended for learning, portfolio demonstration, and analytics practice.
