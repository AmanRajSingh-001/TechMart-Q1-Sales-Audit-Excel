# 📊 TechMart India: Q1 Sales & Margin Performance Audit

## 📌 Executive Summary
This project delivers a comprehensive performance and margin audit for **TechMart India** across 20 orders in Q1, covering 4 primary markets (Delhi, Mumbai, Bangalore, Chennai) and 3 core product categories (Laptops, Mobiles, Accessories).

The primary objective was to identify regional revenue leaks, audit Target AOV gaps, and provide actionable Q2 marketing & pricing recommendations to the VP of Sales.

---

## 🛠️ Tools & Technical Workflow
- **Data Lookup & Cleaning**: `VLOOKUP` with full column references (`A:C`) and `TRIM()` handling for exact string matching.
- **Conditional Logic**: `IF` and `Nested IF` formulas to classify Order Status (`Profitable` vs `Loss-Making`) and Deal Sizes (`High`, `Medium`, `Low`).
- **Aggregations & AOV Analysis**: `SUMIF`, `COUNTIF`, and Target AOV Gap calculation (`Actual AOV - Target AOV`).
- **Pivot Tables & Visuals**: Multi-level hierarchy (`Category` -> `City`), Calculated Fields (`Profit / Sales`), 3-color Heatmaps, and Interactive Category Slicers.

---

## 📊 Key Findings & Business Insights

### 1. 🚨 The Regional Leak (Mumbai Operational Breakdown)
- **Mumbai is operating at a net loss of -₹5,290** (-6.06% overall margin).
- Unlike other cities, **Mumbai is losing money across ALL 3 product lines**:
  - Accessories: **-6.09%**
  - Laptops: **-5.00%**
  - Mobiles: **-7.43%**
- Uncontrolled discounting and high order-level acquisition costs are destroying unit economics in Mumbai.

### 2. 💎 The Accessories Margin Paradox
- **Accessories yield the highest profit margin** across the company (**24.0%** overall, **30.0%** in Bangalore, Chennai, and Delhi).
- However, Accessories contribute **only 2.3% of total revenue** (₹13,300 out of ₹5,71,300).
- High margin, low volume indicates a massive untapped cross-selling opportunity.

### 3. 👑 The Profit Engine (Bangalore & Chennai)
- **Bangalore** and **Chennai** generate **more than 80% of total net profit** (₹27,000 and ₹23,710 respectively).
- Both cities significantly beat their Target AOV by **+₹5,300** (+17.67% and +15.14% above target).

---

## 💡 Q2 Strategic Recommendations

1. **Enforce Profit Margin Floors**: Implement system-level pricing rules in Mumbai and Delhi to prevent Mobile/Laptop sales below an **8% profit margin floor**.
2. **Reallocate Marketing Capital**: Shift Q2 promotional budget away from unprofitable channels in Mumbai toward high-converting, high-AOV regions (**Bangalore & Chennai**).
3. **Product Bundling Strategy**: Package high-margin Accessories (24% margin) with Laptop purchases (e.g., Laptop + Bag + Wireless Mouse) to increase revenue contribution without sacrificing profitability.

---

## 📁 Repository Files
- `TechMart_Q1_Audit.xlsx`: Full Excel workbook containing raw data, reference tables, dynamic summary tables, pivot models, and dashboard visuals.
- `Executive_Business_Report.pdf`: One-page executive summary formatted for C-suite review.
