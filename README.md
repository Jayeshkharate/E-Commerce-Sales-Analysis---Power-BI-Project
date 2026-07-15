# E-Commerce Sales Analysis — Power BI Project

A **Power BI** project that analyzes an e-commerce company's sales, customers, and deliveries to find top products, track revenue trends, and improve logistics. Using **DAX and SQL**, it turns raw order data into an interactive dashboard with actionable insights to boost profit and streamline operations.

---

## The Problem

An e-commerce business generates huge volumes of order, customer, and delivery data — but that data only creates value when it answers real questions about where revenue comes from, why it leaks, and how operations can improve.

The core question this project answers:

> **How is the business really performing on revenue, customers, and logistics — and where are the biggest opportunities to grow profit and improve customer experience?**

To answer it, the dashboard tackles six specific business objectives:

- Year-over-year revenue performance
- The impact of product returns
- Products causing the greatest revenue loss
- The lowest-revenue months
- Region-wise business impact
- Whether product ratings actually affect sales

---

## What I Did

**Built an end-to-end Power BI dashboard** from an Orders and Customers data model, using DAX measures (`CALCULATE`, `SUM`, `RELATED`, `DISTINCTCOUNT`, `FILTER`, `SAMEPERIODLASTYEAR`, and more) to compute every metric.

**1. Prepared the data**
- Modeled two tables — Orders and Customers
- Cleaned nulls from Location, Product Category, and Unit Price fields

**2. Analyzed customers**
- Tracked customer growth over time and segmented by gender
- Found customer count grew **42% from 2015 to 2020**, peaking in 2020

**3. Tracked revenue**
- Measured revenue YoY and by month to spot peaks and troughs
- Identified strong and weak periods for targeted promotions

**4. Examined logistics**
- Compared delivery times and on-time vs. late rates across shipping modes
- Pinpointed international shipping as the main source of delays

**5. Investigated returns, products & ratings**
- Broke down return reasons and their revenue impact
- Identified low-contribution products and tested whether ratings drive sales

---

## Key Findings

| Insight | What it means |
|---|---|
| Customer count grew **42% (2015 to 2020)**, best year **2020** | Strong growth trajectory; 2016 & 2018 were weakest |
| Missing/wrong/defective items = **18K returns (58% of all returns)** | Accurate product descriptions could cut returns by **~42%** |
| **Express** delivers 85%+ on time; **"Shipped from Abroad"** drives most delays | Improving international logistics is the biggest delivery win |
| Avg. delivery ~**10 days**; abroad up to **15 days**, Express as fast as **4 days** | Use Express for time-sensitive orders |
| Weakest months: **June, September, November** | Plan promotional campaigns to lift these periods |
| Ratings show **no direct impact on sales** — low-rated items sold most | Sales are driven by factors other than rating |
| Most business comes from **Africa** | Room to expand into Asian and European markets |

---

## Conclusion

The dashboard gives the business a clear, data-driven view of what's working and where profit is leaking. Revenue is growing and concentrated in strong months and modes, but returns, international delivery delays, and underperforming products are dragging on results.

Recommended actions:
- **Cut returns** by improving product quality and providing accurate product descriptions (a ~42% reduction opportunity)
- **Fix international shipping** to reduce late deliveries; use Express for time-sensitive items
- **Run promotions in weak months** (June, September, November) to smooth revenue
- **Boost underperforming products** with targeted offers (trade-in discounts, EMI, extended warranties)
- **Expand beyond Africa** into Asian and European regions
- **Balance customer segments** with female-targeted campaigns

In short: the analysis shows where revenue comes from, why it's lost, and how logistics and product strategy can be tuned — turning raw order data into decisions that grow profit and improve customer experience.

---

## Tools & Skills

**Power BI** — Data Modeling, DAX (CALCULATE, SUM, RELATED, DISTINCTCOUNT, FILTER, SAMEPERIODLASTYEAR), Interactive Dashboards
**SQL** — Data extraction and querying
**Skills** — Data Cleaning, Revenue & Customer Analytics, Logistics Analysis, KPI Reporting, Data Storytelling

## Files in This Repository

| File | Description |
|---|---|
| `e-commerce.pbix` | Power BI file with the full data model, DAX measures, and dashboard |
| `e.commerce.sql` | SQL queries used for data extraction and analysis |
| `e-commerce answer.docx` | Written breakdown of each business question and its findings |
| `Jayesh Ecommerce Sales PowerBI project PPT` | Presentation walking through the analysis and recommendations |

---

*Author: **Jayesh Kharate** · Data Analyst*
