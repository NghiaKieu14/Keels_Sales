# Keels Supermarkets - Sales Performance Dashboard

A Power BI dashboard analysing sales performance for Keels Supermarkets across 6 store locations in Australia and New Zealand, covering January 2025 to March 2026.

---

## Project Overview

This project uses a pre-built star schema dataset to practise data modelling and dashboard design in Power BI. The focus is on translating raw transactional data into actionable business insights around revenue, profitability, regional performance, and product mix.

---

## Dataset

The dataset is structured as a star schema with the following tables:

| Table | Description |
|---|---|
| `Fact_Sales` | Transaction-level sales records including units sold, revenue, cost, and gross profit |
| `Fact_Store_Target` | Monthly revenue targets per store |
| `Dim_Date` | Date dimension for time intelligence |
| `Dim_Store` | Store details including city, state, country, and size category |
| `Dim_Product` | Product catalogue with category, category group, and standard margin |
| `Dim_Customer` | Customer segment, gender, age band, and loyalty tier |

**Period:** January 2025 – March 2026

**Locations:** Melbourne, Sydney, Brisbane, Perth, Wellington, Auckland

---

## Dashboard Highlights

**Overall performance:** $103.15K total revenue, 36.25% gross margin, $80.40 average transaction value, 98% revenue target attainment.

**Key insights explored:**

- Revenue is close to target overall, but monthly performance is unstable — a small number of strong months carry the result
- Average Transaction Value (ATV) is the main driver of revenue fluctuation, not order volume
- Regional gaps are concentrated in South Australia, Western Australia, and Auckland — each with different root causes
- Health & Wellness and Personal Care are the strongest product groups by both revenue and margin; Meat & Seafood generates high revenue but at lower margin

---

## Dashboard Structure

**Sales Overview**
KPI cards (total revenue, gross margin, ATV, revenue gap, target attainment), revenue target gauge, monthly revenue and gross profit trend

**Transaction Analysis**
Monthly orders vs ATV combo chart, payment method breakdown, hour-of-day sales distribution

**Regional Performance**
Revenue vs target by region, store-level drill-down, regional ATV and order volume comparison

**Product Performance**
Product category scatter plot (revenue vs margin), top and bottom 5 products by quarter-on-quarter growth

---

## Tools Used

- Microsoft Power BI Desktop
- Microsoft Excel (dataset source)

---
