
# 📊 D-Lite Electronics Sales Performance Dashboard

![Status](https://img.shields.io/badge/Project-Completed-success)
![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-green)
![Focus](https://img.shields.io/badge/Focus-Sales%20Analytics-blue)

---

## 📌 Project Overview

This project analyzes the sales performance of D-Lite Electronics, a consumer electronics distributor operating across multiple regions using a hybrid B2B and B2C model.

The goal of this analysis was to:

- Evaluate revenue performance and stability
- Identify concentration risks across regions, customers, and sales reps
- Assess product demand distribution
- Provide strategic, data-driven recommendations for sustainable growth

All data preparation, modeling, validation, and visualization were completed in Microsoft Excel.

---

# 🧹 Data Challenges & Cleaning Process

The raw dataset contained real-world inconsistencies typical of operational sales systems. Before analysis, extensive cleaning and validation were required.

### 🔎 Key Data Issues Identified

1. Inconsistent capitalization:
   - WEST / west / West
   - PETER OBI / Peter Obi / peter obi
   - Mobile / mobile / MOBILE

2. Product naming variations:
   - tv 43q vs TV 43Q
   - monitor m24 vs MONITOR M24
   - camera c100 vs Camera C100

3. Category inconsistencies:
   - Electronics vs ELECTRONICS
   - Photography vs PHOTOGRAPHY

4. Potential pricing anomalies:
   - Identical products showing inconsistent unit prices
   - Outliers reviewed and validated

<img width="1874" height="898" alt="Screenshot 2026-02-28 061453" src="https://github.com/user-attachments/assets/26cc58dd-81e9-4634-bc44-55d056614fab" />


---

## 🛠 Cleaning & Validation Steps (Excel-Based)

- Standardized region names using PROPER/UPPER functions
- Normalized product naming for accurate aggregation
- Unified category labels to prevent pivot fragmentation
- Standardized sales representative naming
- Validated revenue consistency (Units Sold × Unit Price)
- Checked for duplicate transactions
- Removed incomplete or invalid records (<2%)
- Created calculated Month  columns for time analysis
- Structured dataset using Excel Tables for dynamic pivot modeling

This ensured reliable aggregation and accurate insight generation.

---

# 📊 Business Snapshot (Reporting Period)

| Metric | Value |
|--------|--------|
| Total Revenue | ₦303M |
| Units Sold | 1,141 |
| Active Customers | 100 |
| Average Transaction Value | ₦3.03M |

---

# 🖥 Dashboard Preview

*(Insert Screenshot Here)*

---

# 🔍 Key Executive Takeaways

1️⃣ Revenue performance is strong but concentrated across specific regions, customers, and sales representatives.

2️⃣ Core electronics products (Tablets, TVs, Laptops) drive the majority of sales volume.

3️⃣ Geographic and customer diversification represent the largest strategic growth opportunities.

---

# 📈 Insights Deep Dive

---

## 🟦 Revenue & Monthly Trends

- February recorded peak sales performance.
- March experienced a correction followed by steady recovery.
- Recovery pattern suggests operational stability.
- Performance volatility indicates lack of standardized sales drivers.

**Implication:** Institutionalizing peak-performance strategies can stabilize revenue.

---

## 🟦 Sales Representative Performance

| Sales Rep | Revenue |
|-----------|----------|
| Peter Obi | ₦88M |
| Fola Balogun | ₦59M |
| Grace Amos | ₦43M |
| Chinedu Nwosu | ₦36M |
| Ifeanyi Okafor | ₦29M |

- Significant revenue gap between top and mid-tier performers.
- High reliance on top rep increases operational exposure.

**Implication:** Structured knowledge transfer and performance alignment can improve total revenue.

---

## 🟦 Product Portfolio Analysis

Top-performing products by unit volume:

- Tablet T8
- TV 43Q
- Laptop A15
- Monitor M24

Lower-performing SKUs show limited turnover.

**Implication:** Product prioritization can improve inventory turnover and profitability.

---

## 🟦 Regional & Customer Concentration

| Region | Revenue |
|--------|----------|
| West | ₦116M |
| East | ₦80M |
| South | ₦68M |
| North | ₦39M |

- West region dominates revenue contribution.
- North region underpenetrated.
- Omega Wholesale contributes ₦90M (customer concentration risk).

**Implication:** Geographic expansion and customer diversification are critical for scalable growth.

---

# 🚀 Strategic Recommendations

1. Replicate February’s high-performing sales drivers.
2. Standardize top-performing sales methodologies across team.
3. Increase penetration in underperforming regions.
4. Reduce revenue dependency on major customers.
5. Optimize product mix based on turnover performance.

---

# 🏁 Conclusion

This project demonstrates structured data cleaning, analytical modeling, and business interpretation using Excel. Beyond visualization, the analysis identifies concentration risks and provides actionable strategies for sustainable revenue growth.

The dashboard serves as a decision-support tool for revenue optimization, performance alignment, and strategic planning.
