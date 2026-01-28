Customer Shopping Behavior Analysis (SQL, Python, Power BI)
Project Overview

This project simulates a corporate-grade, end-to-end data analytics workflow focused on understanding customer shopping behavior in a retail environment. The objective is to demonstrate how raw transactional data can be transformed into meaningful business insights that support strategic decision-making.

The analysis covers customer demographics, purchasing patterns, loyalty behavior, and revenue drivers using Python for data preparation, SQL for analysis, and Power BI for visualization.

Business Problem

A retail company wants to better understand how customers interact with its products and services in order to improve sales performance, customer engagement, and long-term loyalty. Management has observed variations in purchasing behavior across demographics, product categories, and purchasing conditions such as discounts, seasons, and subscription status.

The core business question addressed in this project is:
How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

Dataset Description

The dataset contains 3,900 customer purchase records with 18 features, including customer demographics, product details, transaction values, subscription status, discount usage, purchase frequency, and review ratings. Minor missing values were present in the review rating field and were handled during preprocessing.

Tools and Technologies

Python (pandas, NumPy) was used for data cleaning, transformation, and feature engineering.
PostgreSQL was used to perform SQL-based business analysis.
Power BI was used to create an interactive dashboard for stakeholder reporting.
Jupyter Notebook and GitHub were used for analysis workflow and project documentation.

Data Preparation and Exploratory Analysis (Python)

The raw dataset was cleaned and standardized by renaming columns, handling missing values, and validating data consistency. New analytical features were created, including customer age groups and purchase frequency in days. Redundant fields were removed, and the final dataset was prepared for SQL-based analysis.

Data Analysis (SQL)

The cleaned dataset was loaded into PostgreSQL to simulate real-world analytical queries. SQL was used to analyze revenue distribution, customer spending behavior, discount effectiveness, subscription impact, customer loyalty segmentation, product performance, and demographic-based revenue contribution. Queries were written with a business-driven approach to reflect how analysts work in production environments.

Visualization and Insights (Power BI)

An interactive Power BI dashboard was developed to communicate insights clearly and effectively. The dashboard includes key performance indicators such as total customers, revenue by category, subscription split, spending by age group, and filters for product category, shipping type, and subscription status. The dashboard enables stakeholders to explore patterns and make data-driven decisions.

Key Insights

Subscribed customers contribute higher long-term revenue compared to non-subscribers.
Repeat and loyal customers form a significant portion of total revenue.
Certain products rely heavily on discounts, which may impact profitability.
Middle-aged and young adult customers are the highest revenue-generating segments.
Customers opting for faster shipping tend to spend slightly more per transaction.

Business Recommendations

Strengthen subscription and loyalty programs to improve retention and lifetime value.
Optimize discount strategies to balance customer acquisition and profit margins.
Focus marketing efforts on high-revenue customer segments and top-performing products.
Use product ratings and purchase behavior to guide inventory and promotional decisions.
