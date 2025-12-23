# 👗 Power BI – Fashion Company Marketing Analytics

## 📌 Project Overview
This project analyzes **marketing performance and sales impact** for a fashion company using **Power BI**.  
The analysis focuses on understanding **campaign effectiveness, revenue drivers, customer behavior, and product performance** to support data-driven marketing decisions.

**Industry:** Fashion Retail  
**Tools:** Power BI, DAX  
**Data Model:** Star Schema (Fact & Dimension tables)

---

## 🎯 Business Objectives
- Evaluate marketing campaign effectiveness (Ads vs Direct Sales)
- Understand revenue contribution by product, category, and region
- Analyze customer segments and purchasing behavior
- Measure marketing efficiency (CPC, CPM, ROAS)
- Support budget allocation and campaign optimization decisions

---

## 📦 Introduction to Dataset

The dataset is designed to support **marketing and sales analytics** and consists of **2 fact tables** and **multiple dimension tables**.

### 🔹 Fact Tables
1. **fact_mkt_camp_by_sku_cost**  
   - Campaign-level performance by SKU  
   - Includes revenue, ad cost, clicks, impressions, CPC, CPM  

2. **fact_order**  
   - Order-level revenue including **Ads-driven and Direct sales**  
   - Contains customer, product, discount, and pricing information  

### 🔹 Dimension Tables
- **dim_danh_sach_san_pham** – Product details and pricing  
- **dim_mkt_camp_cost** – Campaign metadata and cost metrics  
- **dim_date** – Date dimension for time analysis  
- **dim_productcategory** – Custom product categorization  
- **dim_region** – City-to-region mapping  
- **dim_unique_sku_by_campaign** – Mapping SKUs to campaigns  

---

## 📘 Data Dictionary (Key Fields Only)

| Table | Field | Type of Column |
|------|------|----------------|
| fact_order | Order_ID | Dimension |
| fact_order | Order_Date | Dimension |
| fact_order | Revenue | Measure |
| fact_order | Discount | Measure |
| fact_order | Customer_Level | Dimension |
| fact_mkt_camp_by_sku_cost | Campaign_Name | Dimension |
| fact_mkt_camp_by_sku_cost | SKU | Dimension |
| fact_mkt_camp_by_sku_cost | Ads_Revenue | Measure |
| fact_mkt_camp_by_sku_cost | Ads_Cost | Measure |
| fact_mkt_camp_by_sku_cost | Clicks | Measure |
| fact_mkt_camp_by_sku_cost | Impressions | Measure |
| dim_danh_sach_san_pham | Product_Name | Dimension |
| dim_danh_sach_san_pham | Category | Dimension |
| dim_region | Region | Dimension |
| dim_date | Date | Dimension |

---

## 🧩 Data Model Overview (Star Schema)

This project uses a **Star Schema** to ensure performance and analytical flexibility in Power BI.  
Two fact tables capture **sales transactions** and **marketing campaign performance**, while dimension tables provide descriptive context for **time, product, customer, and region**.  
This structure enables efficient slicing across **campaigns, SKUs, customer segments, and geography**, while keeping DAX logic clean and scalable.

### 🖼️ Power BI Data Model
![Power BI Data Model](images/powerbi_data_model.png)

---

## 🧠 Design Thinking Framework

This project follows a **Design Thinking approach** to ensure insights are aligned with business needs.

### 🔹 Overview
- **Empathize:** Understand marketing managers’ needs and decision constraints  
- **Define:** Identify key marketing performance and revenue questions  
- **Ideate:** Brainstorm metrics, segmentation, and analytical angles  
- **Prototype:** Build Power BI dashboards and data model  
- **Review:** Refine insights and visuals based on clarity and actionability  

📎 **Detailed Design Thinking file:**  
👉 `docs/design_thinking_overview.xlsx`

---

## 📊 Dashboard Pages Overview

### 1️⃣ Marketing Performance Overview
- Ads Revenue vs Cost
- ROAS, CPC, CPM
- Campaign trend over time

### 2️⃣ Product & Category Analysis
- Revenue by product & category
- Ads-driven vs Direct sales
- SKU performance within campaigns

### 3️⃣ Customer & Region Analysis
- Revenue by customer level
- Regional performance
- City → Region aggregation

### 4️⃣ Campaign Deep Dive
- Campaign efficiency by SKU
- Cost vs revenue contribution
- Budget utilization

---

## 🔑 Key Insights
- A small number of campaigns and SKUs drive the majority of Ads revenue.
- Direct sales remain a strong revenue base, complementing paid campaigns.
- Certain product categories consistently show higher ROAS.
- Regional performance varies significantly, supporting targeted budget allocation.
- Marketing efficiency metrics (CPC, CPM) reveal optimization opportunities.

---

## 🚀 Next Steps
- Add customer lifetime value (CLV) analysis
- Integrate retention and repeat purchase tracking
- Apply budget optimization scenarios by campaign
- Expand to forecasting and what-if simulations

---

## 📂 Repository Structure
