# Szymon Khrapachenko

**Data & BI Analyst** focused on commercial analytics, unit economics, and data modeling. I design analytical data marts in PostgreSQL and develop production-grade Power BI solutions using Star Schema architecture, performance-optimized DAX, and Dynamic Row-Level Security (RLS).

[LinkedIn](https://www.linkedin.com/in/szymon-khrapachenko) • [Email](mailto:szymon.khrapachenko@gmail.com) • Ukraine (Open to Remote / Relocation)

[📄 Download CV (PDF)](Szymon_Khrapachenko_CV.pdf)

---

### 📊 Featured Analytics Projects

#### 1. [Retail Commercial & Margin Optimization Analytics](https://github.com/SzymonKhrapachenko/Retail-Commercial-Margin-Optimization-Analytics)
* **Domain:** Omnichannel Retail / Pricing Strategy & Freight Economics
* **Core Problem:** Addressed a commercial profitability gap where $1.92M in top-line revenue resulted in margin compression due to hidden product-level and freight subsidies.
* **Architecture & Solutions:**
  * Strict single-direction **Kimball Star Schema** with Zero Implicit Measures.
  * Replaced arithmetic discount averages with **Volume-Weighted Discount %** in DAX.
  * Implemented territory-level **Dynamic Row-Level Security (RLS)** via a disconnected security table.
* **Key Finding:** Isolated a **$21.7K margin leakage** across 6 loss-making sub-categories (Tables operating loss -$7.24K; bulky air freight running at -40.61% margin) and identified a 4.5% discount limit.
* **Stack:** Power BI, DAX, Power Query (M), Data Modeling, Dynamic RLS.

#### 2. [Omnichannel Retail Cohort & Commercial SQL Analytics](https://github.com/SzymonKhrapachenko/omnichannel-retail-cohort-sql-analytics)
* **Domain:** Customer Retention / Channel Migration / Basket Analysis
* **Core Problem:** Auditing customer lifecycle churn and migration patterns between direct flagship boutiques and third-party partner supermarkets.
* **Architecture & Solutions:**
  * 3-table analytical data mart schema with DDL-level defensive constraints (`CHECK >= 0`).
  * 10 production SQL queries using Window Functions (`ROW_NUMBER`, `LAG`, `DENSE_RANK`), CTEs, and anti-join logic (`LEFT JOIN ... WHERE ... IS NULL`).
  * Explicit handling of `NULL` discount values and zero-value warranty replacements.
* **Key Metrics:** Measured time-to-second-purchase velocity and recurring consumable attachment rates (razor-and-blade economics).
* **Stack:** PostgreSQL 14+, Advanced SQL (Windowing, CTEs, Aggregations), Relational Modeling.

#### 3. [Enterprise Supply Chain & Risk Intelligence Solution](https://github.com/SzymonKhrapachenko/Enterprise-Supply-Chain-Margin-Risk-Intelligence-Solution)
* **Domain:** Supply Chain Operations / Risk & Working Capital
* **Core Deliverable:** Consolidated $36.5M across 180.5K+ transactional rows with automated SQL data reconciliation (zero data loss) and built an executive SLA tracking dashboard.
* **Stack:** PostgreSQL, Power BI, DAX, Star Schema.

---

### 🛠️ Technical Arsenal

* **BI & Semantic Modeling:** Power BI Desktop, Star Schema (Kimball methodology), VertiPaq performance awareness, Zero Implicit Measures, Dynamic RLS (disconnected table pattern), Power Query (M-Engine).
* **SQL & Data Warehousing:** PostgreSQL, CTEs, Window Functions (`LAG`, `LEAD`, `DENSE_RANK`, `SUM() OVER`), Defensive Table Constraints (`CHECK`), Analytical Data Marts, Data Quality Verification.
* **Spreadsheets & Modeling:** MS Excel (Advanced Modeling, XLOOKUP, INDEX/MATCH, Pivot Tables, What-If Analysis, Reconciliation), Google Sheets, MS PowerPoint (Executive Data Storytelling).
* **Commercial Expertise:** Margin Erosion Analysis, Pricing & Discount Elasticity, Plan-Fact Variance Analysis, Unit Economics, Cohort & Retention Analysis, POS Performance Tracking.
