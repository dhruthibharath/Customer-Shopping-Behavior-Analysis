# Customer Shopping Behavior Analysis

# 📌 Project Overview

This project analyzes customer shopping behavior using a retail customer dataset to identify purchasing patterns, customer segments, spending behavior, discount usage, shipping preferences, and other business insights.

The project follows an **end-to-end data analytics workflow**, starting with data cleaning and transformation in Python, followed by SQL-based business analysis in PostgreSQL and interactive visualization in Power BI.

The goal is to transform raw customer data into meaningful insights that can help a retail business better understand its customers and make data-driven decisions.

# 🎯 Business Objective

The main objective of this project is to analyze customer shopping behavior and answer important business questions such as:

* Which customer groups contribute the most to purchases?
* How does purchasing behavior differ across age groups?
* What is the average purchase amount?
* How do customers differ based on their purchasing frequency?
* How does discount usage relate to customer purchases?
* What are the differences in purchasing behavior based on shipping preferences?
* How can customers be segmented based on their purchase history?

---

# 🛠️ Tools & Technologies

* **Python** – Data cleaning, transformation and exploratory data analysis(EDA)
* **Pandas** – Data manipulation and analysis
* **PostgreSQL** – Database storage and SQL analysis
* **SQL** – Business analysis and querying
* **Power BI** – Interactive dashboard and visualization
* **Jupyter Notebook** – Python development environment
* **GitHub** – Project documentation and portfolio

# 🔄 Project Workflow

Raw Dataset
     ↓
Data Exploration
     ↓
Data Cleaning & Transformation
     ↓
Feature Engineering
     ↓
PostgreSQL Database
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Recommendations

# 🐍 1. Data Analysis & Cleaning Using Python

The raw customer shopping dataset was loaded into Python using Pandas.

# Data preparation included:

* Inspecting the dataset structure
* Checking data types
* Identifying missing values
* Handling missing review ratings
* Creating customer age groups
* Converting purchase frequency into numerical day values
* Creating a discount-applied indicator
* Removing redundant columns
* Preparing the cleaned dataset for SQL analysis

# Feature Engineering

New useful features were created from existing data.

# Age Group

Customers were divided into four age groups:

* Young Adults
* Adults
* Middle Aged
* Seniors

# Purchase Frequency in Days

Purchase frequency was converted into numerical values:

| Frequency | Days |
| Weekly    |    7 |
| Monthly   |   30 |
| Quarterly |   90 |
| Annually  |  365 |

This makes the data easier to analyze numerically.

# 🗄️ 2. PostgreSQL & SQL Analysis

The cleaned dataset was loaded into a PostgreSQL database using **SQLAlchemy**.

SQL was then used to answer business-related questions from the customer data.

# SQL concepts used:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `COUNT()`
* `AVG()`
* `SUM()`
* `CASE`
* `WITH` / CTE
* Subqueries
* `IN`

# Examples of business analysis:

* Identifying customers with above-average purchase amounts
* Comparing average purchases based on shipping type
* Counting customers by customer segment
* Analyzing purchasing behavior
* Comparing customer groups

# 📊 3. Power BI Dashboard

The processed data was connected to Power BI to create an interactive dashboard.

The dashboard provides a visual overview of customer shopping behavior and allows users to explore the data through different categories and filters.

# Dashboard focuses on:

* Customer purchasing behavior
* Purchase amounts
* Customer segments
* Age groups
* Product/category information
* Discount usage
* Shipping preferences
* Other relevant customer metrics

# 💡 Key Insights

The analysis helps identify:

* Differences in purchasing behavior between customer groups
* High-value customers based on purchase amounts
* Customer distribution across different age groups
* Purchasing patterns based on frequency
* Differences in average purchase amounts across shipping types
* The distribution of new, returning, and loyal customers

# 📈 Business Recommendations

Based on the analysis, a retail company could:

1. **Focus on high-value customers** through personalized offers and loyalty programs.

2. **Target different age groups** with suitable marketing campaigns based on their purchasing behavior.

3. **Use customer segmentation** to create different strategies for new, returning, and loyal customers.

4. **Analyze discount usage** to understand whether promotions are reaching the right customers.

5. **Use purchasing frequency** to identify customers who may be ready for targeted offers or re-engagement campaigns.

## 📂 Project Structure

Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── customer_behaviour_sql_queries.sql
├── customer_behaviour_dashboard.pbix
├── Project_Report.pdf
└── README.md

# 🚀 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Python & Pandas
* SQL
* PostgreSQL
* Database Connectivity
* Business Problem Solving
* Data Visualization
* Power BI
* Dashboard Development
* Business Insights
* Data Storytelling

# 👩‍💻 Author

**Dhruthi**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

# ⭐ Project Summary

**Raw Data → Python → PostgreSQL/SQL → Power BI → Business Insights**

This project demonstrates how a data analyst can take a raw dataset, clean and transform it, analyze it using SQL, and present the results through an interactive business dashboard.
