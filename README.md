# Szymon Khrapachenko

Data & BI Analyst specializing in commercial analytics, retail unit economics, and data modeling. I build analytical data marts in PostgreSQL and end-to-end Power BI reporting with clean Star Schemas, custom DAX measures, and Dynamic RLS.

[LinkedIn](https://www.linkedin.com/in/szymon-khrapachenko) • [Email](mailto:szymon.khrapachenko@gmail.com) • Ukraine (Open to Remote / Relocation)

[📄 Download CV (PDF)](Szymon_Khrapachenko_CV.pdf)

---

### 📊 Featured Projects

#### 1. [Retail Commercial & Margin Optimization Analytics](https://github.com/SzymonKhrapachenko/Retail-Commercial-Margin-Optimization-Analytics)
* Audited 1,370 retail orders ($1.92M sales) to identify why top-line revenue was failing to deliver operating profitability.
* Modeled a single-direction Kimball Star Schema (Zero Implicit Measures) and built a territory-level Dynamic RLS model via a disconnected security table.
* Replaced distorted arithmetic averages with Volume-Weighted Discount % in DAX, pinpointing a $21.7K margin leakage across 6 sub-categories (Tables operating loss -$7.24K; bulky air freight at -40.6% margin) and establishing a strict 4.5% discount ceiling.

#### 2. [Omnichannel Retail Cohort & Commercial SQL Analytics](https://github.com/SzymonKhrapachenko/omnichannel-retail-cohort-sql-analytics)
* Built a 3-table analytical data mart with DDL-level constraints (`CHECK >= 0`) and production handling of `NULL` discounts and warranty replacements.
* Authored 10 analytical queries utilizing CTEs, window functions (`ROW_NUMBER`, `LAG`, `DENSE_RANK`), and anti-joins (`LEFT JOIN ... WHERE ... IS NULL`).
* Analyzed customer retention, time-to-second-purchase velocity, and consumable attachment rates (coffee pods vs. hardware) to track churn from direct stores to retail partner networks.

#### 3. [Enterprise Supply Chain & Risk Intelligence Solution](https://github.com/SzymonKhrapachenko/Enterprise-Supply-Chain-Margin-Risk-Intelligence-Solution)
* Consolidated and audited multi-source operational records analyzing $36.5M across 180.5K+ rows with automated SQL data reconciliation (zero data loss).
* Designed an enterprise Star Schema and established automated pipelines to ensure data integrity across regional commercial markets.
* Delivered executive dashboards tracking vendor SLA compliance, lead-time volatility, and margin risks.

---

### 🛠️ Technical Skills

* **BI & Semantic Modeling:** Power BI Desktop, Star Schema (Kimball), VertiPaq performance optimization, Zero Implicit Measures, Dynamic RLS (disconnected table pattern), Power Query (M).
* **SQL & Databases:** PostgreSQL 14+, CTEs, Window Functions (`LAG`, `LEAD`, `DENSE_RANK`, `SUM() OVER`), Table Constraints (`CHECK`), Analytical Data Marts, Data Quality Verification.
* **Spreadsheets & Presentation:** MS Excel (Advanced Modeling, XLOOKUP, INDEX/MATCH, Pivot Tables, What-If Analysis), Google Sheets, MS PowerPoint (Executive Storytelling).
* **Commercial Expertise:** Margin Leakage & Pricing Elasticity, Plan-Fact Variance, Unit Economics, Cohort & Retention Analysis, POS Performance Tracking.
