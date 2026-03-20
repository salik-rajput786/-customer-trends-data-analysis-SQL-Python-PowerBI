# -customer-trends-data-analysis-SQL-Python-PowerBI

📌 Project Overview

This project analyzes customer shopping behavior using transactional data to uncover patterns in purchasing, customer segmentation, and product performance. The objective is to generate actionable insights that help businesses make data-driven decisions.

The dataset contains 3,900 customer transactions across multiple product categories.

📊 Dataset Summary

Total Records: 3,900

Total Features: 18

🔑 Key Attributes:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Behavioral Data: Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

Missing Values: 37 missing entries in Review Rating

🛠️ Tech Stack

Python (Pandas, NumPy) → Data Cleaning & Feature Engineering

Microsoft SQL Server (MSSQL) → Data Analysis & Querying

Power BI → Data Visualization & Dashboard

🔄 Data Preprocessing

Handled missing values using median imputation (category-wise)

Standardized column names into snake_case format

Created new features:

age_group

purchase_frequency_days

Removed redundant columns (e.g., promo_code_used)

Loaded cleaned dataset into MSSQL database

📈 Business Analysis (MSSQL)

Performed advanced SQL analysis using Microsoft SQL Server to answer key business questions:

💰 Revenue by Gender

🛍️ High-Spending Customers Using Discounts

⭐ Top 5 Products by Average Rating

🚚 Shipping Type Comparison (Standard vs Express)

👥 Subscribers vs Non-Subscribers Analysis

🎯 Discount-Dependent Products

🔄 Customer Segmentation (New, Returning, Loyal)

🏆 Top 3 Products per Category

🔁 Repeat Buyers vs Subscription Behavior

👶 Revenue Contribution by Age Group

📊 Dashboard (Power BI)

Developed an interactive Power BI dashboard to visualize:

Total Customers

Average Purchase Amount

Revenue by Category

Sales Distribution by Age Group

Subscription Status Breakdown

🔍 Key Insights

Male customers contributed higher overall revenue

Loyal customers represent the largest segment

Express shipping users have slightly higher average spending

Some products are highly dependent on discounts for sales

Young adults generate the highest revenue

💡 Business Recommendations

🚀 Promote subscription plans with exclusive benefits

🎁 Implement loyalty programs for repeat customers

💸 Optimize discount strategies to balance revenue and profit

📢 Highlight top-rated and high-performing products

🎯 Focus marketing campaigns on high-revenue age groups

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/customer-shopping-analysis.git
2️⃣ Data Preprocessing (Python)

Run Python scripts to clean and transform data

3️⃣ Load Data into MSSQL

Import dataset into Microsoft SQL Server

Create database and tables

4️⃣ Run SQL Queries

Execute analysis queries in SQL Server Management Studio (SSMS)

5️⃣ Visualize in Power BI

Connect Power BI to MSSQL

Load dataset and build dashboard

🎯 Project Outcome

This project demonstrates the end-to-end data analytics workflow:

Data Cleaning → SQL Analysis → Data Visualization

It highlights how businesses can leverage data to:

Understand customer behavior

Improve decision-making

Increase revenue and customer retention

🤝 Connect with Me

If you liked this project or have suggestions, feel free to connect!

📧 Email: mohdsalik715@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/mohd-salik-rajput-406531247/

