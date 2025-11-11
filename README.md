# ☕ Coffee Shop Sales Performance

## Coffee Shop Sales Power BI Dashboard

This project presents an end-to-end data analysis using Power BI on a coffee shop sales dataset. The goal is to analyze overall business performance by tracking sales, quantity sold, and order trends, while identifying top-performing products, locations, and time-based patterns.

## Tools & Technologies Used

- **Power BI Desktop** – Dashboard design & KPI visualization

- **Power Query Editor** – Data transformation and cleaning

- **MySQL** – Data querying and aggregation

- **Excel** (CSV) – Source format used for data extraction and preview

- **DAX** (Data Analysis Expressions) – KPI creation and calculated metrics

## Dataset Description

Includes daily transactional data from multiple coffee shop outlets with the following details:

- Transaction Date and Time

- Product Category and Product Type

- Store Location (Hell’s Kitchen, Lower Manhattan, Astoria)

- Quantity Sold and Unit Price

- Total Orders and Sales Amount

### Steps Followed

### 1. Data Collection

- Received raw CSV dataset containing coffee shop transactions.

- Loaded and verified in MySQL for cleaning and date/time formatting.

### 2. Data Transformation & Cleaning

- Converted transaction_date and transaction_time columns into correct DATE and TIME formats using SQL.

- Removed inconsistencies and null records.

- Verified total sales calculations as unit_price * transaction_qty.

### 3. Data Import into Power BI

- Connected MySQL database to Power BI using native connector.

- Loaded fact tables for transactional data and built calendar table for date hierarchy.

- Used Power Query for additional shaping and DAX for KPI measures.

### 4. Dashboard Creation

Developed a single interactive dashboard with multiple perspectives:

- KPI Summary

- Sales by Store Location

- Sales by Product Category & Product Type

- Daily & Hourly Sales Trend

- Weekday vs Weekend Sales

## Dashboard Overview

### Objective:

Monitor and compare monthly sales performance across store branches, identify high-performing product categories, and evaluate customer purchase trends based on time and location.

### KPIs & Metrics:

- **Total Sales:** $76K (▼ -6.8% vs previous month)

- **Total Orders:** 16K (▼ -5.5%)

- **Total Quantity Sold:** 24K (▼ -5.3%)

- **Average Daily Sales:** $2.7K

### Key Visuals:

- **Sales by Store Location:** Top locations – Hell’s Kitchen ($25.7K), Lower Manhattan ($25.3K), Astoria ($25.1K)

- **Sales by Product Category:** Coffee ($29.3K), Tea ($21.7K), Bakery ($9.0K), Drinking Chocolate ($8.1K)

- **Top Products:** Barista Espresso ($10K), Brewed Chai Tea ($8.4K), Hot Chocolate ($8.1K)

- **Sales by Weekday vs Weekend:** Weekdays – 70.9% ($54K); Weekends – 29.1% ($22K)

- **Hourly Heatmap:** Highest sales between 8 AM and 11 AM

### Key Insights

- **Sales Dip:** Overall sales decreased by 6.8% compared to the last month, affecting all three store locations.

- **Customer Behavior:** Weekday mornings saw peak sales due to work-hour beverage demand.

- **Top Performing Items:** Coffee and Tea together contributed over 65% of total sales.

- **Store Comparison:** All stores performed similarly; Hell’s Kitchen slightly led.

- **Growth Opportunity:** Packaged and branded products showed low sales—potential for promotional bundles.

- **Operational Insight:** Staffing and inventory can be optimized during morning rush hours.

## Screenshot

### Coffee Shop Sales Dashboard

<img width="1789" height="1006" alt="Coffee Shop Sales Power BI Dashboard" src="https://github.com/user-attachments/assets/007674ca-954b-4815-91c0-7511fc52f879" />

<img width="1207" height="903" alt="Tooltip_1" src="https://github.com/user-attachments/assets/ded20791-17d8-48a1-bd7c-307a9985550f" />

<img width="1210" height="900" alt="Tooltip_2" src="https://github.com/user-attachments/assets/b1212baa-1ec5-44fa-b73b-3d0e4ebc9566" />


