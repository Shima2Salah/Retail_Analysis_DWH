# Retail_Analysis_DWH
Retail Analytics ETL Pipeline Project Adapted for the Olist Brazilian E-Commerce

# 🛒 Retail Analytics Data Warehouse (ETL Pipeline)

## 📌 Project Overview
This project implements a complete **End-to-End ETL Pipeline & Data Warehouse** for retail analytics using the **Olist Brazilian E-Commerce dataset**.

The pipeline extracts raw data from CSV files, transforms it using ETL processes, and loads it into a **SQL Server Data Warehouse** designed using a **Star Schema**, making it ready for analytics and reporting.

---

## 🎯 Objectives
- Build a scalable ETL pipeline
- Apply **Medallion Architecture (Bronze, Silver, Gold)**
- Design a **Star Schema**
- Enable Business Intelligence reporting
- Ensure high data quality and consistency

---

## 📊 Dataset
The project is based on the Olist dataset which includes:
- Orders
- Order Items
- Customers
- Payments
- Reviews
- Products
- Sellers
- Geolocation
- Category Translation

---

# 🏗️ Architecture Overview

## 🟤 Bronze Layer (Raw Data)
Raw data ingestion with no transformation.

<img src="Images/Bronze layer.jpg" width="100%">

### 📂 Bronze Tables
<img src="Images/Bronze_olist_orders.jpg" width="100%">
<img src="Images/Bronze_olist_customers.jpg" width="50%">
<img src="Images/Bronze_olist_geolocation.jpg" width="50%">
<img src="Images/Bronze_olist_order_items.jpg" width="50%">
<img src="Images/Bronze_olist_payments.jpg" width="50%">
<img src="Images/Bronze_olist_products.jpg" width="50%">
<img src="Images/Bronze_olist_reviews.jpg" width="50%">
<img src="Images/Bronze_olist_sellers.jpg" width="50%">
<img src="Images/Bronze_olist_category_name_translation.jpg" width="50%">

---

## ⚪ Silver Layer (Clean & Transformed Data)
- Data cleaning
- Handling nulls
- Standardization
- Data integration across tables

<img src="Images/Silver Layer.JPG" width="100%">

### 📂 Silver Tables
<img src="Images/Silver_olist_customers.JPG" width="100%">
<img src="Images/Silver_olist_geolocation.jpg" width="50%">
<img src="Images/Silver_olist_order_items.JPG" width="50%">
<img src="Images/Silver_olist_orders.JPG" width="50%">
<img src="Images/Silver_olist_payments.JPG" width="50%">
<img src="Images/Silver_olist_product_category_name_translation.jpg" width="50%">
<img src="Images/Silver_olist_products.JPG" width="50%">
<img src="Images/Silver_olist_reviews.JPG" width="100%">
<img src="Images/Silver_olist_sellers.JPG" width="100%">

---

## 🟡 Gold Layer (Analytical Data - Star Schema)
- Aggregated data
- Fact & Dimension tables
- Optimized for analytics

<img src="Images/Gold Layer.JPG" width="100%">

### 📂 Gold Tables
<img src="Images/Gold_olist_order_items1.JPG" width="100%">
<img src="Images/Gold_olist_order_items-2.JPG" width="100%">
<img src="Images/Gold_olist_products.JPG" width="50%">
<img src="Images/Gold_olist_sellers.JPG" width="50%">
<img src="Images/Gold_olist_date.JPG" width="50%">
<img src="Images/Gold_olist_customers.JPG" width="50%">

---

# ⭐ Data Warehouse Design

## 🔸 Database Schema
<img src="Images/Database Diagram.JPG" width="100%">

## 🔸 Star Schema Model
<img src="Images/Data Model.JPG" width="100%">

---

# 🔄 ETL Process
1. Extract CSV files  
2. Load into SQL Server staging (Bronze)  
3. Transform into Silver layer  
4. Build Gold layer (Star Schema)  
5. Connect to Power BI  

---

# ⚙️ Technologies Used
- SQL Server
- SSIS (ETL)
- SQL
- Power BI
- Python (optional)
- GitHub

---

# ✅ Key Concepts Implemented
- ✔ Incremental Load  
- ✔ Surrogate Keys  
- ✔ Slowly Changing Dimensions (SCD Type 2)  
- ✔ Data Cleaning & Transformation  
- ✔ Data Quality Validation  

---

# 📊 Power BI Dashboard

## 📄 Dashboard Pages
<img src="Images/page1.JPG" width="100%">
<img src="Images/page2.JPG" width="100%">
<img src="Images/page3.JPG" width="100%">
<img src="Images/page4.JPG" width="100%">

---

# 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Shima2Salah/Retail_Analysis_DWH.git

<img src="Images/Database Diagram.JPG" width="100%">
<img src="Images/Bronze layer.jpg" width="100%">
<img src="Images/Bronze_olist_orders.jpg" width="100%">
<img src="Images/Bronze_olist_customers.jpg" width="50%">
<img src="Images/Bronze_olist_geolocation.jpg" width="50%">
<img src="Images/Bronze_olist_order_items.jpg" width="50%">
<img src="Images/Bronze_olist_payments.jpg" width="50%">
<img src="Images/Bronze_olist_products.jpg" width="50%">
<img src="Images/Bronze_olist_reviews.jpg" width="50%">
<img src="Images/Bronze_olist_sellers.jpg" width="50%">
<img src="Images/Bronze_olist_category_name_translation.jpg" width="50%">
<img src="Images/Silver Layer.JPG" width="100%">
<img src="Images/Silver_olist_customers.JPG" width="100%">
<img src="Images/Silver_olist_geolocation.jpg" width="50%">
<img src="Images/Silver_olist_order_items.JPG" width="50%">
<img src="Images/Silver_olist_orders.JPG" width="50%">
<img src="Images/Silver_olist_payments.JPG" width="50%">
<img src="Images/Silver_olist_product_category_name_translation.jpg" width="50%">
<img src="Images/Silver_olist_products.JPG" width="50%">
<img src="Images/Silver_olist_reviews.JPG" width="100%">
<img src="Images/Silver_olist_sellers.JPG" width="100%">
<img src="Images/Gold Layer.JPG" width="100%">
<img src="Images/Gold_olist_order_items1.JPG" width="100%">
<img src="Images/Gold_olist_order_items-2.JPG" width="100%">
<img src="Images/Gold_olist_products.JPG" width="50%">
<img src="Images/Gold_olist_sellers.JPG" width="50%">
<img src="Images/Gold_olist_date.JPG" width="50%">
<img src="Images/Gold_olist_customers.JPG" width="50%">

<img src="Images/Data Model.JPG" width="100%">
<img src="Images/page1.JPG" width="100%">
<img src="Images/page2.JPG" width="100%">
<img src="Images/page3.JPG" width="100%">
<img src="Images/page4.JPG" width="100%">
