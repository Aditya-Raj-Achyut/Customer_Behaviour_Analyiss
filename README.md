📊 Customer Shopping Behavior Analysis
🔍 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover meaningful insights related to customer demographics, spending patterns, product performance, discounts, subscriptions, and shipping preferences to support data-driven business decisions.

🛠 Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & feature engineering

PostgreSQL – SQL-based business analysis

SQLAlchemy – Python–PostgreSQL integration

Power BI – Interactive dashboard & visualization

📂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discounts, Previous Purchases, Purchase Frequency, Review Ratings, Shipping Type

Missing Values: 37 missing values in the Review Rating column

🧹 Exploratory Data Analysis (Python)

The analysis started with data preparation and cleaning using Python:

Loaded raw CSV data using pandas

Explored data structure using df.info() and df.describe()

Handled missing values by imputing median review ratings per product category

Standardized column names to snake_case

Performed feature engineering:

Created age_group buckets

Derived purchase frequency indicators

Removed redundant columns after consistency checks

Loaded the cleaned dataset into PostgreSQL for SQL analysis

🧠 Data Analysis using SQL (PostgreSQL)

Performed structured SQL analysis to answer key business questions:

Revenue distribution by gender

High-spending customers who used discounts

Top 5 products by average customer rating

Comparison of purchase value by shipping type

Spending behavior of subscribers vs non-subscribers

Products most dependent on discounts

Customer segmentation into New, Returning, and Loyal

Top 3 products within each category

Relationship between repeat purchases and subscription status

Revenue contribution by age group

📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

Revenue trends

Customer segments

Product performance

Subscription impact

Shipping and discount insights

This dashboard enables stakeholders to quickly explore patterns and make informed decisions.
