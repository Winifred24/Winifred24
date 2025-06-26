 Introduction
This Power BI project aims to explore and analyze a retail sales dataset, offering key insights into regional performance, product category trends, shipping behaviors, and profit contributions. The project simulates real-world business intelligence reporting and demonstrates core Power BI competencies.

 Problem Statement
Retail businesses often struggle to identify which products, regions, and customer segments are the most profitable. The goal of this project is to analyze sales data to help the business:

Identify top-performing product categories and subcategories.

Understand regional sales distribution.

Analyze profit margins by state.

Evaluate shipping methods and delivery timelines.

Detect patterns that support data-driven business decisions.
Data Sourcing
The data was extracted from a simulated sales dataset containing the following key fields:

Order_Date, Ship_Date

Ship_Mode, Postal_Code, Region, State

Product_Reference, Category, Sub_Category

Sales, Quantity, Profit

The dataset was stored in a CSV format and imported into Power BI for analysis.

Data Transformation and Cleaning
Using Power Query in Power BI, the following steps were applied:

Converted Order_Date and Ship_Date columns to Date types.

Removed duplicate records.

Cleaned inconsistencies in Category and Sub_Category naming.

Ensured numerical columns like Sales, Profit, and Quantity were properly typed.

Created new calculated columns like Shipping Duration (difference between Ship_Date and Order_Date).

Validated that each Product_Reference aligned with expected categories.

Data Modeling
Relationships were established between fact and dimension tables:

Created Date table for time intelligence.

Linked Region and State to geography dimensions.

Measures were added using DAX for:

Total Sales

Total Profit

Profit Margin

Quantity Sold

Average Shipping Time

Categories and subcategories were set as hierarchies for drill-down capability in visuals.
