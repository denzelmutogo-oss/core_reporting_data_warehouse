# SQL Server Data Warehouse Project


---
## 📌 Project Overview

This project is a **hands-on SQL Server data warehouse build** designed to mirror how data is handled in real production environments. Rather than focusing only on queries or isolated transformations, the project demonstrates how raw operational data moves through a structured pipeline and becomes **trusted, analytics-ready data**.

The warehouse integrates data from **CRM and ERP systems**, applies progressive refinement using a **Bronze → Silver → Gold** architecture, and delivers a dimensional model that can be consumed confidently by BI tools, analysts, and stakeholders.

The emphasis throughout the project is on **clarity, data quality, and business usability**, not just technical correctness.

---
## 🏗️ Architecture Overview

![Data Warehouse Architecture](docs/data_architecture.png)

The diagram above illustrates the full end-to-end architecture, showing how data flows from source systems through the Bronze, Silver, and Gold layers before being consumed by analytics and reporting tools.

---

## 🔄 Data Flow & Lineage

![Data Flow & Lineage](docs/data_flow.png)

The diagram above provides a detailed view of table-level lineage across layers, highlighting how CRM and ERP datasets are transformed and integrated into dimensional models.

1. **Source Systems (CRM / ERP)**
2. **Bronze Layer** – Raw ingestion (no transformations)
3. **Silver Layer** – Cleansed and standardized datasets
4. **Gold Layer** – Dimensional model (facts & dimensions)
5. **Consumption** – BI dashboards, ad-hoc SQL, analytics

The layered approach ensures **clear data lineage, auditability, and maintainability**.



## 🛠️ Technologies Used

* Microsoft SQL Server
* T-SQL (CTEs, window functions, stored procedures)
* Star schema dimensional modeling
* Batch ETL patterns

---

## 📊 Use Cases

* BI & Reporting (Power BI, Tableau)
* Ad-hoc analytical queries
* KPI and metric reporting
* Data exploration and validation

---

## 🎯 Key Skills Demonstrated

* Data warehouse design & modeling
* Medallion architecture implementation
* ETL development using SQL Server
* Data cleansing and standardization
* Dimensional modeling (facts & dimensions)
* Business-ready analytics design

---

## 🚀 Future Enhancements

* Incremental loading strategies
* Slowly Changing Dimensions (SCD Type 2)
* Data quality checks & error logging
* Performance optimization (indexes, partitioning)
* Orchestration using SQL Agent / Azure Data Factory

---

## 📎 Repository Structure




---

## 🧠 Summary

This project demonstrates more than just SQL proficiency — it shows how to think about data as a product. From preserving raw inputs to delivering clean, business-friendly models, the warehouse reflects real-world patterns used in enterprise analytics teams.

It highlights an understanding of:

* End-to-end data flow and lineage
* Data quality and standardization
* Dimensional modeling for analytics
* Designing systems that are easy to maintain and scale

Overall, this project represents a practical, production-oriented approach to building a SQL Server data warehouse.

