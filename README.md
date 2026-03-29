# Data Warehouse and Analytics Project
Welcome to the "Data Warehouse and Analytics Project** repository !

# 🏗️ SQL Data Warehouse Project (Bronze-Silver-Gold Architecture)

## 📌 Overview

This project demonstrates the design and implementation of a **Data Warehouse using Medallion Architecture (Bronze, Silver, Gold layers)**.
It involves ingesting raw CRM and ERP data, transforming it into clean datasets, and building analytical models for reporting.

---

## 🧱 Architecture

* **Bronze Layer** → Raw data ingestion using BULK INSERT
* **Silver Layer** → Data cleaning, transformation, and standardization
* **Gold Layer** → Business-ready data model (Fact & Dimension tables)

---

## ⚙️ Technologies Used

* SQL Server
* T-SQL (Stored Procedures, Joins, CTEs)
* Power BI (Dashboard & Visualization)
* GitHub (Version Control)

---

## 🔄 ETL Process

### 🔹 Bronze Layer

* Loaded raw CSV files into SQL Server using `BULK INSERT`
* Used `TABLOCK` for performance optimization
* Implemented stored procedures for automation

### 🔹 Silver Layer

* Cleaned and transformed data
* Handled NULL values and duplicates
* Converted data types using `TRY_CAST` and `TRY_CONVERT`

### 🔹 Gold Layer

* Designed Star Schema (Fact & Dimension tables)
* Created business KPIs for reporting

---

## 📊 Key Features

* Automated ETL pipeline using Stored Procedures
* Error handling using TRY-CATCH
* Optimized bulk loading techniques
* Scalable data model for analytics

---

## 📈 Power BI Dashboard

* Sales Analysis
* Customer Insights
* Product Performance

---

## 🚀 How to Run

1. Execute database creation script
2. Run Bronze layer procedure
3. Run Silver transformation scripts
4. Run Gold layer scripts
5. Connect Power BI dashboard

---

## 💡 Key Learnings

* Data Warehouse design principles
* ETL pipeline development
* Data cleaning & transformation
* Performance optimization in SQL

---

## 📬 Contact

Feel free to connect for feedback

