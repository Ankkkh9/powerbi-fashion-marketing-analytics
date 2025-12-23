# Fashion Marketing Analytics Dashboard (Power BI)

## 📌 Project Overview
This project analyzes **marketing performance and customer behavior** for a fashion e-commerce company using **Power BI**.  
The objective is to support **marketing optimization and expansion decisions** by evaluating campaign efficiency, customer engagement, conversion performance, and revenue contribution.

**Industry:** Fashion / Apparel  
**Business Model:** Direct-to-Consumer (DTC)  
**Tools:** Power BI, SQL, Excel  

---

## 📂 Introduction to Dataset

The dataset represents marketing and sales performance of a fashion company across multiple channels and campaigns.

It combines information related to:
- Marketing spend and campaign performance
- Customer transactions and revenue
- Product and customer attributes
- Time-based performance trends

The dataset is designed to simulate a real-world **marketing analytics environment**, supporting analysis across the full funnel from **ad spend → conversion → revenue**.

---

## 🧾 Data Dictionary (Key Fields)

| Category | Field | Description |
|-------|------|------------|
| Date | Order Date | Transaction date |
| Marketing | Channel | Marketing channel (Paid, Organic, Social, etc.) |
| Marketing | Campaign | Campaign identifier |
| Marketing | Spend | Advertising cost |
| Marketing | Impressions | Number of ad impressions |
| Marketing | Clicks | Number of clicks |
| Sales | Orders | Number of completed orders |
| Sales | Revenue | Sales revenue |
| Customer | Customer ID | Unique customer identifier |
| Customer | Customer Type | New / Returning |
| Product | Category | Product category |
| Product | Sub-Category | Product sub-category |

> *Note: The dataset was pre-processed to ensure consistency across time, campaign, and customer dimensions.*

---

## 🎯 Business Objectives
- Evaluate marketing spend efficiency (ROAS, CPA)
- Identify high-performing campaigns and channels
- Understand customer conversion behavior
- Analyze funnel drop-offs
- Support budget reallocation and growth decisions

---

## 🧠 Design Thinking Approach (High-Level)

This project applies a **design thinking framework** to ensure the dashboard addresses real business decision needs rather than reporting metrics only.

The approach focuses on:
- Understanding stakeholder goals and decision constraints
- Defining clear business questions for marketing optimization
- Designing insight-driven dashboards
- Iterating based on clarity and actionability

👉 **[View detailed Design Thinking steps](design-thinking/README.md)**

---

## 📊 Dashboard Structure

### 1️⃣ Marketing Performance Overview
- Total Revenue, Spend, ROAS
- Revenue & Spend trends over time
- Channel contribution to revenue

---

### 2️⃣ Campaign Performance Analysis
- Top & bottom campaigns by ROAS
- Spend vs Revenue comparison
- Campaign efficiency benchmarking

---

### 3️⃣ Conversion Funnel Analysis
- Impression → Click → Purchase
- Conversion rates by channel
- Funnel drop-off identification

---

### 4️⃣ Customer Segmentation
- New vs Returning customers
- Average Order Value (AOV)
- Revenue contribution by customer type

---

## 📈 Key Insights

- Marketing performance is driven by a **small number of high-ROAS campaigns**.
- Returning customers generate **higher revenue efficiency** compared to new customers.
- The largest conversion drop occurs between **click and purchase**, indicating optimization opportunities.
- Increasing conversion efficiency delivers higher ROI than increasing traffic volume alone.

---

## 🧩 Strategic Recommendations

### Marketing Optimization
- Reallocate budget toward consistently high-ROAS campaigns.
- Reduce spend on low-efficiency campaigns with weak conversion.

### Funnel Improvement
- Optimize landing pages and checkout experience to reduce drop-offs.
- Strengthen retargeting strategies for high-intent users.

### Customer Strategy
- Invest in retention programs for returning customers.
- Use segmentation to personalize offers and improve AOV.

---

## 🔑 Key Takeaways
- Marketing efficiency matters more than raw traffic volume.
- A small set of campaigns drives a disproportionate share of revenue.
- Conversion optimization and retention offer the highest growth leverage.
- Dashboards should focus on **decision support**, not just reporting.

---

## 🚀 Next Steps
- Integrate cohort-based retention and CLV analysis
- Add predictive insights for budget planning
- Expand dashboard with real-time performance monitoring
