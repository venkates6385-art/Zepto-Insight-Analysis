Project Overview
This project focuses on analyzing and cleaning a Zepto product dataset using SQL. The goal is to ensure data quality, identify pricing issues, analyze stock availability, and derive meaningful business insights such as category-wise revenue and discount trends.
The project demonstrates strong SQL fundamentals, including table creation, data validation, data cleaning, aggregation, and analytical queries.

Dataset Description

The dataset contains product-level details from Zepto, including:
SKU ID
Product Category
Product Name
MRP (Maximum Retail Price)
Discount Percentage
Available Quantity
Discounted Selling Price
Product Weight
Stock Availability
Quantity

Tools & Technologies
Database: PostgreSQL
Language: SQL
Data Source: CSV file

Table Creation
A structured table named Zepto was created to match the dataset schema.
Key features:
SKU_id as a Primary Key
Appropriate data types for numeric, text, and boolean values
Constraints applied where necessary (e.g., NOT NULL)

Data Import
Data was imported from a CSV file into the PostgreSQL table.
Row count verification was performed to ensure successful import.

The following checks were conducted:
Identification of NULL values across critical columns
Verification of unique product categories
Detection of duplicate product names
Identification of invalid pricing data (MRP or discounted price equal to zero)

Data Cleaning
Removed records with invalid MRP values
Corrected pricing values by converting them into the proper currency format
Ensured consistent and reliable pricing data for analysis

Analysis & Insights
🔹 Stock Analysis
Counted out-of-stock vs in-stock products
Identified high-priced products (> ₹300) that are out of stock
🔹 Pricing & Discounts
Extracted top 10 products with the highest discounts
Found the maximum product price in the dataset
Identified pricing inconsistencies and corrected them

Key Outcomes
Cleaned and validated real-world product data
Identified revenue-driving categories
Highlighted stock and pricing inefficiencies
Demonstrated practical SQL skills used in data analyst roles
