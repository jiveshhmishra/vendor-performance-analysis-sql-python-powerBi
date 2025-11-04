# 🧾 **Vendor Performance Analysis – Retail Inventory & Sales**

_Transformed raw procurement and sales data into actionable business insights using **SQL**, **Python**, and **Power BI** — enhancing vendor strategy, purchasing decisions, and operational efficiency._

---

## 📘 **Table of Contents**
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Research Questions & Key Findings](#research-questions--key-findings)
- [Dashboard](#dashboard)
- [Final Recommendations](#final-recommendations)
- [Author & Contact](#author--contact)

---

## 🧩 **Overview**

This project evaluates **vendor performance** and **retail inventory dynamics** to uncover data-driven insights for **procurement, pricing, and inventory optimization**.  

A complete **end-to-end data pipeline** was designed using:
- 🧮 **SQL** for ETL and data extraction  
- 🐍 **Python** for analytical modeling and hypothesis testing  
- 📊 **Power BI** for interactive visualization and reporting  

The outcome helps retail managers make informed purchasing decisions, identify cost-saving opportunities, and improve stock efficiency.

---

## 💼 **Business Problem**

Efficient vendor and inventory management is essential for retail profitability.  
This project focuses on addressing the following challenges:

- Identify **underperforming brands** for pricing or promotional adjustments  
- Evaluate **vendor contribution** to overall sales and profits  
- Assess the **impact of bulk purchasing** on cost efficiency  
- Detect **inventory turnover inefficiencies**  
- Statistically **validate profitability differences** among vendors  

---

## 🛠️ **Tools & Technologies**

| Category | Tools Used |
|-----------|-------------|
| **Data Extraction & Transformation** | SQL (CTEs, Joins, Filtering, Aggregation) |
| **Data Analysis & Modeling** | Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy) |
| **Visualization & Reporting** | Power BI (Interactive Dashboards, KPIs, Slicers) |

---

## 🧹 **Data Cleaning & Preparation**

- Removed invalid transactions:
  - Gross Profit ≤ 0  
  - Profit Margin ≤ 0  
  - Sales Quantity = 0  
- Created **vendor-level summary tables** for consistency  
- Handled missing values, outliers, and datatype conversions  
- Merged lookup tables for vendor and product-level enrichment  

---

## 📊 **Exploratory Data Analysis (EDA)**

<details>
<summary>🔍 Click to Expand</summary>

### **Data Quality Observations**
- Negative or zero values in profit-related columns indicated **loss-making or zero-cost sales**
- Unsold inventory highlighted **slow-moving stock**

### **Outlier Detection**
- Extremely high freight costs (up to ₹257K)
- Large purchase and actual price discrepancies detected

### **Correlation Analysis**
| Variables | Correlation | Interpretation |
|------------|--------------|----------------|
| Purchase Price ↔ Profit | Weak | Pricing inefficiency present |
| Purchase Qty ↔ Sales Qty | 0.999 | Strong alignment between procurement and sales |
| Sales Price ↔ Profit Margin | -0.179 | Higher prices slightly reduce margins |
</details>

---

## 🔍 **Research Questions & Key Findings**

| Research Area | Key Finding |
|----------------|-------------|
| **Promotional Opportunities** | 198 brands showed low sales but high margins → ideal for marketing focus |
| **Vendor Dependency** | Top 10 vendors account for **65.69%** of total purchases → over-reliance risk |
| **Bulk Purchasing Impact** | **72% average cost savings** per unit observed in large orders |
| **Inventory Turnover** | **$2.71M worth of unsold inventory** → inefficient rotation |
| **Vendor Profitability** | High Vendors: 31.17% vs. Low Vendors: 41.55% margin difference |
| **Statistical Testing** | Significant difference confirmed → distinct vendor strategies |

---

## 📈 **Dashboard**

An interactive **Power BI dashboard** was built to visualize:

- Vendor performance by sales, profit, and category  
- Brand-wise sales contribution  
- Inventory turnover & unsold stock patterns  
- Bulk purchase cost-benefit analysis  

---

## ✅ **Final Recommendations**

- 🏷️ **Diversify vendor base** to reduce supply dependency risks  
- 📦 **Leverage bulk purchasing** for consistent, high-demand items  
- 💰 **Reprice or promote slow-moving high-margin brands**  
- 🧹 **Strategically clear unsold inventory** via targeted offers  
- 📈 **Enhance negotiation & marketing strategies** using data insights  

---

## 👤 **Author & Contact**

**Jivesh Kumar**  
_Data Analyst | Data-Driven Problem Solver_  

📧 **Email:** [jiveshh.mishra@gmail.com](mailto:jiveshh.mishra@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/jiveshh](https://www.linkedin.com/in/jiveshh/)  

---
# vendor-performance-analysis-sql-python-powerBi
