# Customer_Behavior_Analysis
Customer Behavior Analysis Using Python, MySQL, PowerBI
📊 Customer Shopping Behavior Analysis
🔍 Overview

This project analyzes customer shopping behavior using transactional data (3,900+ records) to uncover patterns in spending, customer segments, and product performance. The goal is to generate actionable insights that can support business decisions around marketing, retention, and product strategy.

📁 Dataset
Total Records: 3,900
Features: 18
Key Columns:
Customer: Age, Gender, Location, Subscription Status
Purchase: Item, Category, Amount, Season, Size, Color
Behavior: Discount Applied, Purchase Frequency, Review Rating, Shipping Type
Data Issues:
Missing values in Review Rating (handled using median imputation)
Redundant columns removed (promo_code_used)
🛠️ Tools & Technologies
Python: Data cleaning, preprocessing, feature engineering
Pandas: Data manipulation
PostgreSQL / SQL: Data analysis & business queries
Power BI: Dashboard & visualization
📊 Exploratory Data Analysis (EDA)
Cleaned and standardized dataset (snake_case format)
Handled missing values in review ratings
Created new features:
age_group
purchase_frequency_days
Ensured data consistency and removed redundant fields
🧠 SQL Analysis (Business Questions)

Key insights derived using SQL:

Revenue distribution by gender
High-spending customers using discounts
Top 5 products by average rating
Shipping type impact on purchase amount
Subscribers vs non-subscribers revenue comparison
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top products per category
Repeat buyers vs subscription behavior
Revenue contribution by age group
📈 Dashboard (Power BI)

Built an interactive dashboard to visualize:

Total customers, average purchase, average rating
Revenue by category and age group
Subscription distribution
Sales trends and product performance
📌 Key Results
Loyal customers form the majority of the user base
Subscription adoption is relatively low despite high repeat purchases
Certain products heavily rely on discounts for sales
Young adults contribute the highest revenue
Express shipping users tend to spend slightly more
💡 Business Recommendations
Improve subscription conversion with targeted offers
Introduce loyalty programs for repeat customers
Optimize discount strategy to protect margins
Focus marketing on high-revenue age groups
Promote top-rated and best-selling products
▶️ How to Run
Load dataset into Python (Pandas)
Perform data cleaning and feature engineering
Export cleaned data to PostgreSQL
Run SQL queries for analysis
Connect Power BI to database and build dashboard
🚀 Project Outcome

This project demonstrates end-to-end data analysis:

Raw data → Cleaned dataset → SQL insights → Business dashboard
