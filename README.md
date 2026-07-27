# 🏬 Superstore Sales & Profit Dashboard | Tableau Project



An interactive Tableau workbook analyzing the classic **Sample – Superstore** sales dataset — breaking down sales and profit performance across regions, states, product categories, customer segments, and shipping modes.

---

## 🔗 Live Dashboard


https://public.tableau.com/app/profile/trishula.mitra/viz/supper_storedashboard/Dashboard2?publish=yes



---

## 🖼️ Dashboard Preview


<img width="1656" height="801" alt="Screenshot 2026-07-27 233036" src="https://github.com/user-attachments/assets/c8f2366f-6ccd-4166-877f-95951e3d9c4d" />



---


## 📌 Project Overview

| | |
|---|---|
| **Project Name** | Superstore Sales & Profit Dashboard |
| **Objective** | Analyze regional and segment-level sales and profit performance to surface top-performing areas and shipping/category trends |
| **Dataset** | Sample – Superstore Sales (Excel) |
| **Tool Used** | Tableau Desktop / Public |
| **File Type** | Packaged Workbook (`.twbx`) |

---

## 🎯 Business Problem

A retail superstore chain wants a clear, at-a-glance view of where its sales and profit are actually coming from — by region, state, product category, customer segment, and shipping method — so leadership can identify high-performing areas to invest in and underperforming areas that need attention.

---

## 🗂️ Dataset

Each record represents a single order line item, with fields including:

`Order ID` · `Row ID` · `Region` · `State` · `City` · `Zip Code` · `Product Category` · `Customer Segment` · `Ship Mode` · `Sales` · `Profit`

---

## Worksheets & Analysis

| Sheet | Chart Type | Insight |
|---|---|---|
| Sheet 1 | Bar/Text Chart | Total Sales by Region |
| Sheet 2 | Bar/Text Chart | Total Profit by Region |
| Sheet 3 | Bar/Text Chart | % of Total Profit by Customer Segment |
| Sheet 4 | Bar/Text Chart | % of Total Sales by Ship Mode |
| Sheet 5 | Pie Chart | Sales Distribution by Customer Segment |
| Sheet 7 | Donut/Pie Chart | Profit Distribution Overview |
| Sheet 8 | Filled Map | Sales by State (geographic distribution, sized & colored by Sales) |
| Sheet 9 | Bubble/Text Chart | Sales & Profit by Product Category × Customer Segment |
| Sheet 10 | Bubble/Text Chart | Sales & % Profit by Product Category × Region |

Each visualization uses **color encoding** by dimension (Region, Customer Segment, Ship Mode) and **size/text encoding** by measure (Sales, Profit, % of Total) to make performance comparisons immediately visible.

---

## Key Insights

- **Regional performance varies significantly** in both sales and profit — some regions generate strong revenue but comparatively thinner profit margins, which the side-by-side Sales vs. Profit views make easy to spot.
- **Customer Segment concentration:** a review of the % of Total Profit by Segment shows profit contribution is not evenly split across segments, highlighting which customer types are most valuable.
- **Shipping mode influences sales share:** the % of Total Sales by Ship Mode breakdown flags which shipping methods are most associated with order volume, relevant for logistics and cost planning.
- **Geographic concentration:** the state-level map highlights a handful of high-sales states carrying a disproportionate share of total revenue.
- **Category × Segment interplay:** cross-tabulating Product Category with Customer Segment and Region surfaces which category/segment/region combinations are the strongest (and weakest) performers — useful for targeted merchandising and regional strategy.

---

## Skills Demonstrated

- Connecting and structuring a federated Excel data source in Tableau
- Building comparative bar/text views with color and text-label encoding
- Percent-of-total table calculations (`PctTotal`) for segment and ship-mode analysis
- Pie and donut chart construction with wedge-size encoding
- Filled geographic map visualization using generated Latitude/Longitude and State geometry
- Bubble-style multi-dimensional views combining category, segment, and region breakdowns

---

## Repository Contents

```
├──  README.md                       # Project documentation (this file)
└── supper_store_dashboard.twbx     # Packaged workbook (data + all worksheets)



---

## 🚀 How to Use

1. Download `supper_store_dashboard.twbx`.
2. Open with **Tableau Desktop** (or **Tableau Reader** for view-only access).
3. Explore each sheet individually — Sales/Profit by Region, the State map, Customer Segment pie chart, and the Category × Region/Segment breakdowns — to review performance across every dimension.

---



⭐ If you found this project useful, consider starring the repository!
