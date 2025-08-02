# 🛒 Walmart Sales Analytics - Power BI Dashboard

## 📊 Dashboard Overview
This interactive Power BI dashboard analyzes Walmart sales data across **5 key pages**, revealing trends in revenue, customer behavior, product performance, and payment methods.

---

## 📑 Dashboard Pages

### 1. **Sales Performance (Overview)**
**Key Metrics (Card Visuals):**
- **Total Revenue**: `SUM(Total)`  
- **Total COGS**: `SUM(COGS)`  
- **Gross Profit**: `SUM(Gross Income)`  
- **Avg. Customer Rating**: `AVG(Rating)`  

**Visualizations:**  
- **Revenue by Branch**  
  - *X-axis*: Branch  
  - *Y-axis*: `SUM(Total)`  
  - *Chart Type*: Column Chart  

- **Revenue by City**  
  - *X-axis*: City  
  - *Y-axis*: `SUM(Total)`  
  - *Chart Type*: Bar Chart  

- **Revenue Trend (2023)**  
  - *X-axis*: Date  
  - *Y-axis*: `SUM(Total)`  
  - *Chart Type*: Line Chart  

- **Payment Method Distribution**  
  - *Values*: `COUNT(Invoice ID)`  
  - *Legend*: Payment Method  
  - *Chart Type*: Doughnut Chart  

---

### 2. **Customer Insights**
**Visualizations:**  
- **Revenue by Customer Type & Gender**  
  - *X-axis*: Customer Type  
  - *Y-axis*: `SUM(Total)`  
  - *Color*: Gender  
  - *Chart Type*: Stacked Bar Chart  

- **Customer Type Distribution**  
  - *Values*: `COUNT(Invoice ID)`  
  - *Legend*: Customer Type  
  - *Chart Type*: Donut Chart  

- **Price Sensitivity Analysis**  
  - *X-axis*: `SUM(Quantity)`  
  - *Y-axis*: `SUM(Unit Price)`  
  - *Size*: `SUM(Total)`  
  - *Color*: Product Line  
  - *Chart Type*: Scatter Plot  

---

### 3. **Product Performance**
**Visualizations:**  
- **Revenue by Product Line**  
  - *Category*: Product Line  
  - *Values*: `SUM(Total)`  
  - *Chart Type*: Treemap  

- **Top 5 Products**  
  - *X-axis*: Product Line  
  - *Y-axis*: `SUM(Total)`  
  - *Sort*: Descending  
  - *Chart Type*: Clustered Bar Chart  

- **Product Trends Over Time**  
  - *X-axis*: Date  
  - *Y-axis*: `SUM(Total)`  
  - *Legend*: Product Line  
  - *Chart Type*: Line Chart  

- **Product Metrics Table**  
  - *Columns*: Product Line, `SUM(Quantity)`, `SUM(Total)`, `AVG(Rating)`  

---

### 4. **Time & Payment Analysis**
**Visualizations:**  
- **Peak Sales Hours**  
  - *X-axis*: Hour of Day  
  - *Y-axis*: Day of Week  
  - *Values*: `SUM(Total)`  
  - *Chart Type*: Heatmap  

- **Payment Method Preference**  
  - *Stages*: Payment Method  
  - *Values*: `COUNT(Invoice ID)`  
  - *Filter*: Customer Type  
  - *Chart Type*: Funnel Chart  

- **Daily Sales Trends**  
  - *Date*: Date  
  - *Values*: `SUM(Total)`  
  - *Chart Type*: Calendar Heatmap (Custom Visual)  

---

### 5. **Profitability & Margins (Optional)**
**Visualizations:**  
- **Profit Breakdown**  
  - *Stages*: COGS → Gross Income → Net Profit  
  - *Chart Type*: Waterfall Chart  

- **Avg. Gross Margin %**  
  - *Value*: `AVG(Gross Margin Percentage)`  
  - *Chart Type*: Gauge Chart  

- **Margin by Product Line**  
  - *X-axis*: Product Line  
  - *Y-axis*: `AVG(Gross Margin Percentage)`  
  - *Chart Type*: Bar Chart  

---

## 🛠️ Tools Used
- **Power BI** (Data modeling, DAX, visualization)
- **Data Sources**: Walmart Sales Dataset (2023)

---

## 🔍 How to Use
1. Download the `.pbix` file (if provided).
2. Open in Power BI Desktop to interact with filters/slicers.
3. Hover over visuals for tooltips and drill-down options.

---

## 📂 Repository Contents
- `/images`: Screenshots of all dashboard pages.
- `Walmart_Sales_Analysis.pbix`: Power BI report file *(optional)*.
