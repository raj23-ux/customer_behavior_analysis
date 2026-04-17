📊 Customer Shopping Behavior Analysis

🔍 Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into spending patterns, customer segments, and product preferences to support data-driven business decisions.


📁 Dataset
The dataset consists of:
Rows: 3,900
Columns: 18

Key Features:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Behavioral Data: Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type
Missing Values: Handled missing values in the Review Rating column using median imputation.

🛠️ Tools & Technologies
Python – Data cleaning, preprocessing, and EDA
SQL (SQL Server) – Data querying and business analysis
Power BI – Interactive dashboard and visualization
Libraries: Pandas, NumPy.

⚙️ Steps Performed

1. Data Cleaning (Python)
Loaded dataset using Pandas
Handled missing values and corrected data types
Standardized column names (snake_case)
Performed feature engineering:
Created age_group
Created purchase frequency features
Removed redundant columns

2. Exploratory Data Analysis (EDA)
Analyzed customer demographics
Studied purchase patterns and category trends
Identified relationships between variables

3. SQL Analysis
Performed business-driven queries such as:
Revenue analysis by gender
High-spending customers using discounts
Top-rated products
Shipping type comparison
Subscriber vs non-subscriber analysis
Customer segmentation (New, Returning, Loyal)
Revenue contribution by age group

📊 Dashboard
An interactive Power BI dashboard was built to visualize:
Total customers, average purchase, and ratings
Revenue by category
Customer distribution by subscription
Sales and revenue by age group
(Dashboard preview available in the project files)


📈 Results & Insights
Male customers generated higher total revenue compared to female customers
Non-subscribers contributed more overall revenue despite similar average spending
Certain products showed high dependency on discounts
Loyal customers formed the majority segment
Young adults contributed the highest revenue among age groups

(Insights derived from SQL analysis and dashboard visuals in the report)
