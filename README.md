# SQL Data Analytics Project

## 📌 Overview
A comprehensive SQL data analytics project focused on data exploration, transformation, and reporting. This project demonstrates how to analyze structured data using SQL and apply data warehousing concepts.

It includes multiple datasets and SQL scripts to perform real-world business analysis such as customer segmentation, sales trends, and performance metrics.

---

## 📁 Project Structure

```
sql-data-analytics-project/
│
├── data/
│   ├── raw/                 # Original CSV files (bronze layer)
│   ├── staging/             # Cleaned data (silver layer)
│   └── warehouse/           # Final tables (gold layer)
│
├── scripts/
│   ├── 00_setup/
│   │   └── init_database.sql
│   │
│   ├── 01_staging/
│   │   ├── crm_cleaning.sql
│   │   └── erp_cleaning.sql
│   │
│   ├── 02_warehouse/
│   │   ├── dim_customers.sql
│   │   ├── dim_products.sql
│   │   └── fact_sales.sql
│   │
│   ├── 03_analysis/
│   │   ├── magnitude_analysis.sql
│   │   ├── ranking_analysis.sql
│   │   ├── cumulative_analysis.sql
│   │   └── segmentation.sql
│   │
│   └── 04_reporting/
│       ├── report_customers.sql
│       └── report_products.sql
│
├── docs/
│   └── analytics-workflow.png
│
├── DataWarehouseAnalytics.bak   
│
└── README.md
```




---

## ⚙️ Tools & Technologies
- SQL Server
- T-SQL
- Data Warehousing Concepts
- Git & GitHub

---

## 📊 Key Features
- Data cleaning and transformation
- Customer segmentation (VIP, Regular, New)
- Sales performance analysis
- Aggregations and reporting
- Time-based trend analysis

---

## 📁 Datasets
- Raw CSV files (Bronze layer)
- Processed datasets (Silver/Gold layers)
- SQL Server backup file (.bak)

---

## 🚀 How to Use

1. Restore the database using `.bak` file in SQL Server
2. Run SQL scripts from the `scripts` folder
3. Explore queries for analysis and reporting

---

## 📈 Sample Analysis
- Total sales by customer
- Monthly sales trends
- Top-performing products
- Customer purchase behavior

