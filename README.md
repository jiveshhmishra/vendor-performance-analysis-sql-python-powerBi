# 🧾 Vendor Performance Analysis – Retail Inventory & Sales

_Transformed raw procurement data into actionable insights using **SQL**, **Python**, and **Power BI**, enhancing vendor strategy, cost efficiency, and retail performance._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#Dashboard">Dashboard</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>


---
<h2><a class="anchor" id="overview"></a>🧠 Overview</h2>

This project evaluates **vendor performance** and **retail inventory dynamics** to generate strategic insights for procurement, pricing, and stock optimization.  
A complete end-to-end data pipeline was developed using:
- **SQL** for ETL and data structuring  
- **Python** for analytical modeling and hypothesis testing  
- **Power BI** for interactive visualization and decision dashboards  

---
<h2><a class="anchor" id="business-problem"></a>💼 Business Problem</h2>

Effective inventory and vendor management are critical to profitability in retail operations.  
This project aims to:

- Identify underperforming brands needing pricing or promotional adjustments  
- Determine vendor contributions to overall sales and profit  
- Analyze cost–benefit of bulk purchasing  
- Detect inventory turnover inefficiencies  
- Statistically validate differences in vendor profitability  

---
<h2><a class="anchor" id="tools--technologies"></a>🧰 Tools & Technologies</h2>

- **SQL:** Common Table Expressions (CTEs), Joins, Filtering, Aggregations  
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy (for hypothesis testing)  
- **Power BI:** Interactive dashboards and performance KPIs  

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>🧹 Data Cleaning & Preparation</h2>

Performed rigorous preprocessing steps to ensure data quality:

- Removed invalid transactions with  
  - Gross Profit ≤ 0  
  - Profit Margin ≤ 0  
  - Sales Quantity = 0  
- Created summary tables with vendor-level metrics  
- Converted data types, handled outliers, and merged lookup tables for enriched analysis  

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>📊 Exploratory Data Analysis (EDA)</h2>

**Negative or Zero Values Detected:**  
- Gross Profit: Min = -52,002.78 (loss-making sales)  
- Profit Margin: Min = -∞ (sales at or below cost)  
- Unsold Inventory: Highlighting slow-moving stock  

**Outliers Identified:**  
- High Freight Costs (up to 257K)  
- Large purchase and sales price variations  

**Correlation Analysis:**  
- Weak: Purchase Price ↔ Profit  
- Strong: Purchase Qty ↔ Sales Qty (0.999)  
- Negative: Profit Margin ↔ Sales Price (-0.179)  

---
<h2><a class="anchor" id="research-questions--key-findings"></a>🔍 Research Questions & Key Findings</h2>

1. **Brands for Promotions:** 198 brands show low sales but high profit margins  
2. **Top Vendors:** Top 10 vendors contribute 65.69% of total purchases → over-reliance risk  
3. **Bulk Purchasing Impact:** 72% average cost savings per unit in large orders  
4. **Inventory Turnover:** $2.71M worth of unsold inventory identified  
5. **Vendor Profitability:**
   - High Vendors: Mean Margin = 31.17%  
   - Low Vendors: Mean Margin = 41.55%  
6. **Hypothesis Testing:** Statistically significant difference in vendor margins — confirming distinct pricing and cost strategies  

---
<h2><a class="anchor" id="Dashboard"></a>📈 Dashboard</h2>

An interactive *Power BI dashboard* was built to visualize:
- Vendor performance by sales, profit, and category  
- Brand-wise sales contribution  
- Inventory turnover & unsold stock patterns  
- Bulk purchase cost-benefit analysis


---
<h2><a class="anchor" id="final-recommendations"></a>📈 Final Recommendations</h2>

- Diversify vendor base to reduce dependency and supply risk  
- Optimize bulk order volumes for cost advantage  
- Reprice slow-moving, high-margin brands  
- Clear unsold inventory through targeted discounts  
- Strengthen marketing for underperforming vendors  

---
<h2><a class="anchor" id="author--contact"></a>👤 Author & Contact</h2>

**Jivesh Kumar**  
_Data Analyst_  
📧 **Email:** [jiveshh.mishra@gmail.com](mailto:jiveshh.mishra@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/jiveshh](https://www.linkedin.com/in/jiveshh)  

---


