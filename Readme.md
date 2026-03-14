Customer Shopping Behaviour Analysis
Project Overview

This project analyzes customer shopping behaviour using transactional data from 3,900 purchases across multiple product categories. The objective is to identify patterns in customer spending, product preferences, and subscription behaviour to support better business decisions.

Dataset

Rows: 3,900

Columns: 18

Key Features: Age, Gender, Location, Subscription Status, Item Purchased, Category, Purchase Amount, Discount Applied, Shipping Type, Review Rating, and Purchase Frequency.

Missing Values: 37 values in the Review Rating column, handled during data cleaning.

Data Processing (Python)

Loaded and explored data using Pandas.

Cleaned missing values by imputing median review ratings by category.

Standardized column names to snake_case.

Created new features such as age_group and purchase_frequency_days.

Loaded the cleaned dataset into MySQL for further analysis.

Data Analysis (SQL)

Key analyses performed:

Revenue comparison by gender

Subscribers vs non-subscribers spending

Top-rated and best-selling products

Shipping type impact on purchase amount

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

Dashboard

An interactive Power BI dashboard was created to visualize insights on customer behaviour, product performance, and revenue trends.

Tools Used

Python (Pandas, NumPy)

MySQL

Power BI

Key Insights

Subscribers tend to generate higher overall revenue.

Certain products depend heavily on discount-driven purchases.

Loyal customers and specific age groups contribute the most revenue.