# AfriMart Sales Performance Analysis

## Project Overview

**AfriMart Sales Performance Analysis** is an Excel-based sales analytics project built to understand where revenue and profit come from, how performance changes over time, and which products and markets require attention.

The project takes a transactional sales dataset and turns it into an interactive Excel dashboard supported by Pivot Tables, Pivot Charts, slicers, KPI calculations, and an insights-and-recommendations report.

The analysis covers **January 2024 to December 2026** and contains **700 recorded transactions** across **10 African markets** and **7 products**.

---

## Business Objective

The main objective of this project was to answer practical business questions such as:

- How much revenue and profit did AfriMart generate?
- Which products generate the most revenue and profit?
- Which products have the strongest and weakest profit margins?
- Which countries contribute the most revenue and profit?
- How does sales performance change from year to year?
- Which months and quarters perform best or worst?
- Where is the business highly dependent on a single product?
- Which products and markets could be targeted to improve profitability?
- Are there any data-quality or date issues that could affect the conclusions?

---

## Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data preparation, analysis, Pivot Tables, Pivot Charts, dashboard development and reporting |
| **Excel Pivot Tables** | Aggregating revenue, profit and units sold across products, countries, years and months |
| **Excel Pivot Charts** | Visualizing country, product and time-based performance |
| **Excel Slicers** | Interactive filtering by Country and Year |
| **Excel formulas/calculations** | Profit margin, revenue share and profit share calculations |
| **Microsoft Word** | Formatting the final business insights and recommendations report |

---

## Dataset

The main workbook contains these sheets:

### 1. `Data`

This is the main analysis dataset.

It contains **700 rows** and the following fields:

- **Country**
- **Product**
- **Units Sold**
- **Revenue**
- **Cost**
- **Profit**
- **Date**

### 2. `Pivot_Table`

This sheet contains the aggregated analysis used to power the dashboard.

The project created Pivot Table summaries for:

- Revenue by Country
- Profit by Product
- Units Sold by Product
- Profit by Country
- Revenue Trends Over Time
- Top Products by Profit
- Monthly Sales Performance

### 3. `Dashboard`

This is the interactive dashboard where the analysis is presented visually.

### 4. `New Data`

This sheet contains an additional **525 rows** dated across 2026–2027. It was **not included in the dashboard analysis** because its relationship to the main `Data` sheet had not been confirmed.

---

# Project Process

## Step 1 — Understand the Dataset

I first reviewed the structure of the AfriMart dataset to understand:

- What each column represented
- The number of records available
- The products being sold
- The countries represented
- The available date range
- The financial fields available for analysis

The core fields were sufficient to analyze sales volume, revenue, cost, profit and time-based performance.

---

## Step 2 — Perform Data Quality Checks

Before building the dashboard, I checked the main dataset for common quality problems.

The checks included:

- Missing values
- Duplicate records
- Negative profit values
- Consistency between Revenue, Cost and Profit

A key validation check was:

**Revenue − Cost = Profit**

The report confirms that this relationship held across the main dataset.

These checks were important because incorrect or duplicated records could distort the dashboard KPIs and business conclusions.

---

## Step 3 — Confirm the Analysis Scope

I used the **`Data` sheet as the official analysis source**.

The separate **`New Data` sheet was excluded** from the dashboard because it contains another set of records dated 2026–2027 and its relationship to the main dataset had not been established.

This prevented the dashboard from mixing two potentially different datasets.

---

## Step 4 — Build Pivot Tables

After validating the data, I created Pivot Tables to summarize the information into business-friendly views.

### Revenue by Country

This Pivot Table grouped the data by country and calculated total revenue.

It allowed me to see which markets generated the most sales.

### Profit by Product

This Pivot Table grouped the data by product and calculated total profit.

This helped identify products contributing the most profit to the business.

### Units Sold by Product

This view calculated the total units sold for each product.

It was useful for comparing sales volume with revenue and profit.

### Profit by Country

This Pivot Table compared total profit across the different African markets.

### Revenue Trends Over Time

The data was grouped by year to compare revenue performance across:

- 2024
- 2025
- 2026

### Top Products by Profit

The products were compared by total profit to identify the strongest contributors.

### Monthly Sales Performance

The data was grouped by month to identify seasonal sales patterns.

Both **Revenue** and **Units Sold** were included in this analysis.

---

## Step 5 — Create Business Metrics

Beyond the basic Pivot Table totals, I calculated additional metrics for deeper analysis.

### Profit Margin

Profit margin was calculated as:

`Profit ÷ Revenue × 100`

This helped distinguish products with high sales from products that are actually highly profitable.

### Revenue Share

Revenue share was used to measure how much of total revenue each product contributed.

### Profit Share

Profit share was used to measure how much of total profit each product contributed.

These additional calculations made it possible to identify concentration and dependency risks.

---

## Step 6 — Build the Excel Dashboard

I then converted the Pivot Table analysis into an interactive dashboard.

### KPI Cards

The dashboard displays four major KPIs:

- **Total Revenue**
- **Total Profit**
- **Profit Margin**
- **Units Sold**

### Dashboard Visuals

The dashboard contains six main visualizations:

1. **Revenue by Country**
2. **Profit by Product**
3. **Units Sold by Product**
4. **Revenue Trend Over Time**
5. **Monthly Sales Performance**
6. **Top 5 Products by Profit**

### Interactive Filters

I added slicers for:

- **Country**
- **Year**

This allows the user to interact with the dashboard and filter the analysis dynamically.

---

## Step 7 — Apply a Consistent Dashboard Design

The dashboard uses a dark, professional visual style built around:

- **Dark navy background**
- **Orange accent elements**
- **White text**
- Rounded dashboard panels
- High-contrast KPI cards
- Clear chart titles
- Minimal visual clutter

The same visual language was carried into the written insights report so that the dashboard and report feel like one complete project.

---

# Key Findings

## Overall Performance

Across the main dataset:

- **Total Revenue:** ₦10.45 billion
- **Total Profit:** ₦2.10 billion
- **Profit Margin:** 20.1%
- **Units Sold:** 1,017,885

---

## Product Performance

### Rice was the main revenue driver

Rice (50kg Bag) generated approximately:

- **₦6.14B revenue**
- **₦956M profit**
- **58.8% of total revenue**
- **45.5% of total profit**
- **15.6% profit margin**

This means Rice is both a major source of revenue and a major concentration risk.

### Palm Oil was another major profit contributor

Palm Oil (5L) generated approximately:

- **₦2.27B revenue**
- **₦605M profit**
- **26.7% margin**

Rice and Palm Oil together contributed **74.3% of total profit**.

### High-margin products were relatively small contributors

Examples include:

- **Mobile Data Bundle:** 40.0% margin
- **Garri:** 33.3% margin
- **Bread:** 29.2% margin

Although these products had stronger margins, their revenue and profit contributions were much smaller than Rice and Palm Oil.

---

## Country Performance

The analysis showed that:

- **Nigeria** generated the highest revenue at approximately **₦1.62B**
- **Tanzania** generated approximately **₦1.25B**
- **Côte d’Ivoire** generated approximately **₦1.16B**

Nigeria also generated the highest total profit at approximately **₦303M**.

However, country profitability is strongly influenced by product mix. The report notes that product-level margins are fixed in the dataset, meaning differences between country margins are driven by the products sold in each market.

---

## Yearly Performance

Revenue by year:

| Year | Revenue | Profit | Margin |
|---|---:|---:|---:|
| 2024 | ₦3.13B | ₦629M | 20.1% |
| 2025 | ₦3.85B | ₦763M | 19.8% |
| 2026 | ₦3.47B | ₦708M | 20.4% |

Revenue increased by **22.9% from 2024 to 2025** and then decreased by **9.8% in 2026** based on the dates recorded in the dataset.

---

## Monthly and Seasonal Performance

The analysis showed that:

- **August** was the strongest month for revenue at approximately **₦1.25B**
- **December** was the weakest month at approximately **₦676M**
- **February** had the highest units sold at approximately **109K units**
- **Q3** was the strongest quarter across the full period
- **Q4** was the weakest quarter

This indicates a meaningful seasonal pattern that can be considered in inventory, pricing and promotional planning.

---

# Important Data Caveat

One of the most important findings was a potential date-quality issue in the 2026 data.

The report identified **57 transactions worth approximately ₦1.12B** with dates after the date of the report. In addition, November and December 2026 values were unusually high compared with the same months in 2024 and 2025.

Because of this, the reported **9.8% decline in 2026 revenue should be treated as provisional until the dates are confirmed**.

The separate `New Data` sheet also contains 2026–2027 records whose relationship to the primary dataset should be clarified before combining them with the dashboard data.

---

# Business Recommendations

Based on the analysis, the report proposed several actions:

### 1. Reduce dependence on Rice

Rice accounts for a very large share of AfriMart's revenue and profit. The business could increase the contribution of other products to reduce concentration risk.

### 2. Scale high-margin products

Products such as **Mobile Data Bundle, Garri and Bread** have stronger margins but smaller contributions.

Increasing sales of these products could improve the blended margin.

### 3. Review Nigeria's product mix

Nigeria is the largest market, but its performance is heavily influenced by Rice.

A broader product mix could reduce concentration and improve profitability.

### 4. Protect Rice margins

Because Rice has a lower margin than some other products, changes in supplier costs or pricing could have a significant effect on total profit.

### 5. Plan around seasonal patterns

The Q3 strength and Q4 weakness suggest that inventory and promotional planning should account for the observed seasonal trend.

# Dashboard Preview

Add your dashboard screenshot to the repository and update the path below:

```markdown
![AfriMart Sales Dashboard](images/AfriMart_Dashboard.png)
```

---

# Project Structure

A clean GitHub repository can be organized like this:

```text
afrimart-sales-performance-analysis/
│
├── README.md
│
├── data/
│   └── AfriMart_Sales_Dataset.xlsx
│
├── dashboard/
│   ├── AfriMart_Dashboard.xlsx
│   └── AfriMart_Dashboard.png
│
└── report/
    └── AfriMart_Sales_Insights_Report.pdf
```

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Microsoft Excel
- Data cleaning
- Data validation
- Data quality checks
- Pivot Tables
- Pivot Charts
- Dashboard development
- KPI analysis
- Revenue analysis
- Profit analysis
- Profit margin analysis
- Product performance analysis
- Country-level analysis
- Trend analysis
- Monthly and seasonal analysis
- Business insights
- Data storytelling
- Business recommendations
- Interactive dashboard design

---

# What I Learned

This project reinforced an important lesson:

**Good dashboards are not just about making charts. They are about asking the right business questions, validating the data first, finding meaningful patterns, and communicating those findings clearly.**

The project also showed how an apparently simple sales dataset can reveal product concentration, market differences, seasonal behavior and data-quality issues when analyzed systematically.

---

## Project Deliverables

- Excel sales dataset
- Excel Pivot Table analysis
- Interactive Excel dashboard
- Sales insights and recommendations report

---

## Author

**Mayowa Fasehun**

Data Analyst | Excel | SQL | Tableau | Python

GitHub: [MayortheAnayst](https://github.com/MayortheAnayst)

LinkedIn: [Mayowa Fasehun](https://www.linkedin.com/in/mayowafasehun/)