# 🏠 BC Housing Market Analytics Dashboard

**Power BI · SQL · DAX · Power Query · Data Modeling · Business Intelligence**

An end-to-end Business Intelligence project analyzing **30+ years of British Columbia housing market data** to uncover trends in housing supply, affordability, regional development, and market conditions.

The project transforms complex historical housing data into interactive Power BI dashboards, executive KPIs, and actionable insights designed to support evidence-based planning and decision-making.

> **Data Note:** The original dataset is not included in this repository due to data-sharing and licensing considerations. This repository focuses on the analytical workflow, dashboard development, methodology, and business insights.

---

## 📊 Dashboard Overview

<p align="center">
  <img src="./images/dashboard-overview.png" alt="BC Housing Market Analytics Power BI Dashboard Overview" width="100%">
</p>

<p align="center">
  <b>Executive Summary · Cluster Analysis · Trend Analysis</b>
</p>

---

## 📖 Project Overview

British Columbia's housing market has experienced substantial changes over the past three decades as population growth, housing demand, regional development, and affordability pressures have reshaped market conditions.

This project analyzes historical housing activity from **1990–2024**, together with current regional market conditions, through three interconnected Power BI dashboards.

The analysis focuses on three core areas:

* **Executive Performance** — How has BC's housing market evolved over time?
* **Regional Distribution** — Where is housing development concentrated, and how do regional markets differ?
* **Market Trends** — How are housing supply, prices, affordability, and vacancy conditions changing?

---

## 🎯 Business Questions

The analysis was designed to answer practical housing-market questions:

* Has new housing supply kept pace with population growth?
* How have housing prices and affordability changed over time?
* Which housing types contribute the most to new construction?
* Which regions account for the largest share of housing development?
* How do urban and rural housing markets differ?
* How have housing starts changed year over year?
* Is recent construction activity above or below the longer-term market trend?
* How do housing starts relate to changes in vacancy conditions?

---

## 🛠 Analytics Workflow

### 1️⃣ Data Exploration & Validation

* Explored historical British Columbia housing datasets.
* Assessed data structure, completeness, and analytical suitability.
* Identified business questions, dimensions, and required KPIs.

### 2️⃣ Data Preparation & ETL

Used **Power Query** to prepare the analytical dataset through:

* Data cleaning and validation
* Data type standardization
* Filtering and restructuring
* Merge and Append operations
* Grouping and aggregation
* Calculated columns
* Transformation of raw data into analysis-ready tables

### 3️⃣ Data Modeling

* Designed a dimensional analytical model.
* Established relationships between fact and dimension tables.
* Applied Star Schema principles where appropriate.
* Optimized relationships and filter behavior for interactive reporting.

### 4️⃣ DAX & KPI Development

Developed analytical measures across four major areas:

**Housing Supply & Composition**

* Total Housing Starts
* Condo Starts
* Homeowner Starts
* Rental Starts
* Housing Type Share (%)
* Condo-to-Rental Ratio

**Affordability & Market Conditions**

* Average Housing Price
* Average Vacancy Rate
* Rent-to-Income Ratio
* Price-to-Income Ratio
* Average Price per Housing Start

**Time Intelligence**

* Previous-Year Housing Starts
* Housing Starts YoY Change (%)
* Previous-Year Vacancy Rate
* Vacancy Rate YoY Change (%)
* Three-Year Rolling Average

**Regional Analysis**

* Regional Housing Starts
* Urban vs. Rural Housing Share
* Dynamic Year and Region Measures
* Filter-responsive KPIs
* Benchmark and reference measures

### 5️⃣ Dashboard Development

Designed three interactive Power BI dashboards:

* **Executive Summary** — province-wide KPIs, historical performance, affordability, and current regional activity
* **Cluster Analysis** — regional housing supply, pricing, development mix, and urban/rural distribution
* **Trend Analysis** — year-over-year performance, rolling trends, housing prices, supply composition, and vacancy conditions

### 6️⃣ Business Insight Generation

Translated dashboard results into business findings and planning implications rather than treating visualization as the final analytical output.

---

## ⚙️ Technology Stack

| Category              | Technologies                                               |
| --------------------- | ---------------------------------------------------------- |
| Business Intelligence | Power BI                                                   |
| Data Querying         | SQL                                                        |
| ETL & Transformation  | Power Query                                                |
| Data Modeling         | Star Schema, Relationship Modeling                         |
| Analytics             | DAX, KPI Development, Time Intelligence                    |
| Visualization         | Interactive Dashboards, Executive Reporting                |
| Analysis              | Trend Analysis, Regional Comparison, Business Storytelling |

---

# 📊 Dashboard Details

## 1️⃣ Executive Summary

<p align="center">
  <img src="./images/executive-summary.png" alt="BC Housing Market Executive Summary Dashboard" width="100%">
</p>

Provides an executive-level view of historical housing performance, affordability, housing composition, and current regional construction activity across British Columbia.

### Key Questions

* How has BC's housing supply evolved since 1990?
* Has construction kept pace with population growth?
* How have affordability and vacancy conditions changed?
* Which housing types dominate new construction?
* Which regions currently contribute the most housing supply?

---

## 2️⃣ Cluster Analysis

<p align="center">
  <img src="./images/cluster-analysis.png" alt="BC Housing Market Cluster Analysis Dashboard" width="100%">
</p>

Compares housing supply, pricing, rental conditions, housing mix, and development concentration across British Columbia's regional markets.

### Key Questions

* Where is new housing construction concentrated?
* How does housing composition differ across regions?
* Which markets experience the highest prices?
* How different are urban and rural development patterns?

---

## 3️⃣ Trend Analysis

<p align="center">
  <img src="./images/trend-analysis.png" alt="BC Housing Market Trend Analysis Dashboard" width="100%">
</p>

Examines recent housing-market dynamics through year-over-year performance, rolling averages, housing prices, supply composition, and vacancy trends.

### Key Questions

* Is housing construction increasing or slowing?
* Is current supply above or below the recent market trend?
* How are prices changing across housing types?
* How is the housing mix evolving?
* Do changes in construction correspond with changes in vacancy rates?

---

# 💡 Key Business Insights

### 🏗️ 1. Housing supply expanded substantially, but affordability remains under pressure

More than **1.05 million housing units** were started between 1990 and 2024. Despite this substantial expansion in supply, the **Price-to-Income Ratio reached 6.75**, indicating continued affordability pressure.

### 🏢 2. Condominiums dominate new housing construction

Approximately **520K condominium units** were started during the analysis period, compared with approximately **345K homeowner units** and **181K rental units**.

Condominiums therefore represent nearly half of total housing starts and have been the primary contributor to new housing supply.

### 🏙️ 3. Housing development is heavily concentrated in urban markets

Approximately **91% of housing starts** occur in urban regions.

Vancouver represents the largest concentration of new construction activity, while Victoria and Kelowna form a second tier of regional development.

### 📍 4. Housing conditions vary significantly by region

Major urban centres generally combine higher construction activity with higher housing and rental prices, while many smaller communities experience substantially lower levels of new development.

This suggests that province-wide averages alone may hide important regional housing pressures.

### 📈 5. Recent construction remains relatively strong despite annual fluctuations

Between 2016 and 2024, housing starts generally followed an upward trajectory.

Although construction declined in 2024 compared with the previous year, activity remained relatively high when evaluated against the **three-year rolling average** and recent historical performance.

### 🏘️ 6. More construction does not immediately translate into higher vacancy

Vacancy rates fluctuate independently of short-term changes in housing starts.

This suggests that housing availability is also influenced by factors such as population growth, migration, housing demand, and the time required for newly started projects to reach completion.

---

## 🎯 Business Takeaway

The analysis suggests that **increasing housing supply alone may not be sufficient to address British Columbia's housing challenges**.

Effective housing planning requires evaluating supply alongside:

* Affordability
* Population growth
* Regional demand
* Housing-type composition
* Rental-market conditions
* Vacancy rates

A balanced strategy should continue supporting construction in high-demand urban markets while also encouraging appropriate housing development in emerging regional centres.

---

## 🏆 Skills Demonstrated

`Power BI` · `SQL` · `DAX` · `Power Query` · `ETL` · `Data Modeling` · `Star Schema` · `KPI Development` · `Time Intelligence` · `Dashboard Design` · `Business Intelligence` · `Data Visualization` · `Business Analysis` · `Data Storytelling`

---

## 📬 Contact

Interested in discussing this project or data analytics opportunities?

* **LinkedIn:** https://www.linkedin.com/in/m-bahari
* **Email:** [mism.bahari@gmail.com](mailto:mism.bahari@gmail.com)
