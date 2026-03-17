# 📊 Local Store Sales Dashboard

An interactive Excel-based dashboard that unifies sales, orders, customer demographics, and channel performance into a single, actionable view.

---

## 📌 Project Overview

This dashboard is built for **store managers**, **operations**, **marketing**, and **finance teams** who need quick, reliable insights to make inventory, promotion, and channel decisions.

---

## ⚠️ Business Problem

### Problem Statement
Local store teams often lack a single, reliable view of:
- Revenue trends
- Order volumes
- Customer segments
- Fulfillment health

Data scattered across multiple spreadsheets makes it slow and error-prone to answer critical questions like:
> Where should we move inventory? Which channels need more investment? Which customer groups respond best to promotions?

### Why This Matters

| Issue | Impact |
|-------|--------|
| **Stockouts/Overstock** | Increases costs and reduces sales |
| **Wasted Marketing Spend** | Poor targeting across channels/segments |
| **High Return/Refund Rates** | Erodes margin and customer trust |

### Primary Stakeholders
- Store Manager
- Regional Operations
- Marketing Manager
- Inventory Planner
- Finance Analyst

---

## 🎯 Dashboard Goal

**Provide a single, interactive Excel dashboard** that surfaces the most important sales drivers and operational health metrics so stakeholders can act quickly and confidently.

### Specific Objectives

- ✅ Show revenue and order volume trends by month
- ✅ Highlight top-performing regions and channels
- ✅ Reveal customer demographic composition and behavior
- ✅ Expose order fulfillment health (delivered, returned, refunded, cancelled)
- ✅ Allow fast filtering by month, channel, and product category

---

## 📈 Key Visuals

| Visual | Chart Type | Purpose | Key Metrics |
|--------|------------|---------|-------------|
| **Sales vs Orders** | Combo chart (bars + line) | Compare revenue trend with order count | Total Amount; Order Count |
| **Top Regions** | Horizontal bar chart | Rank states/regions by revenue | State; Sales Amount |
| **Sales by Gender** | Pie chart | Show revenue split by gender | % Revenue by Gender |
| **Orders by Age and Gender** | Clustered column chart | Identify demographic order patterns | Age Group; Gender; Order Count |
| **Order Status** | Pie chart | Monitor fulfillment outcomes | Delivered; Returned; Refunded; Cancelled |

> **Note:** Slicers for **Month**, **Channel**, and **Category** control all charts. Charts are built from pivot tables so numbers update when source data is refreshed.

---

## 📁 Data and Files

### Repository Structure

```
├── dashboard/
│   └── dashboard.xlsx
├── data/
│   └── (source data files)
└── README.md
```

### Data Fields

| Field | Description |
|-------|-------------|
| `OrderID` | Unique order identifier |
| `OrderDate` | Date of order |
| `Amount` | Order revenue amount |
| `Channel` | Sales channel (Amazon, Flipkart, Myntra, etc.) |
| `State` | Shipping state or region |
| `Gender` | Customer gender |
| `AgeGroup` | Age bucket (Teen, Adult, Senior) |
| `OrderStatus` | Delivered, Returned, Refunded, Cancelled |

### Data Quality Checklist

- [ ] Ensure `OrderDate` uses a consistent date format
- [ ] Remove duplicate `OrderID` entries
- [ ] Flag or fill missing values for `Amount`, `Channel`, and `State`
- [ ] Confirm currency and units for `Amount`

---

## 🚀 How to Use

### 1. Open the File
Open `dashboard/dashboard.xlsx` in Excel and enable editing.

### 2. Refresh Data
If the dashboard uses external connections, refresh the data source before using slicers.

### 3. Use Slicers
Apply **Month**, **Channel**, and **Category** slicers on the left to filter all visuals.

### 4. Read the Charts

| Chart | Use Case |
|-------|----------|
| **Sales vs Orders** | Check seasonality and average order value changes |
| **Top Regions** | Prioritize logistics and marketing |
| **Demographic Charts** | Design targeted campaigns |

### 5. Export or Share
Copy charts or export selected sheets to PDF for reports.

---

## 💡 Insights and Example Actions

Use these templates to capture findings and convert them into actions:

### Revenue Concentration
> **Insight:** Top 3 regions contribute **X%** of total revenue.
> 
> **Action:** Prioritize inventory and marketing in those regions.

### Customer Composition
> **Insight:** Women account for **A%** of revenue.
> 
> **Action:** Create women-focused product bundles and creatives.

### Channel Performance
> **Insight:** Channel X drives **Y%** of orders but has lower average order value.
> 
> **Action:** Run higher-value promotions on Channel X or shift premium SKUs to higher-value channels.

### Order Health
> **Insight:** Delivered rate is **D%**; returns/refunds are **R%** combined.
> 
> **Action:** Investigate top return reasons and improve product descriptions or quality checks.

### Demographic Behavior
> **Insight:** Age group Z orders frequently but has low average order value.
> 
> **Action:** Introduce upsell bundles targeted at that age group.

---

<img width="1920" height="1080" alt="Screenshot 2026-03-17 171557" src="https://github.com/user-attachments/assets/44cc5250-452e-4658-9ad2-daaffcf13019" />


---

## 📄 License

This project is provided as-is for educational and business analysis purposes.
