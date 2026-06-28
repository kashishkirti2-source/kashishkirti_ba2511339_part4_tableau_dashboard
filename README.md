# Business Problem Summary

The leadership team requires an executive Tableau dashboard to monitor sales performance, profitability, customer behavior, shipping efficiency, discount impact, and return patterns. The objective is to present key business metrics visually so that leadership can identify opportunities, monitor risks, and make informed business decisions.

---

# Dataset Description

The dataset contains retail order-level information including customer details, geographic information, product categories, sales, profit, discounts, shipping details, returns, customer ratings, and marketing campaign channels.

---

# Tableau Workbook Description

The Tableau workbook contains an executive dashboard with multiple interactive visualizations designed to monitor overall business performance and support leadership decision-making.

---

# Data Inspection

## Date Fields

* order_date
* ship_date

## Geographic Fields

* region
* state
* city

## Categorical Fields

* order_id
* customer_id
* customer_segment
* category
* sub_category
* product_name
* ship_mode
* campaign_channel

## Numerical Measures

* sales
* quantity
* discount
* profit
* delivery_days
* customer_rating

## Binary / Flag Field

* return_flag

---

# Assumptions

* order_date and ship_date are valid date fields.
* return_flag uses 0 for non-returned orders and 1 for returned orders.
* Sales and Profit values are measured in the same currency.
* Geographic fields are correctly assigned and suitable for regional analysis.
* Customer ratings are assumed to be on a consistent rating scale across all records.
