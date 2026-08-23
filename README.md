# Customer Behavior Analysis

**Data Analytics Pipeline: From Raw Data to Executive Insights**

An end-to-end data analytics project that transforms raw transactional data into strategic business recommendations using Python, MySQL, and Power BI.

---

## 📋 Overview

This project demonstrates a complete data analytics lifecycle — from programmatic data cleaning through relational querying to executive-level reporting. The goal: ingest messy retail transaction data, surface actionable trends, and deliver insights in a format ready for stakeholders.

## 📊 Dataset

| | |
|---|---|
| **Source** | Customer Shopping Behaviour Analysis dataset |
| **Size** | 3,901 rows × 18 columns |
| **Description** | Transactional and demographic records used to track key business performance indicators (KPIs) |

## 🛠️ Tools Used

| Stage | Tools |
|---|---|
| Data Processing & EDA | Python (Pandas, NumPy, Seaborn) |
| Database Management | MySQL |
| Data Visualization | Power BI |
| Reporting / Presentation | Gamma AI |

## 🔄 Project Workflow

**1. Python — Ingestion & EDA**
- Profiled the raw dataset to identify missing values, duplicates, and structural anomalies
- Cleaned and validated the data
- Exported a verified `.csv` file for database loading

**2. MySQL — Relational Querying**
- Designed a database schema with an optimized primary key
- Migrated the cleaned data from Python into MySQL tables
- Wrote advanced SQL queries (CTEs, window functions) to extract deeper business trends

**3. Power BI — Interactive Dashboarding**
- Built a data model connected to the MySQL backend
- Developed custom DAX measures for dynamic, real-time KPI tracking
- Designed an interactive dashboard for business stakeholders

**4. Reporting & Presentation**
- Documented methodology and findings in a formal report
- Generated a stakeholder-ready slide deck using Gamma AI

## 📉 Dashboard Preview

*(Add 2–3 screenshots of your Power BI dashboard here — this is the single highest-impact addition you can make. Recruiters and reviewers scan visuals before they read text.)*

```
![Dashboard Overview](images/dashboard_overview.png)
![Sales Trends](images/sales_trends.png)
```

**Key metrics tracked:** Total Revenue, Profit Margins, Customer Retention Rate, Month-over-Month Growth
**Core visuals:** Interactive maps, trend lines, dynamic performance slicers

## 🏆 Key Results & Insights

- **Trend identified:** A 15% dip in Q3 sales, traced back to supply chain delays
- **Top drivers:** 20% of high-value customers generated 80% of total revenue
- **Recommendation:** Optimize inventory levels 30 days ahead of peak seasons to reduce stockout risk

## ▶️ How to Reproduce

1. Clone this repository
2. Open `customer_behaviour Python file.ipynb` and run all cells to clean the raw data and export the processed `.csv`
3. Load the cleaned `.csv` into MySQL, then run `customer_behaviour sql file.sql` to build the schema and generate trend queries
4. Open `customer_behaviour powerbi file.pbix` in Power BI Desktop and refresh the data connection to load the dashboard

### Requirements
```
pandas
numpy
seaborn
matplotlib
mysql-connector-python
```

## 📁 Repository Structure

├── [customer_behaviour Python file.ipynb](https://github.com/priyankamanik35-lgtm/Customer_Behavior_Analysis-/blob/main/customer_behaviour%20Python%20file.ipynb)   # Data cleaning & EDA

├── [customer_behaviour sql file.sql](https://github.com/priyankamanik35-lgtm/Customer_Behavior_Analysis-/blob/main/customer_behaviour%20sql%20file.sql)        # Schema + analytical queries

├── [customer_behaviour powerbi file.pbix](https://github.com/priyankamanik35-lgtm/Customer_Behavior_Analysis-/blob/main/customer_behaviour%20powerbi%20file.pbix)   # Interactive dashboard

└── README.md

