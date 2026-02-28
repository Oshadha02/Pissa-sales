# Pizza Sales Analytics (SQL + Excel)

This project analyzes pizza sales transactions to understand **revenue performance**, **order trends**, and **product popularity**. The goal is to generate clear KPIs and business insights such as peak ordering times, best sellers, and category/size contribution.

---

## Project Objectives
- Track core business KPIs (revenue, orders, AOV, pizzas sold)
- Identify **daily** and **hourly** ordering trends
- Analyze sales contribution by **pizza category** and **pizza size**
- Find **top 5** and **bottom 5** pizzas by quantity sold

---

## Dataset
- File: `pizza_sales.csv`
- Rows/Columns: **48,620 rows × 12 columns**
- Key columns:
  - `order_id`, `order_date`, `order_time`
  - `pizza_name`, `pizza_category`, `pizza_size`
  - `quantity`, `unit_price`, `total_price`

---

## Tools & Technologies
- **SQL (MS SQL Server / SSMS)**: KPI + trend analysis queries
- **Excel**: quick analysis / pivots / reporting
- **PowerPoint**: presentation design (optional)

---

## Key Analysis (SQL)

### A) KPIs
- Total Revenue
- Average Order Value (AOV)
- Total Pizzas Sold
- Total Orders
- Average Pizzas Per Order

### B) Trends
- Daily trend for total orders (by weekday)
- Hourly trend for total orders (by hour)

### C) Product Performance
- % of sales by pizza category
- % of sales by pizza size
- Total pizzas sold by category (monthly filter supported)
- Top 5 best sellers
- Bottom 5 best sellers

---

## SQL Queries
File: `PIZZA SALES SQL QUERIES.docx`

> Note: You can apply **Month / Quarter / Week** filters using a `WHERE` clause as shown in the doc.

---

## Repository Structure
```text
Pizza sales analytics/
├─ pizza_sales.csv                      # Dataset
├─ pizza_sales excel file.xlsx          # Dataset (Excel)
├─ analysis_file.xlsx                   # Analysis / reporting (Excel)
├─ PIZZA SALES SQL QUERIES.docx         # SQL queries (KPIs + trends + best sellers)
├─ Pizza Background.pptx                # Presentation background (optional)
├─ pizza_img.jpg                        # Image asset (optional)
└─ README.md                            # Project documentation

---

## How to Run (Quick Start)

Option A — Run SQL Analysis
1. Open SSMS and create a database (pizza_db)
2. Import pizza_sales.csv into a table (pizza_sales)
3. Open PIZZA SALES SQL QUERIES.docx
4. Run queries section-by-section to generate KPIs and insights

Option B — Excel Review
1. Open analysis_file.xlsx to view analysis outputs
2. IUse filters/pivots to explore category, size, and time trends

---

## Notes

- KPI values will be produced when you run the SQL queries on your local database.  
- If your order_date is stored as text, convert it to a proper DATE type for accurate filtering.

---

## Author
- Oshadha
