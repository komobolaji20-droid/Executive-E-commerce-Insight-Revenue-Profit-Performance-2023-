# Executive E-Commerce Insight: Revenue & Profit Performance (2023)
A strategic Business Intelligence solution built in **Microsoft Power BI** to analyze sales performance, profitability, and customer acquisition.

![Dashboard Executive Summary](assets/dashboard_screenshot.png)

---
##  Project Overview
This project goes beyond standard metric tracking. It implements enterprise-grade analytical frameworks—including target variance benchmarking, Pareto concentration analysis, and acquisition channel evaluation—to surface the insights that actually drive decisions. 
The result is a single-page executive dashboard that answers not just *what* happened in 2023, but *why* it matters and *where* to act next.
### Key Performance Results (2023)

| Metric | Actual | Target | Variance | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Revenue** | $82.54K | $75.89K | +9.33% | ✅ |
| **Quantity Sold** | 240 units | 211 units | +13.74% | ✅ |
| **Profit** | $16.51K | $15.09K | +9.33% | ✅ |
| **Profit Margin** | 20% | 20% | On Target | ✅ |
| **Active Customers** | 87 | 76 | +14.47% | ✅ |

> **Note:** All five KPIs exceeded or met targets for the full year.
---

## 🎯 Business Problems & Context

This solution was engineered to address five critical business problems where leadership previously lacked unified, reliable data to guide decision-making.

###  Problem 1: No Visibility Into KPI Target Performance
* **Problem Statement:** The business established annual targets for revenue, profit, quantity sold, profit margin, and customer acquisition—but lacked a unified view to confirm performance tracking. Decisions were being made on intuition rather than empirical data.

###  Problem 2: High Q4 Revenue Contraction
* **Problem Statement:** Revenue peaked sharply in June and contracted by approximately 35% through Q4 with no documented explanation. Without understanding if this trend was seasonal, demand-driven, or operational, accurate budgeting for the subsequent fiscal year was impossible.

### Problem 3: High Portfolio Concentration Risk
* **Problem Statement:** Just three product categories—**Chairs, Printers, and Laptops**—generated **61% of total revenue**. This severe concentration exposes the business to extreme risk from supply chain disruptions, pricing pressures, or category-specific demand shifts.

### Problem 4: Misaligned Marketing Spend Allocation
* **Problem Statement:** Capital was being invested into paid social channels (Facebook, Instagram) without a clear understanding of relative ROI. Email campaigns ($7.8K) and organic referrals ($7.5K) massively outperformed paid social channels (both at $0.7K), yet budget allocations failed to reflect this performance gap.

###  Problem 5: Customer Acquisition Lacks a Retention Lens
* **Problem Statement:** Active customers grew **14.47% beyond target**, a strong top-of-funnel win. However, leadership lacked visibility into whether this acquisition burst translates into long-term customer lifetime value (LTV) or simply inflated one-time transactional volume, potentially masking high churn.


##  Strategic Insights
1. **Broad Target Outperformance:** Annual revenue exceeded forecasts by 9.33%, driven significantly by customer acquisition outperforming its baseline by 14.47%. This suggests the top-of-funnel strategy was well-calibrated.
2. **Q4 Revenue Contraction (-35%):** Revenue peaked in June before declining sharply through Q4. This seasonal pattern signals a clear opportunity for year-end promotional strategy, targeted retention campaigns, or bundled product offers timed for Q3-Q4.
3. **Portfolio Concentration Risk:** Three product lines — *Chairs, Printers, and Laptops* — account for 61% of total revenue. While this concentration reflects strong performers, it creates dependency risk. Cross-selling Tablets, Monitors, and Phones represents a tangible diversification opportunity.
4. **Email & Referral Dominate Acquisition:** Email campaigns ($7.8K) and organic referrals ($7.5K) outperformed every paid channel, including Facebook and Instagram (both at $0.7K). This indicates high ROI from owned and earned channels relative to paid social spend.
5. **Online Payment Leads at $299K:** Online transactions account for the largest payment volume, with Debit Card and Cash closely behind at $252K each. Combined, Online and Debit Card make up 44% of total sales volume — pointing to a digitally-engaged customer base.


## Strategic Recommendations

Based on the insights surfaced by the dashboard, the following data-driven strategies are recommended to leadership:

### 1. Implement KPI Thresholds & Ownership
 Implement a permanent KPI variance tracking layer (as engineered in this dashboard) that updates monthly and flags any metric falling below 95% of its target. Assign a dedicated metric owner to each KPI to drive corrective action immediately when thresholds are breached.

###  2. Execute Root-Cause & Seasonal Mitigation
 Execute a root-cause analysis combining order volume, product mix, and customer churn data specifically for the Q3–Q4 pivot. Introduce a targeted Q3 promotional strategy (e.g., bundled offers, loyalty discounts) to counteract the seasonal dip, and monitor a newly established Q4 revenue floor weekly from October onward.

###  3. Portfolio Diversification Roadmap
Develop a portfolio diversification roadmap aggressively targeting underperforming segments (Tablets, Monitors, and Phones). Deploy automated cross-sell triggers at checkout and within post-purchase email flows to lift attachment rates, aiming to reduce top-3 category concentration below 50% within 18 months.

### 4. Optimize Marketing Budget Allocation
Immediately reallocate a percentage of the paid social budget into advanced email automation and referral infrastructure. Build a structured referral incentive program to amplify existing organic word-of-mouth momentum, and establish a monthly channel ROI review to ensure capital dynamically follows performance.

### 5. Deploy Cohort Retention Tracking
Enrich the analytics architecture with a cohort retention layer tracking repeat purchase velocity by acquisition channel. Establish a baseline 90-day repeat purchase target (e.g., 30% retention). For channels falling short, trigger a post-purchase nurture email sequence targeting first-time buyers within 14 days of their initial transaction.

##  Analytical Frameworks Applied
* **Target Variance Analysis:** KPI cards display both absolute values and % deviation from targets, enabling immediate performance diagnosis.
* **Pareto 80/20 Concentration Analysis:** Cumulative revenue distribution across product lines identifies the vital few driving the majority of results.
* **Acquisition Funnel Benchmarking:** Referral source revenue comparison surfaces channel efficiency beyond raw traffic volume.
* **Dynamic Narrative Headers:** Chart subtitles communicate the data story dynamically (e.g., *"Revenue Peak in June, Drops 35% in Q4"*) rather than using generic visual labels.
---
##  Tech Stack & Architecture
### Tool Application
* **Microsoft Power BI Desktop:** Dashboard design, publishing, and interactivity.
* **Power Query (M Language):** Data transformation, cleansing pipeline, and optimization.
* **DAX (Data Analysis Expressions):** Advanced KPI measures, target variance calculations, cumulative Pareto totals, time intelligence, and running totals.
### Data Model
The data architecture follows a **Star Schema** pattern to ensure efficient filtering across slicers and scalable extension for future dimensions.
* `1` Fact table: Transactional sales records.
* `4` Dimension tables: `Products`, `Dates`, `Customers`, and `Channels`.
### Dataset Scope
* **Source:** Synthetic e-commerce transactional dataset.
* **Scope:** January – December 2023 (full year).
* **Grain:** Individual order-level transactions.
---
## How to Explore This Project
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/komobolaji20-droid/Executive-E-Commerce-Insight-Revenue-Profit-Performance-2023-.git](https://github.com/komobolaji20-droid/Executive-E-Commerce-Insight-Revenue-Profit-Performance-2023-.git)
