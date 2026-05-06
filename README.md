# 🏥 Patient Records Data Engineering Platform (Azure End-to-End ETL Pipeline)

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![ADF](https://img.shields.io/badge/Azure%20Data%20Factory-FF6F00?style=for-the-badge\&logo=azuredatafactory\&logoColor=white)
![ADLS](https://img.shields.io/badge/ADLS%20Gen2-0089D6?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Databricks](https://img.shields.io/badge/Azure%20Databricks-E87722?style=for-the-badge\&logo=databricks\&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-0A6EBD?style=for-the-badge)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)

**Azure Data Engineer Project | ETL Pipeline | Medallion Architecture | Data Lakehouse | Big Data Processing**

---

## 🚀 Project Summary

Designed and implemented a **scalable, Azure Data Engineering pipeline** for processing healthcare patient records using modern cloud data engineering practices.

The solution follows a **Medallion Architecture (Bronze → Silver → Gold)** and demonstrates end-to-end **ETL/ELT pipeline development, data modeling, transformation, and analytics readiness** using Azure ecosystem tools.

This project utilises:

* Azure Data Factory (ADF) for orchestration
* Azure Data Lake Storage Gen2 (ADLS) for scalable storage
* Azure Databricks for distributed processing
* Delta Lake for reliable data engineering
* PySpark for transformation logic
* SQL for analytics-ready modeling

---

## 🎯 Business Objective

To build a **reliable, scalable, and automated data pipeline** that transforms raw patient records into clean, structured, and analytics-ready datasets for healthcare insights and reporting.

---

## 🏗️ Architecture: Medallion Data Lakehouse Design

### 🔹 Bronze Layer (Raw Data Ingestion)

* Ingests raw patient data from Azure Data Factory
* Stores unprocessed data in ADLS Gen2
* Maintains full fidelity of source data

### 🔹 Silver Layer (Cleaned & Standardized Data)

* Data cleansing and transformation using Azure Databricks
* Deduplication using PySpark window functions
* Schema standardization and null handling
* Data quality enforcement

### 🔹 Gold Layer (Business-Ready Data Model)

* Aggregated and curated datasets for analytics
* Implementation of **SCD Type 2 (Slowly Changing Dimensions)**
* MERGE-based incremental data processing
* Optimized for reporting and BI tools

---

## ⚙️ ETL / Data Pipeline Orchestration

* End-to-end orchestration using **Azure Data Factory (ADF)**
* Parameterized pipelines for reusable workflows
* Automated triggers (scheduled + event-based)
* Monitoring, logging, and failure handling enabled
* Integration with Databricks notebooks for transformation execution

---

## 🛠️ Tech Stack

* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2 (ADLS Gen2)
* Azure Databricks
* Delta Lake (ACID Transactions)
* PySpark (Distributed Data Processing)
* SQL (Data Modeling & Analytics)
* Medallion Architecture (Bronze, Silver, Gold)
* ETL / ELT Data Pipeline Design
* Cloud Data Engineering (Azure Ecosystem)

---

## 🔄 Data Engineering Workflow

### 1. Data Ingestion (Bronze Layer)

* Raw patient records ingested from multiple sources
* Stored in ADLS Gen2 without transformation

### 2. Data Transformation (Silver Layer)

* Data cleaning, deduplication, and schema enforcement
* Standardization of patient attributes
* Transformation logic implemented in PySpark (Databricks)

### 3. Data Modeling (Gold Layer)

* Business logic applied for analytics use cases
* Star-schema aligned structured datasets
* SCD Type 2 implementation using Delta Lake MERGE

---

## ⚡ Advanced Features Implemented

* Delta Lake ACID compliance
* Time travel (data versioning)
* Schema enforcement and evolution
* Incremental processing using MERGE INTO
* Window functions for deduplication
* Scalable distributed processing with PySpark

---

## 📊 Data Quality Framework

* Row-level validation checks
* Null handling and missing data treatment
* Duplicate detection and elimination
* Schema consistency validation
* Cross-layer reconciliation (Bronze → Silver → Gold)

---

## 📈 Key Engineering Outcomes

* Fully automated Azure-based ETL pipeline
* Scalable Medallion Architecture implementation
* Production-style data transformation framework
* Analytics-ready Gold layer datasets
* Improved data reliability and governance



