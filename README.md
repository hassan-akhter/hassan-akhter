<h1 align="center">Hi, I'm Hassan 👋</h1>
<h3 align="center">Data Engineering & Analytics Intern · Warsaw / Berlin · Open to Relocation</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/hassanakhter122/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://hassan-akhter.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=github&logoColor=white" />
  </a>
  <a href="mailto:hassanakhter421@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
</p>

---

MSc Forest Information Technology student (HNEE Germany × SGGW Poland) building end-to-end data pipelines from API ingestion to PostgreSQL schemas to Power BI dashboards.

**9 public projects** across flight operations, e-commerce, job market analytics, geospatial analysis, and statistical testing. Seeking a **Data Engineering or Analytics internship starting July 2026** in Europe or remote.

---

## 🛠 Tech Stack

### Languages & Databases
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

### Libraries & Frameworks
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat)
![Statsmodels](https://img.shields.io/badge/Statsmodels-003B57?style=flat)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)

### Engineering & Tools
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 🚀 Featured Projects

### 🏭 AdventureWorks ETL Pipeline
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/adventureworks-airflow-etl)

End-to-end ETL pipeline loading the AdventureWorks dataset from raw CSV files into a normalised PostgreSQL schema, orchestrated by Apache Airflow in Docker.

- Processed **213K rows across 10 tables** (121K order lines, 31K orders, 20K customers) in a single DAG run
- Built a **custom CSV parser** to handle non-standard `+|` / `&|` delimiters in source files standard parsers cannot read
- Designed **idempotent TRUNCATE + bulk-load** using `psycopg2 execute_values` in FK dependency order — safe to re-trigger daily
- Wrote **10 analytics SQL queries** covering revenue trends, top products, customer lifetime value, and geographic sales distribution

`Python` · `PostgreSQL` · `Apache Airflow` · `Docker` · `psycopg2` · `pandas` · `SQL`

---

### ✈️ Flight Operations Analytics Pipeline
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/flight-operations-data-engineering)

End-to-end ETL pipeline ingesting real-time flight data from the AviationStack API into a multi-layer PostgreSQL architecture, ending in an interactive Power BI dashboard.

- Processed **16,273 flights** across **193 airlines** and **176 airports** in a single pipeline run
- Designed **Bronze → Silver → Gold** medallion architecture with a full star schema (`dim_airline`, `dim_airport`, `dim_time`, `fact_flight`)
- Built **6 reusable KPI SQL views** covering on-time rate, avg delay, cancellations, and busiest routes
- Delivered a **3-page Power BI dashboard** with DAX measures, slicers, and route-level filtering

`Python` · `PostgreSQL` · `SQL` · `Power BI` · `DAX` · `ETL`

---

### 📊 Job Market Analysis Pipeline
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/job_market_analysis_pipeline)

End-to-end ELT pipeline analyzing 25,000+ job postings (2017–2021) across 6 normalized PostgreSQL tables.

- Uncovered **+165.8% market growth** with a **+65.9% COVID spike in 2020** driving digital hiring
- Identified **Cloud · SQL · Python** as top 3 skills, covering 15.5% of all job requirements
- Built **8 analytical charts**, **10 SQL queries**, and **5 reusable views** from scratch

`Python` · `PostgreSQL` · `SQLAlchemy` · `pandas` · `matplotlib` · `seaborn`

---

### 🚕 NYC Taxi Trip Analysis · 7.4M Rows
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/nyc-taxi-trip-analysis)

End-to-end data science project analyzing 7,469,779 NYC yellow taxi trips (January 2019) across data engineering, geospatial analysis, and machine learning.

- Cleaned **198,013 rows** (2.6%) with validated fare ranges, coordinates, and trip durations
- Mapped pickup hotspots across **263 NYC taxi zones** — Manhattan accounts for 90%+ of all trips
- Discovered demand peaks at **8–9 AM and 6–8 PM** weekdays; Fridays and Saturdays busiest overall
- Trained a **Random Forest (100 trees)** to predict tip amounts — MAE ~$1.0–1.5, top feature: `fare_amount`

`Python` · `pandas` · `GeoPandas` · `Scikit-Learn` · `matplotlib` · `seaborn`

---

### 🛒 Brazilian E-Commerce Pipeline · Olist Dataset
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/brazilian-ecommerce-project)

Production-style ETL pipeline on 100,000+ orders across 9 normalized PostgreSQL tables, from raw CSV ingestion to SQL analytics and visualizations.

- Cleaned **1M+ rows** across 9 tables — fixed 23 illogical delivery dates, removed 261,858 duplicate geolocations, validated referential integrity with **zero orphans** across all joins
- Discovered **8× revenue growth** (R$127K → R$1.1M in 12 months) and a **96.9% single-purchase customer rate** signaling a retention problem
- Wrote **16 SQL queries** using window functions, RFM scoring, and RANK() for seller and customer analysis
- Generated **13 charts** covering revenue trends, late delivery by state, payment methods, and geo distribution

`Python` · `PostgreSQL` · `SQLAlchemy` · `pandas` · `matplotlib` · `seaborn`

---

### ☕ Coffee Shop Sales Analysis · 15 Stores · 5 Countries
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/coffee_shop_sales_analysis_2025)

End-to-end sales analytics pipeline for a fictional coffee chain across Poland, UK, Germany, France, and Spain — from PostgreSQL schema design to 14 interactive Plotly charts.

- Designed a **5-table PostgreSQL schema** with indexed foreign keys and 15 analytical SQL queries
- Found **Manchester as the top-revenue store**, **February as the weakest month**, and **Beans as the #1 revenue category** by a significant margin
- Identified **Bronze tier customers drive majority of revenue** by volume — a clear retention and upsell opportunity
- Generated **14 charts** covering daily trends, seasonal demand, loyalty tier performance, and best-selling product per country

`Python` · `PostgreSQL` · `pandas` · `Plotly` · `SQL`

---

### 🧪 A/B Test Analysis · Landing Page Conversion
[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat&logo=github&logoColor=white)](https://github.com/hassan-akhter/ab_testing_analysis)

Statistical evaluation of a 290,000-row experiment to determine whether a new landing page drives higher conversion — with a data-backed recommendation not to launch.

- Cleaned **290,000+ rows** — removed mismatched group assignments and duplicate user records
- Ran a **two-proportion z-test**, 95% CI, and power analysis — p-value of **0.1897** confirms the 0.16% difference is noise, not a real effect
- Confirmed result reliability: **145K users per group** gives ≥0.80 statistical power — the sample size is not the problem
- Delivered a clear **evidence-based no-launch recommendation** — saved the company from shipping a change with no proven benefit

`Python` · `pandas` · `statsmodels` · `SciPy` · `matplotlib`

---

## 📜 Certifications

- **Statistics Foundations Professional Certificate** — Wolfram Research
- **Excel Business Intelligence: Power Pivot, DAX & Data Modeling** — PMI & LinkedIn Learning

---

<p align="center">
  <i>Building clean, reproducible data pipelines — one project at a time.</i>
</p>
