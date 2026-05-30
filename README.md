<h1 align="center">Hi, I'm Hassan 👋</h1>
<h3 align="center">Data Engineering Intern & Analytics Developer · Berlin, Germany</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/hassanakhter122/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/hassan-akhter"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" /></a>
</p>

I build end-to-end data systems from ETL pipelines to analytical dashboards.

My work spans real projects in flight operations, e-commerce analytics, job market data, and predictive modeling.

**My toolkit:** Python · SQL · PostgreSQL · Airflow · Docker · dbt · Snowflake · Power BI

Master's student in Forest IT (Germany & Poland) with a focus on reproducible, well-documented data infrastructure. Seeking my first professional data internship to apply these skills at scale.

**Explore my portfolio projects** below each demonstrates a different aspect of the data pipeline.


## 🛠 Technical Skills

### **Languages & Databases**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

### **Libraries & Frameworks**
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat)
![Statsmodels](https://img.shields.io/badge/Statsmodels-003B57?style=flat)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

### **Data Engineering & Workflow**
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

### **Domains**
E‑commerce · Geospatial · Job Market Analytics · Environmental Data · Flight Operations

### **Core Competencies**
ETL/ELT pipelines · Data modeling (Star Schema) · API ingestion · Data validation · Dashboarding · Statistical analysis · Machine learning workflows


## 🚀 Featured Projects

### ✈️ Flight Operations Analytics: End‑to‑End Data Pipeline
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/flight-operations-data-engineering)

End-to-end ETL pipeline ingesting real-time flight data from the AviationStack API into a multi-layer PostgreSQL architecture, ending in an interactive Power BI dashboard.

- Processed **16,273 flights** across **193 airlines** and **176 airports** in a single pipeline run
- Designed **Bronze → Silver → Gold** medallion architecture with a full star schema
  (`dim_airline`, `dim_airport`, `dim_time`, `fact_flight`)
- Built **6 reusable KPI SQL views** covering on-time rate, avg delay, cancellations, and busiest routes
- Delivered a **3-page Power BI dashboard** with DAX measures, slicers, and route-level filtering

`Python` · `PostgreSQL` · `SQL` · `Power BI` · `DAX` · `ETL`

### 🗽 NYC Taxi Trip Analysis: ML + Geospatial
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/nyc-taxi-trip-analysis)

End-to-end data science project analyzing 7,469,779 NYC yellow taxi trips (January 2019) across data engineering, geospatial analysis, and machine learning.

- Cleaned **198,013 rows** (2.6%) with validated fare ranges, coordinates, and trip durations
- Mapped pickup hotspots across **263 NYC taxi zones** — Manhattan accounts for 90%+ of all trips
- Discovered demand peaks at **8–9 AM and 6–8 PM** weekdays; Fridays and Saturdays busiest overall
- Trained a **Random Forest (100 trees)** to predict tip amounts — MAE ~$1.0–1.5, top feature: `fare_amount`

`Python` · `pandas` · `GeoPandas` · `Scikit-Learn` · `matplotlib`

### 🛒 Brazilian E-Commerce: Data Engineering (Olist Dataset)
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/brazilian-ecommerce-project)

Production-style ETL pipeline on 100,000+ orders across 9 normalized PostgreSQL tables, from raw CSV ingestion to SQL analytics and visualizations.

- Cleaned **1M+ rows** across 9 tables — fixed 23 illogical delivery dates, removed 261,858 duplicate geolocations, validated referential integrity with **zero orphans** across all joins
- Discovered **8× revenue growth** (R$127K → R$1.1M in 12 months) and a **96.9% single-purchase customer rate** signaling a retention problem
- Wrote **16 SQL queries** using window functions, RFM scoring, and RANK() for seller/customer analysis
- Generated **13 charts** covering revenue trends, late delivery by state, payment methods, and geo distribution

`Python` · `PostgreSQL` · `SQLAlchemy` · `pandas` · `matplotlib` · `seaborn`

### ☕ Coffee Shop Sales Analysis: Multi-Country
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/coffee_shop_sales_analysis_2025)

End-to-end sales analytics pipeline for a fictional coffee chain across Poland, UK, Germany, France, and Spain — from PostgreSQL schema design to 14 interactive Plotly charts.

- Designed a **5-table PostgreSQL schema** with indexed foreign keys and optimized queries across 15 SQL analytical queries
- Found **Manchester as the top-revenue store**, **February as the weakest month** chain-wide, and **Beans as the #1 revenue category** by a significant margin
- Identified **Bronze tier customers drive majority of revenue** by volume despite lower individual spend — a clear retention and upsell opportunity
- Generated **14 charts** covering daily trends, seasonal demand (Pumpkin Spice Latte), loyalty tier performance, and best-selling product per country

`Python` · `PostgreSQL` · `pandas` · `Plotly` · `SQL`


### 🧪 A/B Test Analysis: Landing Page Conversion
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/ab_testing_analysis)

Statistical evaluation of a **290K-row** experiment using Python + Statsmodels.

- Ran two-proportion z-test, confidence intervals, and power analysis
- Found no statistically significant lift (p = 0.1897) — evidence-based no-go recommendation
- `Python` · `Statsmodels` · `SciPy`


### 📊 Job Market Analysis
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/job_market_analysis_pipeline)

End-to-end ELT pipeline analyzing 25,000+ job postings (2017–2021) across 6 normalized PostgreSQL tables.

- Uncovered **+165.8% market growth** with a **+65.9% COVID spike in 2020** driving digital hiring
- Identified **Cloud · SQL · Python** as top 3 skills, covering 15.5% of all job requirements
- Built 8 analytical charts, 10 SQL queries, and 5 reusable views from scratch

`Python` · `PostgreSQL` · `SQLAlchemy` · `pandas` · `matplotlib` · `seaborn`

### 🌳 Tree Stem Volume Modeling: Scientific ML
[![Repo](https://img.shields.io/badge/View%20Project-000?style=for-the-badge&logo=github)](https://github.com/hassan-akhter/tree_volume_analysis)

Species-specific allometric modeling across **312 trees, 8 species** (Haselburg Marteloscope).

- Implemented Zianis et al. (2005) equations in Python
- Achieved **R² = 0.9317** and **MAE = 0.1659 m³**
- Generated diagnostic plots and validated predictions
- `Python` · `Pandas` · `Matplotlib`


## 📜 Certifications

- **Statistics Foundations Professional Certificate** — Wolfram Research
- **Statistics Foundations 4: Advanced Topics** — LinkedIn Learning
- **Excel Business Intelligence: Power Pivot, DAX, Data Modeling Certificate** — Project Management Institute (PMI) & LinkedIn Learning
- **Excel Data Analysis** — LinkedIn Learning
- **Excel Statistics Essential Training 2** — LinkedIn Learning

## 🔭 Currently Working On
- Building production-style data engineering projects (APIs → ETL → SQL → BI)
- Expanding skills in orchestration and containerization (Airflow, Docker)
- Learning cloud data tools (BigQuery, dbt, Azure Data Studio)
- Developing real-time and batch pipelines for analytics use cases
- Open to Data Analyst / Data Engineer / Data Scientist internships

<p align="center">
  <i>"Turning raw data into clean, meaningful insights."</i>
</p>
