# Customer-Behavior-analysis

📊 Customer Behavior Data Analytics Project
🧭 Overview

This project demonstrates the end-to-end data analytics workflow, from loading and exploring raw data in Python to visualizing insights in Power BI and presenting findings in a professional report. The goal is to analyze customer behavior patterns and provide actionable insights through data cleaning, SQL analysis, and interactive dashboards.

📁 Dataset

Name: Customer Behavior Dataset

Source: Collected / Provided for analytics practice (can be replaced with any business dataset)

Description: Contains customer details, purchase information, review ratings, discounts, and other behavioral metrics.

Size: ~10,000 records with multiple categorical and numerical variables

🧰 Tools and Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Reporting	Gamma App (for creating presentation decks)
IDE	Jupyter Notebook / VS Code
Libraries	SQLAlchemy, Psycopg2, MySQL Connector, Plotly, Pandas-Profiling
🪜 Project Steps
1. Data Loading

Imported the dataset using Pandas in Jupyter Notebook.

Performed initial data inspection (df.head(), df.info(), df.describe()).

2. Exploratory Data Analysis (EDA)

Checked for missing values, outliers, and data distributions.

Visualized customer demographics, purchase trends, and review ratings using Matplotlib and Seaborn.

3. Data Cleaning

Handled null values using group-based imputation and mean/median filling.

Removed duplicate records and standardized column names.

Transformed data types for SQL and Power BI compatibility.

4. Database Integration

Loaded cleaned data into PostgreSQL/MySQL using SQLAlchemy.

Ran SQL queries to:

Retrieve top-selling products

Find customers with highest purchase frequency

Calculate average review ratings

Identify patterns in discount vs. sales performance

5. Power BI Dashboard

Connected Power BI to the SQL database.

Created visual dashboards for:

Sales trends by category and location

Customer segmentation by age group

Review rating distribution

Discount impact on revenue

6. Reporting

Created an interactive report and presentation using Gamma.app, summarizing:

Key insights

Data-driven recommendations

Visual highlights from the dashboard

📈 Dashboard Preview

(Attach or link Power BI dashboard screenshots here)
Example visuals:

📊 Sales by Product Category

👥 Customer Distribution by Age Group

⭐ Average Review Ratings by Product

💸 Discount Impact Analysis

🧩 Results and Insights

Found strong correlation between discounts and purchase frequency.

Top 5 products contributed to 60% of total revenue.

Majority of customers aged 25–35 years showed the highest retention rate.

Review ratings significantly influenced repeat purchases.
