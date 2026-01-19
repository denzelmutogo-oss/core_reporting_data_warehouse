# 🏢 SQL Server Data Warehouse Project

---

## 📌 Project Overview
This project is a **hands-on SQL Server data warehouse build** designed to reflect real-world **Business Intelligence and analytics environments**. It demonstrates how raw operational data flows through a structured pipeline and becomes **clean, trusted, analytics-ready data**.

Data from **CRM and ERP systems** is processed using a **Medallion(Bronze → Silver → Gold)** architecture and modeled into business-friendly datasets that can be easily consumed by BI tools, analysts, and stakeholders.

The focus is on **data quality, clarity, and usability**, not just writing SQL.

---

## 🏗️ Architecture Overview

![Data Warehouse Architecture](docs/data_architecture.png)

The diagram above shows the end-to-end architecture, illustrating how data moves from source systems through the Bronze, Silver, and Gold layers before reaching reporting and analytics.

This layered approach ensures **scalability, traceability, and maintainability**.

---

## 🔄 Data Flow & Lineage
![Data Flow & Lineage](docs/data_flow.png)

This diagram highlights table-level lineage across layers and shows how CRM and ERP data is transformed into analytical models.

**Data Flow Summary:**
1. Source Systems (CRM / ERP)  
2. Bronze – Raw ingestion  
3. Silver – Cleansed & standardized  
4. Gold – Dimensional model  
5. Consumption – BI dashboards & analytics  

---

## 🛠️ Technologies Used
- Microsoft SQL Server  
- T-SQL (CTEs, window functions, stored procedures)  
- Star schema dimensional modeling  
- Batch ETL patterns  

---

## 📊 Use Cases
- BI & dashboarding (Tableau, Power BI)  
- Ad-hoc analytical queries  
- KPI and performance reporting  
- Data validation and exploration  

---

## 🎯 Key Skills Demonstrated
- SQL-based ETL development  
- Data warehousing & dimensional modeling  
- Data cleansing and standardization  
- BI-ready data design  
- Analytics and reporting enablement  

---

## 🚀 Future Enhancements
- Incremental loading & SCD Type 2  
- Expanded data quality checks  
- Performance optimization  
- ETL orchestration  

---

## 👤 About Me

**Denzel Mutogo**  
*Tableau Developer | Data Analyst | Business Intelligence*

I focus on building **analytics-ready data models and BI solutions** that turn complex data into clear, actionable insights. My work spans **Excel, SQL, ETL, Tableau, and Power BI**, with experience supporting analytics in **healthcare and finance**.

This project reflects how I approach BI work: structured pipelines, strong data quality, and models designed specifically for reporting and analysis.

---

