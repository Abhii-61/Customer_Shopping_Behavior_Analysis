# Customer_Shopping_Behavior_Analysis
Data Analytics project showing the behavior of customers, using Python, MySQL, PowerBI. 
🛍️ Customer Shopping Behavior Analysis

Tools: Python | MySQL | Power BI | Jupyter Notebook

📌 Project Overview

This project focuses on analyzing customer shopping behavior using real-world style e-commerce data.
The analysis was performed using:

Python for data cleaning & preprocessing

MySQL for analytical SQL queries

Power BI for dashboard visualization

Jupyter Notebook for exploration and insights

The goal of this project is to understand customer purchase patterns, identify high-revenue products, evaluate seasonal trends, and build interactive dashboards that support business decision-making.

🎯 Objectives

Analyze total revenue, purchase patterns, and customer demographics

Determine category-wise and season-wise performance

Evaluate the impact of discounts and subscriptions

Identify top-performing products using ratings and sales

Build an interactive Power BI dashboard

Solve business queries using SQL

📊 Dashboard (Power BI)

The Power BI dashboard includes:

KPI Cards: Total customers, Average Purchase Amount, Avg. Review Rating

Revenue by Category

Season-wise Sales

Subscription Status Distribution

Total Item Sales by Category

Interactive Filters: Gender, Shipping Type, Promo Code Used, Subscription Status

Dashboard Preview:

(Add your dashboard image here in GitHub)

![Dashboard Preview](dashboard_image.png)

🗄️ Dataset Information

The dataset contains:

Customer ID

Gender & Age Group

Item Purchased & Category

Review Ratings

Purchase Amount

Previous Purchases

Shipping Type

Discount & Promo Code Usage

Subscription Status

🧹 Data Cleaning (Python)

Performed in Jupyter Notebook:

Removed duplicates

Handled missing values

Standardized column formats

Converted datatypes

Created new columns (Age Group, Segments, etc.)

Exported cleaned dataset to MySQL

🧮 SQL Analysis

Business questions solved using SQL include:

Revenue by gender

High-spending discount users

Top-rated products

Comparison of shipping types

Subscription impact on spend

Discount usage by products

Customer segmentation (New/Returning/Loyal)

Category-wise top 3 products

Repeat buyers vs subscription

Revenue by age group

Full SQL script included in:

SQL Scripts.sql

📈 Key Insights

Clothing category generated the highest revenue

Spring season has the highest sales

Average purchase amount: ~$59.76

73% customers are non-subscribers

Subscribers tend to spend more than non-subscribers

Discounts drive purchases for certain product categories

Customer segmentation helps understand purchasing behavior

🖥️ Tech Stack
Tool	Purpose
Python	Data cleaning, preprocessing
Pandas, NumPy	Data handling
MySQL	SQL analysis
Power BI	Dashboard & visualization
Jupyter Notebook	Exploratory analysis
Matplotlib/Seaborn	Data visualization
📂 Project Structure
├── PowerBI_Dashboard.pbix
├── Customer_Shopping_Behavior_Analysis.ipynb
├── SQL Scripts.sql
├── README.md
└── Dashboard_Screenshot.png

🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/customer-shopping-analysis.git

2. Install required Python libraries
pip install pandas numpy matplotlib seaborn mysql-connector-python sqlalchemy

3. Run Jupyter Notebook
jupyter notebook

4. Import SQL file in MySQL

Use MySQL Workbench or CLI to run:

source SQL Scripts.sql

5. Open Power BI Dashboard

Load the .pbix file into Power BI Desktop.

📝 Conclusion

This project demonstrates the end-to-end analytical workflow of a data analyst—covering data cleaning, SQL analysis, and BI dashboard creation.
It provides useful insights into customer behavior and retail business performance.
