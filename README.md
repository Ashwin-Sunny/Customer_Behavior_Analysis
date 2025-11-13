# Customer_Behavior_Analysis
Analyze and visualize customer shopping trends using Python, SQL, and Power BI. This project explores a dataset of 3,900 purchases to uncover key insights into spending behavior, customer segmentation, product performance, and subscription patterns.

📊 Project Overview

The goal of this project is to understand how different customer segments shop — who spends more, which products perform best, and how discounts and subscriptions affect revenue.
The analysis combines Python for data preparation, PostgreSQL for business analysis, and Power BI for visualization.

🧾 Dataset Summary

Rows: 3,900

Columns: 18

Features include:

Customer demographics — Age, Gender, Location, Subscription Status

Purchase details — Item, Category, Amount, Season, Size, Color

Behavioral data — Discount Applied, Frequency of Purchases, Review Rating, Shipping Type

Missing Data: 37 null values in the Review Rating column

⚙️ Data Preparation in Python

Data Loading & Exploration – Imported dataset with pandas, checked structure using df.info() and .describe().

Handling Missing Values – Imputed missing review ratings with the median rating per product category.

Feature Engineering –

Created age_group bins.

Calculated purchase_frequency_days.

Database Integration – Loaded the cleaned dataset into PostgreSQL for structured SQL analysis.

🧮 SQL Analysis & Insights

Key analytical queries were performed in PostgreSQL:

Revenue by Gender – Compared total revenue between male and female customers.

High-Spending Discount Users – Found users who used discounts yet spent above average.

Top-Rated Products – Identified top 5 products by average review score.

Shipping Type Comparison – Compared average spend under standard vs. express shipping.

Subscribers vs. Non-Subscribers – Compared spending and revenue patterns.

Customer Segmentation – Classified customers into New, Returning, and Loyal groups.

📈 Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue trends by gender and age group

Product performance and ratings

Subscription and shipping comparisons

Customer segmentation breakdowns

💡 Business Recommendations

Boost Subscriptions – Offer exclusive perks to increase recurring customers.

Loyalty Programs – Reward frequent buyers to drive retention.

Optimize Discount Strategy – Balance sales boosts with profit margins.

Product Promotion – Highlight top-rated and best-selling products in marketing.

Targeted Marketing – Focus on high-revenue age groups and express-shipping users.

🧰 Tools & Technologies

Python: Pandas, NumPy

SQL: PostgreSQL

Visualization: Power BI

IDE: Jupyter Notebook / VS Code
