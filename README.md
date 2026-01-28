# Customer Shopping Behavior Analysis (Python, SQL, PowerBI)
---
## Project Overview
This project simulates a corporate-grade, end-to-end data analytics workflow for a retail business. The objective is to transform raw customer transaction data into actionable business insights that support strategic decision-making.
The analysis focuses on understanding customer segments, purchase drivers, loyalty patterns, and revenue trends using Python, SQL, and Power BI.
---
## Business Problem
A retail company wants to better understand customer shopping behavior in order to:
-Improve sales performance
-Increase customer engagement and loyalty
-Optimize marketing and product strategies
-Key areas of interest include:
-Demographics and customer segments
-Product categories and purchasing trends
-Discounts, subscriptions, and repeat purchases
-Revenue contribution across different customer groups

The core business question addressed in this project is:
How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?
---
## Dataset Overview
The dataset contains 3,900 transaction records with 18 columns.

Key Features:
-Customer demographics: age, gender, location, subscription status
-Purchase details: item, category, price, season, size, color
-Behavioral metrics: discounts, promo usage, previous purchases, purchase frequency, review ratings, shipping type
---
## Tools and Technologies
-Python (pandas, NumPy) was used for data cleaning, transformation, and feature engineering.
-PostgreSQL was used to perform SQL-based business analysis.
-Power BI was used to build an interactive dashboard and visualize insights.
-Jupyter Notebook was used for the analysis workflow.
-GitHub was used for version control and project documentation.
---
## Project Workflow
# Data Preparation and Exploratory Analysis (Python)
The dataset was loaded and explored using pandas. Column names were standardized for consistency and readability. Missing values in the review_rating column were handled using median imputation at the category level.
New features were created, including age_group (Young Adult, Adult, Middle-aged, Senior) and purchase_frequency_days derived from purchase frequency categories. Data consistency checks were performed, redundant columns were removed, and the final cleaned dataset was prepared for SQL analysis.

# Data Analysis (SQL)
The cleaned dataset was loaded into PostgreSQL to simulate real-world business analysis. SQL queries were written to answer business-driven questions such as revenue comparison by gender, identification of high-spending customers who used discounts, top products by average review rating, purchase behavior by shipping type, spending patterns of subscribers versus non-subscribers, discount dependency by product, customer segmentation into New, Returning, and Loyal groups, top products within each category, the relationship between repeat purchases and subscriptions, and revenue contribution by age group.

# Visualization and Dashboard (Power BI)
An interactive Power BI dashboard was developed to present insights clearly to stakeholders. The dashboard includes total customers and average purchase value, revenue by product category, subscription versus non-subscription split, sales and revenue by age group, and interactive filters for category, shipping type, and subscription status.
---
## Key Insights
-Subscribers generate higher long-term value despite similar average purchase amounts
-Loyal customers form the largest segment, highlighting retention opportunities
-Certain products rely heavily on discounts, impacting margins
-Middle-aged and young adult customers contribute the most revenue
-Express shipping customers tend to spend slightly more per purchase
---
## Business Recommendations
-Promote subscription benefits to increase long-term revenue
-Introduce loyalty programs for high-repeat customers
-Optimize discount strategies to protect margins
-Highlight top-rated and high-performing products in marketing campaigns
-Focus marketing efforts on high-revenue customer segments


Jupyter Notebook was used for the analysis workflow.
GitHub was used for version control and project documentation.
