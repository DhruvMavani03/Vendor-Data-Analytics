# Vendor-Data-Analytics

Vendor Data Analytics Dashboard

A comprehensive and interactive data analytics dashboard designed to analyze and visualize vendor, sales, and inventory performance.
The project integrates SQL Server, Python (via Apache connection), and data visualization tools to provide deep insights into vendor efficiency, purchase trends, profit margins, and overall business performance.

### 1. Project Overview

The Vendor Data Analytics Dashboard empowers business users, analysts, and management to interactively monitor key operational metrics related to vendor transactions, purchases, sales performance, and profitability.
This project enables stakeholders to make data-driven decisions by identifying top-performing vendors, low-performing brands, and overall supply chain efficiency through clear and actionable insights.

### 2. Tech Stack
•**MS SQL Server**: Used for storing, cleaning, and preprocessing data (including handling duplicates and nulls).
•**Apache & pyodbc**: Established a bridge between SQL Server and Python for seamless data integration.
•**Python (Jupyter Notebook)**: Used for data extraction, transformation, and exploratory analysis.
•**Power BI**: Utilized for dashboard development and data visualization.
•**Dataset**: A multi-table dataset downloaded from a YouTube analytics resource, containing vendor, sales, and inventory data across multiple CSV files.

### 3. Data Source and Preparation
The dataset consists of multiple CSV files representing various aspects of vendor operations:
• **begin_inventory.csv** – Opening inventory details
• **end_inventory.csv**– Closing inventory and stock comparison
• **purchase_prices.csv** – Item purchase price records
• **purchases.csv** – Vendor purchase transaction data
• **sales.csv** – Sales transactions and revenue information
• **vendor_invoice.csv** – Vendor billing and payment records
• **Vendor_Sales_Summary.csv** – Derived summary table for dashboard visualization
All files were first imported into MS SQL Server for cleaning, transformation, and integrity checks.
Using Python (via Apache connection), data was retrieved, merged, and processed to calculate KPIs like total sales, purchases, profit margins, and unsold capital.

### 4. Key Features and Insights
Business Problem: Organizations dealing with multiple vendors often struggle with tracking purchase efficiency, monitoring performance, and identifying profitable relationships.
Dashboard Goal: Provide a unified view of vendor and sales data for quick performance monitoring, purchase analysis, and profitability insights.

### 5. Dashboard Highlights
Key KPIs:
 • Total Sales ($441.41M)
 • Total Purchase ($307.34M)
 • Gross Profit ($134.07M)
 • Profit Margin (38.72%)
 • Unsold Capital ($2.71M)
 
**Purchase Contribution %**: Donut chart showing top 10 vendors by purchase share.

**Top Vendors by Sales**: Visualizing high-performing vendors based on total revenue.

**Low Performing Vendors**: Identifying vendors contributing the least to profit and sales.

**Low Performing Brands**: Scatter plot of total sales vs. profit margin to highlight underperforming brands.

**Operational Metrics**: Compare purchase vs. sales values, vendor margins, and inventory movement.


### 6. Business Impact
• Enhanced vendor evaluation through performance-based metrics.
• Improved inventory management by tracking beginning and ending stock trends.
• Supported data-backed purchasing decisions by comparing purchase vs. sales data.
• Increased profitability tracking and operational transparency across vendors and brands.

### 7. Project Workflow
• Import all CSV datasets into MS SQL Server.
• Clean and preprocess data (remove duplicates, standardize columns, handle null values).
• Connect Python to SQL Server using Apache and pyodbc.
• Extract and merge relevant tables using SQL queries and Pandas.
• Compute performance metrics — total sales, purchase, profit, margin, unsold capital.
• Export the cleaned dataset to Power BI or use Python’s visualization libraries to build dashboards.

### 8. Dashboard Snapshot
