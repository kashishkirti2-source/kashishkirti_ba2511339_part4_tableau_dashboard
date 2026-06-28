# Part 4: Tableau Executive Dashboard & Data Storytelling

## Business Problem Summary

The objective of this project is to develop an executive Tableau dashboard that helps retail leadership monitor business performance and make data-driven decisions. The dashboard focuses on sales performance, profitability, customer segments, regional performance, shipping efficiency, discount impact, and return patterns to identify business opportunities and potential risks.

---

## Dataset Description

The dataset contains retail sales transaction data including:

* Order Date
* Region
* State
* Category
* Sub-Category
* Customer Segment
* Ship Mode
* Sales
* Profit
* Discount
* Delivery Days
* Return Status

The dataset was used to create multiple visualizations and calculated fields for business analysis.

---

## Tableau Workbook Description

The Tableau workbook (`executive_dashboard.twbx`) contains:

* Executive Dashboard
* Sales Trend View
* Regional Performance View
* Category Profitability View
* Customer Segment View
* Shipping Performance View
* Discount vs Profit View
* Return Analysis View
* KPI Cards

---

## Calculated Fields Created

The following calculated fields were created in Tableau:

* Profit Margin = Profit / Sales
* Cost = Sales − Profit
* Average Order Value = Sales / Number of Orders
* Return Rate = Returned Orders / Total Orders
* Shipping Delay Bucket = Categorized delivery days into business-friendly delay groups

---

## Dashboard Components

The executive dashboard includes:

* Total Sales KPI
* Total Profit KPI
* Profit Margin KPI
* Sales Trend
* Regional Performance
* Category Profitability
* Customer Segment Analysis
* Shipping Performance
* Discount vs Profit Analysis
* Return Analysis

---

## Filters and Interactions Used

Interactive filters included:

* Region
* Category
* Customer Segment

Dashboard interactions:

* Filter actions allowing users to click on charts and dynamically update other dashboard views.
* Interactive filtering across worksheets using the same data source.

---

## Key Business Insights

* Sales remain relatively stable over time with minor seasonal variation.
* South region generates the highest sales.
* Technology products contribute the highest profitability.
* Home Office customers generate strong revenue.
* Higher discounts are associated with lower profit.
* Standard Class shipping experiences longer delivery times.
* Furniture products have relatively higher return rates.
* Improving profitability requires balancing discounts, delivery performance, and return management.

---

## Dashboard Story Summary

The dashboard provides leadership with a comprehensive overview of business performance by combining sales, profitability, regional performance, customer behavior, shipping efficiency, and return analysis. It highlights both business strengths and operational risks while supporting strategic decision-making through interactive visualizations.

---

## Assumptions and Limitations

### Assumptions

* The dataset accurately represents business transactions.
* Sales and profit values are correctly recorded.
* Return information is complete and accurate.
* Delivery days represent actual shipping performance.

### Limitations

* The dashboard is based on historical data and does not predict future performance.
* External business factors such as competition, inflation, and customer preferences are not included.
* Results show business performance but do not establish causal relationships.

---

## Screenshots Included

The repository includes the following screenshots:

* `full_dashboard.png`
* `sales_trend_view.png`
* `regional_performance_view.png`
* `category_profitability_view.png`
* `filter_interaction_view.png`

These screenshots demonstrate the dashboard layout, individual visualizations, and interactive filtering functionality.
