# 📘 Data Dictionary  
**Electric Vehicle Adoption Analysis (Power BI)**

This document describes the key datasets, fields, and metrics used in the Electric Vehicle Adoption Analysis dashboard.  
The purpose of this data dictionary is to provide **clarity, transparency, and interpretability** for all visuals and insights presented in the report.

---

## 📊 Dataset Overview

The analysis is based on publicly available electric vehicle population and adoption datasets.  
Data has been aggregated and transformed using **Power Query** to support time-based, regional, and category-level analysis.

> ⚠️ Raw datasets are not included in this repository due to size considerations.  
> This document explains how the data is structured and interpreted within the dashboard.

---

## 🗂️ Core Fields Description

### 🔹 Time Dimension

| Column Name | Description |
|------------|-------------|
| Year | Calendar year of observation |
| Date | Reference date used for time-based analysis (year-level aggregation) |

---

### 🔹 Geographic Dimension

| Column Name | Description |
|------------|-------------|
| Country | Country name |
| State / Region | State, province, or regional classification |
| City | City or local administrative area (if applicable) |

---

### 🔹 Vehicle Information

| Column Name | Description |
|------------|-------------|
| Vehicle_Type | Type of electric vehicle (BEV, PHEV, etc.) |
| Make | Manufacturer or brand name |
| Model | Vehicle model name |
| Model_Year | Manufacturing year of the vehicle |

---

### 🔹 Adoption & Population Metrics

| Column Name | Description |
|------------|-------------|
| EV_Count | Number of registered electric vehicles |
| Total_Vehicles | Total number of registered vehicles |
| EV_Adoption_Rate | Percentage share of electric vehicles |
| Growth_Rate | Year-over-year growth in EV adoption |

---

### 🔹 Infrastructure & Policy (If Applicable)

| Column Name | Description |
|------------|-------------|
| Charging_Stations | Number of public charging points |
| Policy_Type | EV-related policy category |
| Incentive_Available | Indicates availability of incentives or subsidies |

---

## 📈 Calculated Measures (DAX)

The following metrics are calculated within Power BI using DAX:

| Measure Name | Description |
|-------------|-------------|
| Total EVs | Total electric vehicles across selected filters |
| EV Adoption % | EV share relative to total vehicles |
| YoY Growth % | Year-over-year adoption growth |
| Regional Share | Contribution of a region to total EV adoption |

---

## 🔄 Data Transformation Notes

- Data cleaning and transformation were performed using **Power Query**
- Missing values were handled during preprocessing
- Aggregations were applied at yearly and regional levels
- Column names were standardized for consistency across visuals

---

## ⚠️ Data Usage Notes

- The dataset is used **for analytical and educational purposes only**
- Results are dependent on data availability and reporting practices
- Visual insights should be interpreted in context, not as forecasts

---

## 📌 Purpose of This Data Dictionary

This document ensures:
- Transparency in data usage  
- Clear interpretation of metrics  
- Reproducibility of analysis  
- Better understanding for reviewers and collaborators  

---

**Author:** Tabassum Unnisa  
**Project:** Electric Vehicle Adoption Analysis (Power BI)


