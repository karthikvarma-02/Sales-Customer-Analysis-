# Sales Customer Analysis Data Warehouse

## Project Overview
This project demonstrates a SQL-based data warehouse designed for sales and customer analytics. 
The architecture follows the Medallion Architecture approach using Bronze, Silver, and Gold layers.

## Architecture
Bronze Layer – Raw CRM and ERP data  
Silver Layer – Cleaned and transformed data  
Gold Layer – Analytical views for reporting

## Gold Layer Views
dim_customers – Customer dimension table  
dim_products – Product dimension table  
fact_sales – Sales fact table

## Technologies Used
SQL Server  
Data Warehousing  
Star Schema Modeling

## Key Concepts
- Surrogate Keys using ROW_NUMBER()
- Dimension and Fact tables
- Medallion Architecture
- SQL Views for analytics

## Author
Karthik Varma
