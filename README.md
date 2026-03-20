🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to extract meaningful insights into:

Customer spending patterns

Product preferences

Customer segmentation

Subscription behavior

These insights help drive data-driven business decisions.

📄 Source:

📊 Dataset Summary

Total Records: 3,900

Total Columns: 18

🔑 Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior:

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

⚠️ Missing values:

37 missing entries in Review Rating

🧹 Data Preprocessing (Python)

The dataset was cleaned and prepared using Python:

Loaded data using pandas

Performed exploratory analysis using:

df.info()
df.describe()

Handled missing values using median imputation

Standardized column names (snake_case)

Created new features:

age_group

purchase_frequency_days

Removed redundant columns (promo_code_used)

Integrated with PostgreSQL for further analysis

🗄️ SQL Analysis (PostgreSQL)

Key business questions answered using SQL:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs Non-Subscribers

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Top Products per Category

Repeat Buyers & Subscription Trends

Revenue by Age Group

📈 Key Insights

Male customers generated higher revenue than female customers (page 3 table)

Express shipping users spend slightly more than standard users (page 4 table)

Most customers fall into the Loyal segment (3116 users) (page 5 table)

Certain products (like Hats, Sneakers) are highly discount-driven (page 5)

Young Adults contribute the highest revenue (page 7 table)

📊 Dashboard (Power BI)

An interactive dashboard was built in Power BI to visualize insights:

Dashboard Highlights:

Total Customers: 3.9K

Avg Purchase Amount: $59.76

Avg Rating: 3.75

Revenue by Category & Age Group

Subscription distribution

📍 (Refer to dashboard image on page 7)

💡 Business Recommendations

🎯 Boost Subscriptions with exclusive benefits

🏆 Loyalty Programs for repeat customers

💰 Optimize Discount Strategy to balance profit

📦 Highlight Top Products in marketing campaigns

🎯 Target High-Value Segments (young adults, express users)

🛠️ Tech Stack

Python (Pandas, Data Cleaning)

PostgreSQL (SQL Analysis)

Power BI (Dashboard & Visualization)
