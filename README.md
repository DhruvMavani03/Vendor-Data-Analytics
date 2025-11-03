# Vendor-Data-Analytics

### Vendor Data Analytics Dashboard

A comprehensive and interactive data analytics dashboard designed to analyze and visualize vendor, sales, and inventory performance.
The project integrates SQL Server, Python (via Apache connection), and data visualization tools to provide deep insights into vendor efficiency, purchase trends, profit margins, and overall business performance.

### 1. Project Overview

The Vendor Data Analytics Dashboard empowers business users, analysts, and management to interactively monitor key operational metrics related to vendor transactions, purchases, sales performance, and profitability.
This project enables stakeholders to make data-driven decisions by identifying top-performing vendors, low-performing brands, and overall supply chain efficiency through clear and actionable insights.

### 2. Tech Stack
 • **MS SQL Server**: Used for storing, cleaning, and preprocessing data (including handling duplicates and nulls).<br>
 • **Apache & pyodbc**: Established a bridge between SQL Server and Python for seamless data integration.<br>
 • **Python (Jupyter Notebook)**: Used for data extraction, transformation, and exploratory analysis.<br>
 • **Power BI**: Utilized for dashboard development and data visualization.<br>
 • **Dataset**: A multi-table dataset downloaded from a YouTube analytics resource, containing vendor, sales, and inventory data across multiple CSV files.<br>

### 3. Data Source and Preparation
The dataset consists of multiple CSV files representing various aspects of vendor operations:<br>
 • **begin_inventory.csv** – Opening inventory details<br>
 • **end_inventory.csv**– Closing inventory and stock comparison<br>
 • **purchase_prices.csv** – Item purchase price records<br>
 • **purchases.csv** – Vendor purchase transaction data<br>
 • **sales.csv** – Sales transactions and revenue information<br>
 • **vendor_invoice.csv** – Vendor billing and payment records<br>
 • **Vendor_Sales_Summary.csv** – Derived summary table for dashboard visualization<br>

All files were first imported into MS SQL Server for cleaning, transformation, and integrity checks.<br>
Using Python (via Apache connection), data was retrieved, merged, and processed to calculate KPIs like total sales, purchases, profit margins, and unsold capital

### 4. Key Features and Insights
Business Problem: Organizations dealing with multiple vendors often struggle with tracking purchase efficiency, monitoring performance, and identifying profitable relationships.<br>
Dashboard Goal: Provide a unified view of vendor and sales data for quick performance monitoring, purchase analysis, and profitability insights.

### 5. Dashboard Highlights
Key KPIs:
 • Total Sales ($441.41M)
 • Total Purchase ($307.34M)
 • Gross Profit ($134.07M)
 • Profit Margin (38.72%)
 • Unsold Capital ($2.71M)<br>
 
**Purchase Contribution %**: Donut chart showing top 10 vendors by purchase share.<br>

**Top Vendors by Sales**: Visualizing high-performing vendors based on total revenue.<br>

**Low Performing Vendors**: Identifying vendors contributing the least to profit and sales.<br>

**Low Performing Brands**: Scatter plot of total sales vs. profit margin to highlight underperforming brands.<br>

**Operational Metrics**: Compare purchase vs. sales values, vendor margins, and inventory movement.<br>


### 6. Business Impact
 • Enhanced vendor evaluation through performance-based metrics.<br>
 • Improved inventory management by tracking beginning and ending stock trends.<br>
 • Supported data-backed purchasing decisions by comparing purchase vs. sales data.<br>
 • Increased profitability tracking and operational transparency across vendors and brands.<br>

### 7. Project Workflow
 • Import all CSV datasets into MS SQL Server.<br>
 • Clean and preprocess data (remove duplicates, standardize columns, handle null values).<br>
 • Connect Python to SQL Server using Apache and pyodbc.<br>
 • Extract and merge relevant tables using SQL queries and Pandas.<br>
 • Compute performance metrics — total sales, purchase, profit, margin, unsold capital.<br>
 • Export the cleaned dataset to Power BI or use Python’s visualization libraries to build dashboards.<br>

### 8. Dashboard Snapshot
![Dashborad Image](https://github.com/DhruvMavani03/Vendor-Data-Analytics/blob/main/Dashboard%20Snapshot.png)
