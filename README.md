# \# Online Retail Sales \& Customer Analytics

# 

# \## Project Overview

# 

# This project is an end-to-end Data Analytics project based on the UCI Online Retail dataset. The objective is to analyze retail transaction data and identify important patterns in sales performance, customer behavior, product demand, purchasing time, and geographical markets.

# 

# The project covers the complete analytics workflow, including data preparation, exploratory data analysis, data visualization, Power BI dashboard development, business insights, and recommendations.

# 

# \---

# 

# \## Problem Statement

# 

# The business has a large volume of transaction data but needs to better understand its sales performance, customer purchasing behavior, product performance, and geographical revenue distribution.

# 

# The project aims to answer questions such as:

# 

# \- What are the overall sales and order performance?

# \- Which countries generate the most revenue?

# \- Which products perform best?

# \- When are customers most active?

# \- What important relationships exist within the transaction data?

# \- What business actions can be taken based on the analysis?

# 

# \---

# 

# \## Project Objectives

# 

# 1\. Analyze retail transaction data.

# 2\. Clean and prepare the dataset for analysis.

# 3\. Perform exploratory data analysis using Python.

# 4\. Identify important trends and patterns.

# 5\. Create meaningful visualizations.

# 6\. Develop an interactive Power BI dashboard.

# 7\. Generate business insights and recommendations.

# 8\. Document the project using GitHub.

# 

# \---

# 

# \## Dataset Description

# 

# \### Dataset Name

# 

# UCI Online Retail Dataset

# 

# \### Dataset Type

# 

# Online retail transaction data.

# 

# \### Original Dataset

# 

# The original dataset contains transaction-level information including:

# 

# \- InvoiceNo

# \- StockCode

# \- Description

# \- Quantity

# \- InvoiceDate

# \- UnitPrice

# \- CustomerID

# \- Country

# 

# The original dataset contains 541,909 transaction records.

# 

# \### Prepared Dataset

# 

# After data cleaning and feature engineering, the analytical dataset contains 524,878 records and 15 columns.

# 

# Additional analytical fields include:

# 

# \- SalesAmount

# \- Year

# \- Month

# \- MonthName

# \- Day

# \- DayOfWeek

# \- Hour

# 

# \---

# 

# \## Tools Used

# 

# \- Python

# \- Pandas

# \- NumPy

# \- Matplotlib

# \- Seaborn

# \- Power BI

# \- Git

# \- GitHub

# \- Jupyter Notebook

# 

# \---

# 

# \## Project Structure

# 

# ```text

# online-retail-sales-analytics/

# │

# ├── Data/

# │   ├── Raw/

# │   │   └── Online Retail.xlsx

# │   │

# │   └── Processed/

# │       ├── Online\_Retail\_Cleaned.xlsx

# │       └── Online\_Retail\_Cleaned.csv

# │

# ├── Notebook/

# │   └── Online\_Retail\_EDA.ipynb

# │

# ├── Visualizations/

# │

# ├── Power BI/

# │   └── Online\_Retail\_Sales\_Analytics.pbix

# │

# ├── Presentation/

# │

# ├── Report/

# │

# └── README.md







# Data Cleaning Process

# 

# The original dataset was inspected for missing values, duplicates, invalid transactions, and inconsistent records.

# 

# Cleaning steps performed

# Duplicate rows were identified and removed.

# Records with missing product descriptions were removed.

# Cancelled transactions were excluded from the sales-analysis dataset.

# Records with non-positive quantities were removed.

# Records with non-positive unit prices were removed.

# Missing CustomerID values were retained for transaction-level analysis because those records can still contribute to sales, product, country, and time-based analysis.

# InvoiceDate was confirmed as a datetime field.

# SalesAmount was calculated as:

# SalesAmount = Quantity × UnitPrice

# Additional date-related fields were created for analysis.

# Exploratory Data Analysis

# 

# The EDA was performed using Python and included:

# 

# Dataset inspection

# Descriptive statistics

# Sales performance analysis

# Country analysis

# Product analysis

# Customer analysis

# Day-of-week analysis

# Hourly sales analysis

# Correlation analysis

# Outlier analysis

# Key EDA Metrics

# Metric	Value

# Total Revenue	Approximately £10.64M

# Total Orders	Approximately 19,960

# Total Units Sold	Approximately 5.57M

# Unique Customers	4,338

# Unique Products	3,922

# Countries	38

# Average Order Value	Approximately £533

# UK Revenue Share	Approximately 84.59%

# Data Visualizations

# 

# The project includes visualizations for:

# 

# Monthly Sales Trend

# Top 10 Countries by Sales

# Top 10 Products by Sales

# Sales by Day of Week

# Sales by Hour of Day

# Correlation Matrix

# Outlier Analysis

# 

# These visualizations were created to communicate major trends, comparisons, and relationships in the dataset.

# 

# Power BI Dashboard

# 

# An interactive Power BI dashboard was developed to provide a business-oriented view of the dataset.

# 

# Dashboard KPIs

# Total Revenue

# Total Orders

# Unique Customers

# Average Order Value

# Units Sold

# Countries Served

# Dashboard Visualizations

# Monthly Sales Trend

# UK vs Rest of World Revenue

# Top Countries by Revenue

# Top Products by Revenue

# Sales by Day of Week

# Sales by Hour

# Customer Mix

# Top Products by Units Sold

# Dashboard Filters

# Country

# Year

# Month

# Key Business Insights

# 1\. Overall Sales Performance

# 

# The cleaned dataset generated approximately £10.64 million in revenue across nearly 20,000 unique invoices.

# 

# 2\. UK Market Dominance

# 

# The United Kingdom contributes approximately 84.59% of total revenue, making it the dominant market.

# 

# 3\. Strong Year-End Sales

# 

# November 2011 recorded the highest monthly sales, at approximately £1.50 million.

# 

# 4\. Product Revenue Concentration

# 

# A relatively small group of products contributes a significant share of revenue, particularly among gift, household, and decorative products.

# 

# 5\. Quantity and Revenue Relationship

# 

# Quantity has a strong positive correlation with SalesAmount, at approximately 0.91.

# 

# 6\. Customer Data Availability

# 

# Approximately 25.18% of cleaned transactions do not contain a CustomerID, which limits complete customer-level analysis.

# 

# 7\. Purchasing Patterns

# 

# Sales activity is concentrated during daytime hours, and some weekdays perform significantly better than others.

# 

# Business Recommendations

# 1\. Expand International Markets

# 

# The business should reduce its dependence on the UK by targeting high-potential international markets such as the Netherlands, EIRE, Germany, and France.

# 

# 2\. Strengthen Seasonal Planning

# 

# Inventory, promotional campaigns, and operational planning should be strengthened before the year-end period, particularly before November.

# 

# 3\. Focus on High-Performing Products

# 

# High-revenue products should receive greater promotional attention, adequate stock coverage, and cross-selling opportunities.

# 

# 4\. Improve Customer Data Capture

# 

# Improving CustomerID collection would support stronger customer segmentation, retention analysis, personalized marketing, and future customer lifetime value analysis.

# 

# Conclusion

# 

# The analysis demonstrates that the online retail business has strong overall revenue performance but is highly dependent on the United Kingdom market.

# 

# The dataset also shows clear seasonal purchasing patterns and a concentration of revenue among high-performing products.

# 

# The findings suggest that international market expansion, improved seasonal planning, product-focused strategies, and better customer data capture could support future business growth and more effective decision-making.

# 

# Project Deliverables

# 

# The repository contains:

# 

# Raw dataset

# Cleaned dataset

# Python/Jupyter Notebook

# Data visualizations

# Power BI dashboard

# Presentation

# Project documentation



# 



# \## Author

# 

# \*\*Omkar Pujari\*\*  

# MBA in Business Analytics | AISSMS Institute of Management Studies  

# Data Analytics Internship — Week 6 Final Capstone Project

