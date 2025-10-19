# Business Sales Performance Analysis

Delivering actionable insights for retail sales performance, customer segmentation, and strategic decisions using SQL, Excel, and Power BI.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Research Questions & Key Findings](#research-questions--key-findings)
- [Visualizations & Insights](#visualizations--insights)
- [How to Run This Project](#how-to-run-this-project)
- [Final Recommendations](#final-recommendations)
- [Author & Contact](#author--contact)

---

## Overview

This project explores sales transaction data to reveal drivers of revenue, profitability, and customer loyalty in a retail business. Through systematic data cleaning in SQL and Excel and interactive dashboarding in Power BI, business decision-makers are equipped to optimize product strategy, target retention, and improve sales team execution.

---

## Business Problem

Retail organizations face the constant challenge of growing sales and maximizing profits. This project empowers business leaders to:
- Identify top and underperforming products, regions, and sales representatives
- Segment new versus returning customers for loyalty and retention analysis
- Track sales growth and profit margins over time
- Discover regional and quarterly patterns to guide inventory and marketing

---

## Dataset

- **Source**: Retail store sales transactions (2023)
- **Records**: Transaction-level sales data including sales rep, region, customer type, product category, sales amount, and quantity
- **Core Fields**: Sale_Date, Product_ID, Sales_Rep, Region, Sales_Amount, Quantity_Sold, Product_Category, Customer_Type, Unit_Cost, Unit_Price
- **Data Quality**: Cleaned in SQL and Excel, removing invalid records and standardizing types

---

## Tools & Technologies

- **Excel**: Initial assessment and manual data formatting
- **SQL**: Cleaning, aggregation (KPIs, profit, MoM/YoY growth), and derived column creation
- **Power BI**: Interactive dashboard with KPIs, visual comparisons, regional and segment insights
- **GitHub**: Project versioning and documentation

---

## Project Structure

sales-performance-analysis/
│
├── README.md
├── sales.csv
├── cleaned_sales.sql
├── dashboard/
│ └── sales_dashboard.pbix


---

## Data Cleaning & Preparation

### Data Quality Steps

- Removed invalid entries (zero/negative sales/quantity)
- Standardized categorical fields (customer type, product category)
- Converted date fields to proper datetime formats for time series analysis
- Calculated derived metrics (profit, margins, growth)
- Aggregated data by month, region, representative, and customer segment for dashboard visuals

---

## Exploratory Data Analysis (EDA)

### Analytical Approaches

- **Descriptive Statistics**: Distribution of sales by product category, region, and customer segment
- **Segmented Analysis**: Revenue and quantity comparisons for New vs Returning customers
- **Trend Analysis**: Month-over-month and year-over-year growth metrics
- **Sales Team Performance**: Total sales and contribution of individual representatives
- **Profitability Analysis**: Product profit margins and top revenue categories

---

## Research Questions & Key Findings

### 1. What drives sales revenue growth and profitability?
- Clothing and Furniture are leaders in total revenue and quantity sold.
- MoM Growth of 8.58% and Profit Margin of 9.22% show healthy business expansion.

### 2. How do customer segments impact business?
- Nearly equal revenue from New (51.9%) and Returning (48.1%) customers signals balanced retention and acquisition.
- Significant sales value contributed by returning customers highlights loyalty potential.

### 3. Where are market opportunities by region and representative?
- Regional trends and quarterly sales patterns inform where promotions and inventory should be focused.
- Top sales representatives can be modeled to drive increased team performance.

### 4. What are the cross-sectional insights by product and region?
- Category/Region matrix exposes high-performing products in specific areas, guiding location-based strategies.

---

## Visualizations & Insights

### Power BI Dashboard Highlights

- **KPIs**: MoM Growth %, Profit Margin, Total Sales, Quantity Sold
- **Bar Chart**: Top Products by Revenue
- **Pie Chart**: Sales split by New vs Returning customers
- **Line Chart**: Sales split by region and quarter
- **Matrix/Table**: Product category performance across regions
- **Slicers**: Filter by sales channel and customer type for granular analysis

*![Dashboard Overview](images/dashboard.jpg)*

---

## How to Run This Project

### Prerequisites

- SQL-compatible database (e.g., SQLite, SQL Server) for structured data
- Excel for initial inspection and formatting
- Power BI for visualization
- Download sales data (sales.csv) and dashboard (sales_dashboard.pbix)

### Setup Steps

1. **Download/cloning the repository**
2. **Load and clean sales.csv in SQL using provided queries**
3. **Export cleaned/aggregated tables to Power BI**
4. **Open sales_dashboard.pbix in Power BI Desktop**
5. **Explore and analyze with interactive visuals and filters**

---

## Final Recommendations

- Prioritize key categories for promotion and inventory investment
- Enhance loyalty program targeting for high-value returning customers
- Use regional and rep insights to allocate resources and set targets
- Monitor profit margins and growth KPIs for early signal trends
- Collect more granular customer and campaign data for advanced analytical capabilities

---

## Author & Contact

**Ganesh Rao**
Data Analyst

📧 Email: jganeshrao5@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/j-ganesh-rao-055ba2279)  
🐙 [GitHub](https://github.com/GaneshRaogit)  

---

*This project demonstrates professional sales analysis and dashboarding, focusing on deep business insights, strong SQL and Power BI skills, and actionable recommendations for retail strategy.*
