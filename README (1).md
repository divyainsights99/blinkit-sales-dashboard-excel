# Blinkit Sales Dashboard – Excel

An interactive Excel dashboard analyzing Blinkit's grocery sales, outlet performance, and item-level trends, built with PivotTables, PivotCharts, and slicers.

## 📊 Overview

This dashboard breaks down Blinkit's sales across outlet size, location tier, item type, and fat content, with interactive filters for Outlet Size, Outlet Location Type, and Item Type.

**Key Metrics**
| Metric | Value |
|---|---|
| Total Sales | ₹1.20M |
| Average Sales | ₹141 |
| No. of Items | 8,523 |
| Average Rating | 4.0 |

## 🔍 What the Dashboard Shows

- **Outlet Establishment Trend** – sales by the year each outlet was established (2011–2022)
- **Outlet Size Split** – High (37%), Medium (42%), Small (21%) share of sales
- **Outlet Location Tier** – sales by Tier 1, Tier 2, and Tier 3 locations
- **Outlet Type Breakdown** – Total Sales, Avg Sales, and No. of Items across Grocery Store and Supermarket Types 1–3
- **Fat Content Split** – Low Fat (35%) vs Regular (65%) share of sales, and by outlet tier
- **Item Type Performance** – sales ranked across 15 categories, from Fruits & Vegetables down to Seafood
- **Interactive Slicers** – filter the whole dashboard by Outlet Size, Outlet Location Type, and Item Type

## 🛠️ Tools & Techniques Used

- Microsoft Excel (PivotTables & PivotCharts)
- Data cleaning and transformation on raw item-level outlet data
- Slicers for interactive filtering
- Donut and bar charts for category and tier comparisons
- Custom dashboard design (KPI cards, trend line, ranked bar charts)

## 📁 Repository Structure

```
blinkit-sales-dashboard/
├── README.md
├── Blinkit_Raw_Data.xlsx             # Raw/source outlet & item data
└── Blinkit_Sales_Analysis.xlsx       # Final workbook (Pivot Table + Dashboard + Data)
```

## 🚀 How to Use

1. Download `Blinkit_Sales_Analysis.xlsx`
2. Open in Microsoft Excel (2016 or later recommended for full slicer support)
3. Use the slicers on the **Dashboard** sheet to filter by Outlet Size, Location Type, or Item Type
4. Explore the **Pivot Table** sheet to see how each visual is built

## 📌 Key Insights

- Fruits and Vegetables and Snack Foods are the top two item categories, each contributing ₹0.18M in sales
- Medium-sized outlets drive the largest share of sales (42%), ahead of High (37%) and Small (21%)
- Regular fat items account for 65% of total sales versus 35% for Low Fat
- Supermarket Type1 leads all outlet types by a wide margin in both total sales (₹787.5K) and item count (5,577)
- Sales by outlet establishment year peaked in 2018 (₹204.5K) before dipping again

## 👤 Author

**Divya Gupta**
Aspiring Data Analyst | Python, SQL, Power BI, Excel
GitHub: [@divyainsights99](https://github.com/divyainsights99)
