# E-Commerce Data Pipeline Project – PySpark, SQL & Databricks

## 📖 Project Overview
This project demonstrates an end-to-end Data Engineering pipeline built using PySpark, SQL, and Databricks.  
The goal is to process raw e-commerce data and transform it into analytics-ready datasets using the Bronze–Silver–Gold (Medallion) architecture.

---

## 🏗️ Architecture
Bronze → Silver → Gold (Medallion Architecture)

- **Bronze Layer:** Raw data ingestion
- **Silver Layer:** Cleaned and transformed data
- **Gold Layer:** Aggregated data for analytics and reporting

---

## ⚙️ Tech Stack
- PySpark
- SQL (Databricks SQL)
- Databricks
- Delta Lake
- Data Warehousing Concepts

---

## 📂 Data Pipeline Flow
1. Ingest raw e-commerce data into Bronze tables
2. Clean and standardize data in Silver layer using PySpark
3. Perform aggregations and business logic using SQL
4. Create Gold tables for analytics
5. Build dashboards to visualize insights

---

## 🧪 Data Processing Details
- Data cleaning and null handling
- Type casting and column standardization
- Aggregations using SQL (GROUP BY, SUM, COUNT)
- Optimized Spark transformations

---

## 📊 Analytics & Dashboards
The project includes dashboards showing:
- Day-wise sales trends
- Month-wise revenue analysis
- Transaction volume patterns
- Net amount insights

---

## 🧠 Key Learnings
- Hands-on experience with PySpark and distributed data processing
- Practical use of SQL in large-scale analytics
- Understanding of Medallion Architecture
- Working with Delta Lake tables on Databricks
- End-to-end data engineering workflow

---

## 🚀 How to Run
1. Upload the dataset to Databricks File System (DBFS)
2. Run the Bronze notebook to ingest raw data
3. Execute Silver notebook for transformations
4. Run Gold notebook for aggregations
5. Use Databricks SQL for analytics and dashboards

---

## 📌 Project Structure
