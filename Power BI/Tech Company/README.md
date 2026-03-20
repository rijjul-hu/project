# 📊 Alone Tech Shop E-Commerce Dashboard

An interactive Power BI dashboard that visualizes brand performance, customer distribution, and revenue trends for a tech-focused e-commerce business.

---

## 📌 Project Overview

This dashboard is designed for **e-commerce managers**, **brand analysts**, **regional sales teams**, and **executive leadership** to monitor performance across brands, regions, and time. It helps identify high-performing products, customer hotspots, and sales patterns.

---

## ⚠️ Business Problem

### Problem Statement
E-commerce businesses often struggle to:
- Track brand-wise revenue and quantity sold
- Understand customer distribution across regions
- Monitor sales trends over time
- Compare performance across multiple tech brands

Fragmented data sources and lack of visual clarity make it difficult to answer:
> Which brands are driving the most revenue? Where are our customers located? How are sales trending month-over-month?

### Why This Matters

| Issue | Impact |
|-------|--------|
| **Unclear brand performance** | Missed opportunities for promotion or inventory focus |
| **No customer location insights** | Poor regional targeting and logistics planning |
| **Flat or declining revenue trends** | Delayed response to market shifts |
| **Equal quantity sold across brands** | Need to differentiate based on value, not just volume |

### Primary Stakeholders
- E-Commerce Manager  
- Brand Performance Analyst  
- Regional Sales Head  
- Marketing Strategist  
- Inventory Planner

---

## 🎯 Dashboard Goal

**Deliver a unified Power BI dashboard** that highlights brand revenue, customer geography, quantity sold, and sales trends over time.

### Specific Objectives

- ✅ Show brand-wise revenue and quantity sold  
- ✅ Map customer locations globally  
- ✅ Visualize regional sales distribution  
- ✅ Track monthly revenue trends  
- ✅ Compare brand performance by value and volume

---

## 📈 Key Visuals

| Visual | Chart Type | Purpose | Key Metrics |
|--------|------------|---------|-------------|
| **Brand Revenue** | Vertical bar chart | Compare revenue across top brands | Brand; Revenue |
| **Customer Location Map** | Geo map | Visualize customer distribution | Location; Region |
| **Quantity Sold by Brand** | Donut chart | Show volume share across brands | Brand; Quantity Sold |
| **Yearly Revenue Trend** | Line chart | Track revenue over time | Month; Revenue |
| **Regional Sales Legend** | Color-coded labels | Identify sales by region | Region |
| **Summary Metrics** | Card visuals | Display total quantity and revenue | Quantity Sold; Total Revenue |
| **Brand List** | Grid | Reference available brands | Brand Names

> **Note:** All visuals are interactive and update based on filters applied. Data is refreshed from a transactional sales table with 24,983 rows and 24,526 distinct revenue entries.

---

## 📁 Data and Files

### Data Source Overview

| Field | Description |
|-------|-------------|
| `Product` | Type of item sold (e.g., Mobile Phone) |
| `Brand` | Manufacturer or label |
| `Product Code` | Unique product identifier |
| `Price` | Unit price |
| `Dispatch Date` | Date of shipment |
| `Quantity Sold` | Units sold per transaction |
| `Customer Name` | Buyer name |
| `Customer Location` | City or town |
| `Region` | Sales region (North, South, East, West, Central) |
| `Processor Specification` | Chipset used |
| `RAM` | Memory size |
| `ROM` | Storage size |
| `Revenue` | Total revenue per transaction |

### Data Quality Checklist

- [ ] Validate unique `Product Code` per brand  
- [ ] Confirm `Dispatch Date` format and range  
- [ ] Check for missing `Revenue`, `Region`, or `Customer Location`  
- [ ] Ensure consistent units for `Price`, `RAM`, and `ROM`  
- [ ] Reconcile total revenue with summary cards

---

## 🚀 How to Use

### 1. Open the Dashboard
Launch the Power BI file and enable interactions.

### 2. Explore Brand Performance
Use the **Brand Revenue** and **Quantity Sold** visuals to compare value vs volume.

### 3. Analyze Customer Distribution
Zoom into the **Customer Location Map** to identify geographic clusters.

### 4. Monitor Trends
Use the **Yearly Revenue Trend** to spot seasonal spikes or dips.

### 5. Review Regional Sales
Use the **Regional Legend** and filters to compare performance across zones.

### 6. Export or Share
Export visuals or summary pages to PDF or PowerPoint for reporting.

---

## 🧭 Reviewer Guidance

### ✅ Quick Start Checklist
- Open dashboard and confirm data refresh  
- Check top 10 brands by revenue  
- Compare revenue vs quantity sold  
- Review customer map for regional spread  
- Scan revenue trend for anomalies

### 🔍 Visual Interpretation

| Visual | Focus | Ask Yourself |
|--------|-------|--------------|
| Brand Revenue | Value leaders | Are high-revenue brands also high-volume? |
| Quantity Sold | Volume spread | Is volume evenly distributed or skewed? |
| Customer Map | Location clusters | Are there underserved regions? |
| Revenue Trend | Time-based performance | Are there seasonal dips or spikes? |
| Regional Sales | Zone-wise comparison | Which region needs more attention? |

### ⚡ Decision Triggers

- **High revenue, low quantity** → Premium brand strategy  
- **Equal quantity, unequal revenue** → Revisit pricing or bundling  
- **Sparse customer map zones** → Expand delivery or marketing reach  
- **Flat revenue trend** → Launch seasonal campaigns or product refresh

### 🧾 Validation Steps

- Spot-check top 20 transactions  
- Confirm brand-wise revenue matches source table  
- Check for duplicate product codes  
- Validate RAM/ROM specs for consistency

---

## 💡 Insights and Example Actions

### Brand Performance
> **Insight:** Google leads with 755M revenue.  
> **Action:** Prioritize Google for promotions and inventory.

### Regional Spread
> **Insight:** South region dominates customer locations.  
> **Action:** Expand logistics and service coverage in South.

### Quantity vs Value
> **Insight:** All brands sold ~7K units, but revenue varies.  
> **Action:** Focus on high-margin brands for profitability.

### Revenue Trend
> **Insight:** Revenue peaked in Dec 2023, dipped in mid-2024.  
> **Action:** Investigate campaign timing and product launches.

---

## 📄 License

This dashboard is shared for business analysis and educational use. Add a license file (e.g., MIT or Apache 2.0) if reuse or contribution is intended.
