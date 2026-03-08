Project Overview

This project analyzes customer shopping behavior using 3,900 transactional records to uncover insights about spending patterns, product preferences, and customer segments.The analysis combines Python for data cleaning, SQL for business analysis, and Power BI for visualization, demonstrating an end-to-end data analytics workflow from raw data to business insights.The goal is to help businesses make data-driven decisions in marketing, customer retention, and product strategy.

Dataset Summary:
Rows: 3,900
Columns: 18

Key Features:
Customer demographics: Age, Gender, Location
Purchase details: Item Purchased, Category, Purchase Amount
Shopping behavior: Previous Purchases, Frequency of Purchases
Marketing data: Discount Applied, Subscription Status
Product feedback: Review Rating
Logistics: Shipping Type

Data Issue
37 missing values in Review Rating column

Tools & Technologies
Tool	Purpose
Python	Data cleaning & preprocessing
Pandas	Data manipulation
PostgreSQL	Business analysis using SQL
Power BI	Dashboard & visualization

Project Workflow
1 Data Cleaning (Python)
Loaded dataset using pandas
Checked dataset structure using .info() and .describe()
Handled missing values in review_rating
Standardized column names to snake_case

Created new features:
age_group
purchase_frequency_days
Removed redundant columns
Loaded cleaned data into MySQL
SQL Business Analysis

Key analytical queries included:
Revenue Analysis
Revenue by gender
Revenue by age group
Customer Behavior
Customer segmentation: New, Returning, Loyal

Product Insights:
Top 5 highest rated products
Top 3 most purchased items per category

Marketing Insights:
Discount dependency analysis
Subscriber vs non-subscriber spending
Logistics
Shipping type purchase comparison

Power BI Dashboard:
An interactive dashboard was created to visualize:
Customer demographics
Revenue distribution
Product performance
Purchase behavior
Customer segmentation

Dashboard enables quick exploration of business insights.

<img width="1302" height="730" alt="image" src="https://github.com/user-attachments/assets/b8fccbaf-ac36-496e-b439-c56c96f691b6" />

Key Insights:
Repeat buyers generate significant revenue.
Some products rely heavily on discounts to drive purchases.
Subscribers tend to spend more consistently.
Certain age groups contribute more to total revenue.

Business Recommendations:
1. Subscription Growth
Offer exclusive discounts and perks for subscribers.
2. Loyalty Programs
Reward repeat customers to increase retention.
3. Discount Strategy
Optimize discount usage to protect profit margins.
4. Targeted Marketing
Focus on high-value customer segments.

Project Structure
customer-shopping-analysis
│
├── data
│   └── shopping_data.csv
│
├── python
│   └── data_cleaning.py
│
├── sql
│   └── analysis_queries.sql
│
├── powerbi
│   └── dashboard.pbix
│
├── dashboard
│   └── dashboard_screenshot.png
│
└── README.md

Skills Demonstrated:
Data Cleaning
Exploratory Data Analysis
SQL Window Functions
Customer Segmentation
Business Analysis
Dashboard Design
Data Storytelling

Author
Kushagra Mishra
Aspiring Data Analyst | SQL | Python | Power BI
