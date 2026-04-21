# E-commerce Customer Analytics & Segmentation Dashboard (Power BI)

# Overview
This project analyzes e-commerce transactional data to uncover insights into customer behavior, revenue trends, and retention patterns.
The dashboard is built using Power BI and leverages DAX for advanced analytics, including cohort analysis and RFM-based customer segmentation.

The goal is to transform raw transaction data into actionable business insights that can support decision-making in customer retention, marketing, and revenue growth.

# Business Problem
E-commerce businesses often struggle to answer key questions such as:

1.Are customers returning after their first purchase?
2.Who are the most valuable customers?
3.How does customer behavior change over time?
4.What drives revenue growth — new customers or repeat customers?

This project addresses these questions by building a comprehensive analytics dashboard.

# Dataset Used
Online Retail Dataset by UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/352/online+retail

# Tools Used
1.Power BI
2.DAX (Data Analysis Expressions)
3.Power Query (Data Cleaning & Transformation)
4.Excel (Data Source)

# Process
1.Cleaned and transformed raw transactional data using Power Query by handling missing values, invalid records, and fixing data types
2.Built a data model with fact and dimension tables, including a dedicated date table
3.Created DAX measures for key metrics such as revenue, orders, customers, and average order value
4.Developed customer-level analysis including new vs repeat customers and cohort-based retention tracking
5.Implemented RFM-based customer segmentation and designed an interactive multi-page dashboard for insights

# Customer Segments

Customers were segmented using RFM logic into:

High Value → High spend and high purchase frequency
Loyal → Frequent buyers with moderate spend
At Risk → Customers inactive for a long time
Low Value → Low spend and low engagement

# Key Insights
Revenue growth is primarily driven by repeat customers rather than new acquisitions
High-value customers contribute a significant portion of total revenue
Customer retention declines after the first purchase, as seen in cohort analysis
A large portion of customers fall into inactive (high recency) segments
Average Order Value shows an increasing trend in later months

# Key Takeaways
Retaining existing customers is more impactful than acquiring new ones
Identifying high-value customers enables targeted marketing strategies
Cohort analysis is essential to understand long-term customer behavior
Customer segmentation helps prioritize business efforts effectively

# Project Structure
```
customer-analytics-powerbi/
|
|-- data/
|   |-- sample_data.xlsx
|
|-- dashboard/
|   |-- customer-analysis.pbix
|
|-- screenshots/
|   |-- trend_over_months.png
|   |-- customer_segmentation.png
|
|-- README.md

```

# How to run
Download or clone this repository
Open the customer-analysis.pbix file in Power BI Desktop
Refresh the data (if needed)
Navigate through report pages:
1.Trend over months
2.Customer Segmentation

# Note
The dataset used is historical (2010–2011), and recency calculations are based on the latest transaction date in the dataset rather than the current date.
