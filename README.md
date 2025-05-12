# 📊 COVID-19 Exploratory Data Analysis (EDA)

This project explores global COVID-19 data to uncover key trends, correlations, and regional patterns. Using Python and Power BI, we performed a full data cleaning pipeline and created impactful visualizations that show the progression and disparities of the pandemic.

---

## 🌍 Overview

The analysis focuses on:
- Total confirmed cases, deaths, and recoveries
- Weekly case growth and regional disparities
- Correlation between infection, recovery, and mortality rates
- Healthcare response insights across WHO regions

---

## 🧼 Data Cleaning Steps

- Standardized column names (snake_case)
- Fixed inconsistencies (e.g., “USA” vs “United States”)
- Removed duplicate and null entries
- Converted numeric fields to appropriate types
- Verified calculated metrics like:
  - `weekly_percentage_increase`
  - `deaths_100_cases`
  - `recovered_100_cases`

---

## 📈 Key Findings

- Strong correlation between confirmed cases and deaths
- Lower recovery-to-death ratios in some under-resourced regions
- Emerging hotspots identified through weekly trends
- Large variance in case distribution, especially between continents

---

## 📊 Power BI Dashboard

Features:
- ✅ KPIs for confirmed, recovered, deaths, and active cases
- 🗺️ Map: Cases by country
- 📊 Bar charts: Country-wise comparison of new cases/deaths
- 📈 Line charts: Weekly change per WHO region
- 🎯 Gauge: Recovery rate vs. target
- 🎚️ Slicers: Filter by WHO region or country

> 📁 Dashboard file located in `dashboard/` folder

---

## 💻 Technologies Used

- Python (Pandas, Seaborn, Matplotlib)
- Power BI (DAX, slicers, KPI cards)
- Jupyter Notebook

---

## 📂 Project Structure
COVID19_EDA_Project/
├── data/ # Cleaned dataset
├── notebooks/ # Python notebooks for EDA
├── dashboard/ # Power BI dashboard files
├── README.md # This file


