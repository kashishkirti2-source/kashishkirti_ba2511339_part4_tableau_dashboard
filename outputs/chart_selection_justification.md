# Chart Selection Justification

## 1. Sales Trend View

**Business Question Answered:**
How are sales changing over time?

**Why This Chart Type:**
A line chart is the most appropriate choice because it clearly shows trends, growth, and seasonal changes across different time periods.

**Fields Used:**

* X-axis: Order Date (Month)
* Y-axis: Sales
* Filter: Region, Category, Customer Segment

**Design Principle Applied:**
Used a simple line chart with clear labels to emphasize trends while minimizing visual clutter.

**Mistake Avoided:**
Avoided using bar charts for time-series data, which would make long-term trends harder to identify.

---

## 2. Regional Performance View

**Business Question Answered:**
Which region performs best in terms of sales?

**Why This Chart Type:**
A bar chart allows easy comparison between different regions and quickly highlights the highest and lowest performers.

**Fields Used:**

* X-axis: Region
* Y-axis: Sales
* Color: Region
* Filter: Customer Segment, Category

**Design Principle Applied:**
Regions are displayed with consistent colors and sorted for easy comparison.

**Mistake Avoided:**
Avoided using a pie chart because comparing values across multiple regions is easier with bars.

---

## 3. Category Profitability View

**Business Question Answered:**
Which product categories generate the highest profit?

**Why This Chart Type:**
Bar charts effectively compare profit across categories and sub-categories.

**Fields Used:**

* X-axis: Category
* Y-axis: Profit
* Color: Category
* Filter: Region

**Design Principle Applied:**
Categories are clearly labeled and arranged for easy comparison.

**Mistake Avoided:**
Avoided unnecessary 3D effects and excessive colors that could reduce readability.

---

## 4. Customer Segment View

**Business Question Answered:**
Which customer segment contributes the most sales?

**Why This Chart Type:**
A bar chart provides a straightforward comparison of sales across customer segments.

**Fields Used:**

* X-axis: Customer Segment
* Y-axis: Sales
* Color: Customer Segment
* Filter: Region, Category

**Design Principle Applied:**
Used consistent formatting and colors across all categorical charts.

**Mistake Avoided:**
Avoided stacked charts that would make comparison more difficult.

---

## 5. Discount vs Profit View

**Business Question Answered:**
How does discount affect profit?

**Why This Chart Type:**
A scatter plot is best for showing the relationship between two numerical variables.

**Fields Used:**

* X-axis: Discount
* Y-axis: Profit
* Color: Category
* Filter: Region

**Design Principle Applied:**
Individual data points help identify patterns, clusters, and outliers.

**Mistake Avoided:**
Avoided line charts because there is no continuous time sequence.

---

## 6. Return Analysis View

**Business Question Answered:**
Which categories or segments have higher return rates?

**Why This Chart Type:**
A stacked bar chart compares return counts across categories while showing their composition.

**Fields Used:**

* X-axis: Category
* Y-axis: Returned Orders
* Color: Return Status
* Filter: Region

**Design Principle Applied:**
Color is used only to distinguish returned and non-returned orders.

**Mistake Avoided:**
Avoided excessive segmentation that would reduce readability.

---

## 7. Shipping Performance View

**Business Question Answered:**
Which shipping mode experiences longer delivery times?

**Why This Chart Type:**
A bar chart effectively compares average delivery days across shipping modes.

**Fields Used:**

* X-axis: Ship Mode
* Y-axis: Average Delivery Days
* Color: Shipping Delay Bucket
* Filter: Region

**Design Principle Applied:**
Consistent colors and labels improve interpretation of delivery performance.

**Mistake Avoided:**
Avoided complex visualizations that could make shipping comparisons difficult.

---

# Overall Dashboard Design Principles

* Correct chart types were selected based on the business question.
* KPI cards were placed at the top to create a clear visual hierarchy.
* Consistent colors and formatting were used throughout the dashboard.
* Interactive filters (Region, Category, and Customer Segment) allow dynamic exploration.
* Charts include clear titles and readable labels.
* Categories and regions are sorted appropriately for easier comparison.
* Misleading scales, unnecessary decorations, and excessive colors were avoided.
* The dashboard focuses on business interpretation rather than only displaying numbers, enabling leadership to make informed decisions.
