# 🏢 SQL Server Data Warehouse Project


---

## 📌 Project Overview

This project demonstrates how a SQL Server data warehouse is designed and built to **directly support business reporting and decision-making**.

Key objectives of the project include:

* Translating **operational CRM and ERP data** into analytics-ready datasets
* Supporting **business questions, KPIs, and executive reporting**, not just technical transformations
* Implementing a **Medallion Architecture (Bronze → Silver → Gold)** to improve data trust and usability
* Ensuring data is **clean, consistent, and governed** before reaching BI tools
* Designing models that enable **self-service analytics** for analysts and stakeholders
* Reflecting **real-world BI practices** used in healthcare, finance, and enterprise environments

The result is a structured data foundation that allows business users to **trust metrics, identify trends, and make informed decisions**.

---

## 🏗️ Architecture Overview

![Data Warehouse Architecture](docs/data_architecture.png)

This architecture reflects how production BI platforms are designed to:

* Isolate raw source data from reporting logic
* Protect data integrity while allowing transformation flexibility
* Scale as data volume, users, and reporting needs grow

---

## 🔄 Data Flow & Lineage

![Data Flow & Lineage](docs/data_flow.png)

This lineage view demonstrates how data is traceable from **source systems to business metrics**, enabling:

* Confidence in reported KPIs
* Easier root-cause analysis when numbers change
* Transparency for analysts, auditors, and stakeholders

### Data Flow Summary

1. **Source Systems (CRM / ERP)** – Capture customer, sales, and operational activity
2. **Bronze Layer** – Preserves raw data for auditing and reconciliation
3. **Silver Layer** – Cleans, standardizes, and aligns data to business definitions
4. **Gold Layer** – Structures data into a dimensional model optimized for analytics
5. **Consumption Layer** – BI dashboards, KPIs, and ad-hoc analysis

---

## 📂 Repository Structure

```text
sql-server-data-warehouse/
│
├── datasets/               # Source system extracts (as received)
│   ├── source_crm/         # CRM source data
│   └── source_erp/         # ERP source data
│
├── scripts/                # SQL transformation logic
│   ├── bronze/             # Raw ingestion & source-aligned tables
│   ├── silver/             # Cleansed, standardized business data
│   └── gold/               # Analytics-ready dimensional models
│
├── tests/                  # Data quality & validation checks
│   ├── quality_checks_silver/
│   └── quality_checks_gold/
│
├── docs/                   # Business & technical documentation
│   ├── data_architecture.png
│   ├── data_catalogue.md
│   ├── data_flow.png
│   ├── data_integration.png
│   ├── data_model.png
│   └── naming_conventions.md
│
├── LICENSE                 # MIT License
└── README.md               # Project overview & business context
```

---

## 🛠️ Technologies Used

* **Microsoft SQL Server**
* **T-SQL** (CTEs, window functions, stored procedures)
* **Star schema dimensional modeling**
* **Batch ETL design patterns**

---

## 📊 Business Use Cases Enabled

This warehouse is designed to directly support business stakeholders by enabling:

* Executive dashboards with trusted KPIs
* Sales and revenue performance analysis
* Customer and operational trend analysis
* Consistent metrics across Tableau and Power BI
* Self-service analytics without breaking data logic

---

## 🚀 Future Enhancements

* Incremental loading & **SCD Type 2** for historical analysis
* Expanded data quality rules aligned to business KPIs
* Query and model optimization for executive dashboards
* ETL orchestration for production-scale reliability

---

## 👤 About Me

**Denzel Mutogo**
*Tableau Developer | Data Analyst | Business Intelligence*

I specialize in building **business-aligned data models and BI solutions** that bridge the gap between raw data and strategic decision-making. My experience spans **SQL, ETL, Tableau, Power BI, and Excel**, supporting analytics across **healthcare and finance**.


