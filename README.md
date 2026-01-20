# Retail Sales Analytics Dashboard (SQL & PowerBI)

## Project Overview
This project is an end-to-end retail analytics solution built using SQL and PowerBI. The objective is to transform raw transactional data into meaningful business insights related to sales performance, product trends, customer behaviour, and payment patterns.

The entire dataset was self-generated, modelled in SQL, cleaned, and visualized using PowerBI with interactive dashboards.

---

## Business Objectives
- Analyse overall sales and revenue trends  
- Identify top-performing products and categories  
- Understand customer contribution and geographic distribution  
- Analyse payment mode preferences  
- Support data-driven decision-making through dashboards  

---

## Dataset Description
The project uses 5 interrelated tables:

| Table Name   | Description                     | Rows   |
|-------------|----------------------------------|--------|
| customers    | Customer demographic data        | ~1,000 |
| products     | Product category with pricing    | ~100   |
| orders       | Customer orders                  | ~2,000 |
| order_items  | Order-level product details      | ~5,000 |
| payments     | Payment transactions             | ~1,200 |

---

## Data Model
- Fact Table: order_items  
- Dimension Tables: customers, products, orders, payments  
- Relationships created using primary and foreign keys  
- Star-schema style modelling implemented in PowerBI  

---

## Data Preparation
- Data cleaning performed in Power Query  
- Removed duplicates and handled null values  
- Standardized date formats and data types  
- Created calculated columns and measures using DAX  

---

## Key Metrics (DAX)
- Total Revenue  
- Total Orders  
- Total Quantity Sold  
- Average Order Value (AOV)  
- Top-N Products & Customers  

---

## Dashboards Overview

### 1. Executive Sales Overview
- KPI Cards: Revenue, Orders, Quantity, AOV  
- Monthly Revenue Trend  
- Revenue by Category  
- Interactive slicers for Year and Order Status  

### 2. Product Performance Analysis
- Top 10 Products by Revenue  
- Category-wise Revenue & Quantity (Combo Chart)  
- Category filtering for focused analysis  

### 3. Customer & Payment Insights
- Top 10 Customers by Revenue  
- Revenue by City  
- Payment Mode Distribution  

---

## Key Business Insights
- Revenue is highly concentrated among top 10 products and customers  
- Certain categories generate high revenue with lower quantities, indicating premium pricing  
- Monthly revenue shows fluctuations suggesting possible seasonality  
- Digital payment modes (UPI) dominate transactions  

---

## Tools & Technologies
- SQL: Schema design, joins, aggregations  
- PowerBI: Data modelling, DAX, interactive dashboards  
- Excel / CSV: Data generation and storage  

---
```
## Project Folder Structure
Retail-Analytics-Powerbi/
│
├── data/
│ ├── customers.csv
│ ├── products.csv
│ ├── orders.csv
│ ├── order_items.csv
│ └── payments.csv
│
├── sql/
│ └── retail_schema.sql
│
├── powerbi/
│ └── Retail_Analytics_EndToEnd.pbix
│
├── screenshots/
│ ├── executive_dashboard.png
│ ├── product_analysis.png
│ └── customer_payments.png
│
└── README.md
```

---

## How to Use
1. Clone the repository  
2. Open the .pbix file in PowerBI Desktop  
3. Load CSV files if required  
4. Explore dashboards using slicers and filters  

---

## Author
**Divyy Pratap**    
Data Analyst | SQL • PowerBI • Excel
