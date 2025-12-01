# Customer-Shopping-Behaviour-Data-Analysis
# Overview
  This project analyzes customer shopping behavior using a complete data-analytics workflow. <br>
  It covers data loading, exploratory data analysis (EDA), cleaning, SQL-based analysis, and creating an interactive Power BI dashboard for insights.<br>
  The goal is to uncover patterns in purchasing behavior, identify high-value customer segments, and provide actionable insights for business decision-making.<br>

# Dataset
  Rows: 3,900 records<br>
  Columns: 18<br>
  Type: Customer demographics, purchase details, ratings, shipping preferences, subscription info<br>
  Missing Values: Only in the Review Rating column (handled using median imputation)<br>
  The dataset was used to generate insights such as purchase trends, customer segmentation, revenue patterns, and product-level behavior.<br>

# Tools & Technologies
  Python: Pandas <br>
  MySQL: SQL analysis and querying <br>
  Power BI: Interactive dashboard creation <br>
  Jupyter Notebook / VS Code: Development and analysis environment <br>

# Project Steps
1. Data Loading <br>
Loaded the dataset using pandas <br>
Verified structure, data types, and summary statistics<br>

2. Exploratory Data Analysis (EDA)<br>
Univariate and bivariate analysis<br>
Distribution of purchase amount, age, ratings, etc.<br>
Gender-wise revenue comparison<br>
Shipping preference and spending insights<br>

3. Data Cleaning<br>
Handled missing values<br>
Removed inconsistent records<br>
Created new features such as:
  - Age groups<br>
  - Purchase frequency segments<br>
  - Discount usage metrics<br>

4. SQL Analysis (MySQL)<br>
Executed several SQL queries such as:<br>
  Top products by revenue<br>
  Highest discount users<br>
  Customer segmentation using SQL logic<br>
  Average spend by subscription type<br>
  Shipping preference spend analysis<br>

5. Power BI Dashboard <br>
An interactive dashboard was built to visualize:<br>
  Revenue by gender<br>
  High-value discount users<br>
  Top-rated products<br>
  Customer segmentation breakdown<br>
  Subscription-based performance<br>
  Shipping preference vs revenue<br>
<br>
The dashboard helps stakeholders interpret complex data quickly and make decisions. <br>

# Key Results & Insights

Female customers contribute slightly higher total revenue than male customers. <br>
Express shipping users spend ~12% more per purchase.<br>
Subscribers account for 45% of revenue with higher loyalty rates. <br>
Top-rated products (Blouse, Dress, Shirt) have consistently strong performance. <br>
Customer segments identified: 
- Loyal (15%) – highest value <br>
- Returning (35%) – steady revenue<br>
- New (50%) – high potential for conversion
<br>
These insights can guide marketing strategies, loyalty campaigns, and product promotions. <br>

