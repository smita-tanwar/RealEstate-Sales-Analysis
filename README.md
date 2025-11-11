


# 🏡 Real Estate Sales Analysis Dashboard

### Power BI + Google BigQuery + SQL

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![BigQuery](https://img.shields.io/badge/Database-Google%20BigQuery-blue?style=for-the-badge&logo=googlecloud)
![SQL](https://img.shields.io/badge/Language-SQL-lightgrey?style=for-the-badge&logo=sqlite)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📘 Project Overview

This Power BI project analyzes **real estate sales performance** by integrating **Google BigQuery**, **SQL**, and **Power BI**.  
It demonstrates end-to-end data analytics — from **data extraction and transformation** to **visual reporting** and **publishing dashboards**.

The goal is to uncover insights into **sales growth**, **regional trends**, **pricing behavior**, and **key factors influencing real estate sales**.

---

## ⚙️ Tools & Technologies Used

| Tool                        | Purpose                                        |
| --------------------------- | ---------------------------------------------- |
| 🧠 **Google BigQuery**      | Cloud data storage & SQL processing            |
| 🧩 **SQL**                  | Data transformation & aggregation              |
| 🧹 **Power Query Editor**   | Data cleaning & shaping                        |
| 📊 **Power BI Desktop**     | Dashboard creation & visualization             |
| 🧮 **DAX Functions**        | Custom metrics (YOY growth, MedianX, TOTALYTD) |
| 🖥️ **Microsoft SQL Server** | Local testing & connection setup               |

---

## 🧭 Project Workflow

1. **Loading Data into Google BigQuery**

   - Uploaded and connected raw sales data.
   - Created a link to Power BI for live data access.

2. **Using SQL for Data Understanding & Transformation**

   - Cleaned missing values and standardized column formats.
   - Aggregated and filtered data for key measures.

3. **Power Query Editor for Cleaning**

   - Handled nulls, corrected data types, and created new columns.

4. **DAX for Analytical Measures**

   - `CALCULATE`, `YEAR`, `IF`, `BLANK` → YOY Sales Growth
   - `MEDIANX` → Median Sales Price by Region
   - `DISTINCTCOUNT`, `ALLEXCEPT` → Units Sold & Regional Analysis
   - `DATESINPERIOD`, `TOTALYTD` → Rolling 12-month & YTD trends

5. **Dashboard Design**

   - **Sales Performance Page:** KPIs, donut charts, YOY trends
   - **Regional Analysis Page:** Median price change by region
   - **House Type Analysis:** Offer vs purchase comparison, key influencers

6. **Publishing Reports**
   - Published dashboards to **Power BI Service** and shared in workspace.

---

## 📈 Key Insights

✅ Identified **Year-over-Year Sales Growth** trends  
✅ Visualized **median price variations by region**  
✅ Compared **average offer vs purchase price**  
✅ Highlighted **key influencers** impacting property sales

---

## 📦 Files Included

| File                              | Description                     |
| --------------------------------- | ------------------------------- |
| `Real_Estate_Sales_Analysis.pbix` | Power BI Dashboard              |
| `SQL_Scripts.sql`                 | BigQuery transformation queries |
| `Dataset.csv` / `Dataset.xlsx`    | Source data (if public)         |
| `README.md`                       | Project documentation           |

---

## 🚀 How to Use

1. **Clone** this repository
   ```bash
   git clone https://github.com/smita Tanwar/RealEstate-Sales-Analysis.git
   ```

