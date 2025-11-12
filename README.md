# Customer-Behavior-Dashboard-
🛍️ Customer Shopping Behavior Analysis
📖 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The objective is to uncover insights into spending patterns, product preferences, customer segmentation, and subscription behavior — helping businesses make data-driven decisions.

📊 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer Demographics → Age, Gender, Location, Subscription Status

Purchase Details → Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior → Discount Applied, Promo Code Used, Previous Purchases, Review Rating, Shipping Type

Missing Data: 37 values in Review Rating column

🧠 Exploratory Data Analysis (Python)

Performed data preparation and cleaning using Pandas and NumPy:

Loaded dataset and explored using .info() and .describe()

Imputed missing values in Review Rating using median by category

Renamed columns to snake_case for consistency

Engineered new features:

age_group (binned customer ages)

purchase_frequency_days (time gap between purchases)

Verified and removed redundant fields (promo_code_used)

Integrated with PostgreSQL for further SQL-based business analysis

🧾 SQL Business Analysis (PostgreSQL)

Structured SQL queries were used to answer critical business questions:

Revenue by Gender – Compare total revenue between male and female customers

High-Spending Discount Users – Identify discount users spending above average

Top 5 Products by Rating – Find best-rated products

Shipping Type Comparison – Compare avg purchase for Standard vs Express

Subscribers vs Non-Subscribers – Analyze revenue and spend

Discount-Dependent Products – Top 5 products with the highest discount ratio

Customer Segmentation – New, Returning, Loyal classification

Top 3 Products per Category – Find popular items by category

Repeat Buyers & Subscriptions – Link between frequent buyers and subscriptions

Revenue by Age Group – Age-wise contribution to total revenue

📈 Dashboard (Power BI)

An interactive Power BI dashboard visualizes all key findings:

Sales by Category, Gender, and Age Group

Top Products by Rating

Discount and Subscription trends

Shipping type analysis

💡 Business Recommendations

Boost Subscriptions: Offer exclusive subscriber perks

Loyalty Programs: Reward repeat buyers to drive retention

Optimize Discount Strategy: Manage balance between volume and profit

Product Positioning: Promote top-rated and best-selling items

Targeted Marketing: Focus on high-value age groups and express users

🧰 Tech Stack

Python: pandas, numpy, matplotlib

SQL: PostgreSQL

Visualization: Power BI

Environment: Jupyter Notebook / VS Code

📎 Project Structure
├── data/
│   └── customer_shopping_data.csv
├── notebooks/
│   └── EDA_and_Cleaning.ipynb
├── sql/
│   └── business_queries.sql
├── dashboard/
│   └── Customer_Shopping_Behavior.pbix
├── README.md

Dashboard Preview https://github.com/vivekyadav3-45/Customer-Behavior-Dashboard-/blob/main/Snapshot%20of%20tha%20dashboard.png
