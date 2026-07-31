
# Superstore Sales & Profit Dashboard — A Statistical & Visual Investigation



## An interactive Tableau dashboard and story analyzing the **Sample – Superstore Sales** dataset — breaking down sales and profit performance by customer segment, region, state, shipping mode, and product category to uncover where revenue and profit are actually concentrated.



---


## Live Dashboard


https://public.tableau.com/app/profile/trishula.mitra/viz/supper_storedashboard/Dashboard2?publish=yes




---


## Dashboard Preview



<img width="1656" height="801" alt="Screenshot 2026-07-27 233036" src="https://github.com/user-attachments/assets/c8f2366f-6ccd-4166-877f-95951e3d9c4d" />




---

## Project Overview

| | |
|---|---|
| **Project Name** | Superstore Sales & Profit Dashboard |
| **Objective** | Identify which customer segments, regions, states, and product categories drive the most sales and profit — and where profit is underperforming relative to sales |
| **Dataset** | Sample – Superstore Sales (Excel) |
| **Tool Used** | Tableau Desktop / Public |
| **File Type** | Packaged Workbook (`.twbx`) |

---

## Business Problem

A retail superstore chain needs to know **where its revenue is coming from and where its profit is actually being made** — because the two don't always line up. This dashboard answers questions like:

- **Which customer segment generates the most sales, and which generates the most profit?**
- **Do all regions convert sales into profit at the same rate?**
- **Which shipping mode dominates order volume?**
- **Which states carry the largest share of total sales?**
- **Which product category and customer segment combination is the single most valuable?**

---

## Dataset

Each record represents one order line item:

`Order ID` · `Row ID` · `Region` · `State` · `City` · `Zip Code` · `Product Category` · `Customer Segment` · `Ship Mode` · `Sales` · `Profit`

---

## Dashboard Features

### Ship Mode Analysis
- **Breaks down the share of sales by shipping method** across every customer segment.

### Region-Wise Profit Analysis
- **Compares profit contribution by customer segment within each region**, exposing regions where segment performance is uneven.

### Customer Segment Sales & Profit Analysis
- **Ranks all four customer segments by total sales and total profit separately**, so segments that sell well but underperform on margin are easy to spot.

### State-Wise Sales Map
- **Visualizes total sales geographically**, highlighting the states carrying the largest share of revenue.

### Segment × Category Treemap
- **Cross-tabulates Product Category against Customer Segment**, sized and colored by combined Sales and Profit, to surface the single strongest product-segment combination.

### Sales Heatmap by Region
- **A color-and-value heatmap of total Sales by Region**, giving an instant visual read on regional performance without needing to read exact numbers.

---

## Key Insights

### Shipping Mode
- **Regular Air dominates shipping across all customer segments, accounting for 50–53% of sales.**
- **Delivery Truck is the second most-used method; Express Air is used the least.**

**Business Insight:**
**Heavy reliance on Regular Air suggests either a strong customer preference for standard shipping or a cost-driven default.** If Express Air carries higher margins despite low usage, there's a real opportunity to **promote faster shipping as a premium upsell** rather than treating it as a rarely-used option.

### Regional Profit by Segment
- **The Central region shows the most balanced profit split across customer segments.**
- **South and West show a much wider profit gap between segments** — in the West, Corporate accounts for 39.77% of profit versus only ~9% for Small Business.

**Business Insight:**
**Profit is not evenly distributed by region, so a one-size-fits-all regional strategy would be the wrong move.** South and West specifically need segment-level attention — Small Business underperforms there even though it performs better in other regions, which points to a regional, not a segment-wide, problem.

### Customer Segment Sales
- **Corporate leads all segments in sales at $5.5M — 39.4% of total revenue** — followed by Home Office ($3.56M), Consumer ($3.06M), and Small Business ($2.79M).

**Business Insight:**
**Corporate is the revenue backbone of the business.** Nearly 40% of total sales come from a single segment, so any growth strategy should prioritize **retaining and expanding Corporate accounts** — losing even a small share here has an outsized impact compared to the smaller segments.

### Customer Segment Profit
- **Corporate again leads in profit at 39.41% ($599,746).**
- **Home Office contributes 20.92% of profit ($318,354) despite lower sales than Consumer** — meaning Home Office is more profitable per dollar of sales than Consumer.

**Business Insight:**
**Consumer generates high sales volume but a comparatively low profit share — a margin problem, not a demand problem.** This points to Consumer being discount-heavy or costly to serve, and is worth a dedicated pricing/promotions review.

### State-Wise Sales
- **Sales are heavily concentrated in a small number of states**, with Texas and California standing out as the largest contributors.

**Business Insight:**
**Since sales are geographically concentrated in a few large states, inventory, marketing spend, and delivery infrastructure investment should weight toward these high-performing states** rather than being spread evenly nationwide.

### Segment × Category
- **Technology sold to Corporate customers is the single largest block in the entire dataset, at $2,294,749** — dominating the treemap both visually and numerically.

**Business Insight:**
**Technology + Corporate is the single most valuable product-segment combination in the business**, and is disproportionately valuable compared to every other combination — a strong candidate for **bundling, loyalty programs, or dedicated account management.**

---

## Business Impact

This dashboard enables stakeholders to:

- **Identify which customer segments to prioritize for retention and growth.**
- **Spot regions where profit isn't keeping pace with sales, and investigate why.**
- **Direct logistics and marketing investment toward the highest-performing states.**
- **Recognize the single most valuable product-segment combination for targeted account management.**

---

## Skills Demonstrated

- **Building comparative bar, pie, treemap, heatmap, and filled-map visualizations in Tableau.**
- **Percent-of-total calculations for segment and shipping-mode breakdowns.**
- **Cross-tabulated (two-dimension) analysis using treemaps and heatmaps.**
- **Data storytelling using Tableau Story Points**, each pairing a Statistical Analysis with a written Business Insight.
- **Translating raw sales and profit data into segment-, region-, and state-specific recommendations.**

---

## Repository Structure

```
Data analysis files 
README.md
supper_store_dashboard.twbx
---

## How to Use

1. **Download `supper_store_dashboard.twbx`.**
2. **Open with Tableau Desktop** (or Tableau Reader for view-only access).
3. **Navigate to the "Data Insight" story** to walk through every finding in sequence — Ship Mode, Regional Profit, Segment Sales, Segment Profit, State Sales, and the Segment × Category Treemap — or explore each worksheet individually.

---

## What I Learned

Through this project, I learned how to:

- **Pair every chart with a written Statistical Analysis and Business Insight**, rather than leaving the visualization to speak for itself.
- **Separate sales performance from profit performance**, since the two frequently tell different stories about the same segment or region.
- **Use treemaps and heatmaps to surface the single most valuable combination in a dataset**, not just the top-performing single dimension.
- **Build a Tableau Story that reads as a business narrative**, not just a sequence of charts.

---


