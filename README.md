# 🛒 End-to-End E-Commerce Lakehouse Project using Databricks

## 📌 Overview
This project implements a complete **Lakehouse architecture** using Databricks on the **Olist Brazilian E-Commerce dataset**.  
It integrates data from multiple sources and transforms it into meaningful business insights.

---

## 🎯 Business Problem
The company stores customer, order, product, and payment data in separate systems, making it difficult to:
- Track total revenue
- Analyze customer behavior
- Identify best-selling products
- Monitor sales trends

This project builds a **single source of truth** using a Lakehouse solution.

---

## 📂 Dataset
- Source: Olist Brazilian E-Commerce Dataset (Kaggle)
- Records: ~110,000+ orders

### Tables Used:
- customers
- orders
- order_items
- order_payments
- products

---

## 🏗️ Architecture
This project follows the **Medallion Architecture (Bronze, Silver, Gold)**

### 🥉 Bronze Layer
- Raw data ingestion from CSV files
- Stored as Delta tables

### 🥈 Silver Layer
- Data cleaning and transformation
- Handling null values and duplicates
- Joining multiple tables

### 🥇 Gold Layer
- Aggregated data for analytics
- Business-level insights

---

## ⚙️ Technologies Used
- Databricks
- PySpark
- SQL
- Delta Lake

---

## 🔄 Workflow
1. Load data into Bronze layer  
2. Clean and transform data in Silver layer  
3. Join datasets  
4. Perform Delta operations (MERGE, UPDATE, DELETE)  
5. Apply Schema Evolution and Time Travel  
6. Build Gold layer for analytics  

---

## 📈 Key Insights
- Total Revenue
- Top Customers
- Best Selling Products
- Sales Trends
- Payment Analysis
- Customer Insights

---

## 🚀 How to Run
1. Upload dataset to Databricks
2. Create Bronze tables using PySpark
3. Transform data into Silver layer
4. Create Gold tables using SQL
5. Run queries to generate insights

---

## 🧠 Learnings
- Lakehouse Architecture (Bronze-Silver-Gold)
- Delta Lake operations
- Data transformation using PySpark
- Real-world data engineering pipeline

