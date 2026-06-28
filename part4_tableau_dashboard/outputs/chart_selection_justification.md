# Chart Selection Justification

## Overview

The executive dashboard was designed using visualisation best practices to ensure that business users can quickly understand key performance indicators, identify trends, compare business performance, and make informed decisions. Each chart was selected based on the business question it answers rather than for visual appearance.

---

# 1. Monthly Sales Trend

## Business Question

How are sales changing over time?

## Chart Type

Line Chart

## Why This Chart?

A line chart is the most appropriate visualisation for displaying trends over time because it clearly shows increases, decreases, and overall sales patterns across months.

## Fields Used

- X-axis: Order Month
- Y-axis: Sales
- Filter: Region, Category, Customer Segment

## Design Principle Applied

- Continuous time-series display
- Simple layout
- Clear axis labels
- Minimal visual clutter

## Mistake Avoided

A bar chart was avoided because it is less effective than a line chart for identifying trends over time.

---

# 2. Regional Performance

## Business Question

Which region generates the highest sales?

## Chart Type

Horizontal Bar Chart

## Why This Chart?

A horizontal bar chart enables easy comparison of sales across regions and allows users to quickly identify the highest and lowest performing regions.

## Fields Used

- Y-axis: Region
- X-axis: Sales
- Color: Sales
- Filter: Region, Category, Customer Segment

## Design Principle Applied

- Easy comparison
- Sorted values
- Consistent colour palette

## Mistake Avoided

Pie charts were avoided because comparing regional values is much easier using bar charts.

---

# 3. Category Profitability

## Business Question

Which product sub-categories contribute the most profit?

## Chart Type

Horizontal Bar Chart

## Why This Chart?

Bar charts clearly compare profitability between sub-categories and help identify the strongest profit contributors.

## Fields Used

- Y-axis: Sub-Category
- X-axis: Profit
- Color: Category
- Filter: Region, Customer Segment

## Design Principle Applied

- High readability
- Easy ranking
- Clear comparison

## Mistake Avoided

Treemaps were avoided because precise comparisons are more difficult than with bar charts.

---

# 4. Customer Segment Performance

## Business Question

Which customer segment generates the highest sales?

## Chart Type

Bar Chart

## Why This Chart?

A bar chart provides a simple comparison between customer segments and highlights differences in sales contribution.

## Fields Used

- X-axis: Customer Segment
- Y-axis: Sales
- Color: Customer Segment

## Design Principle Applied

- Direct comparison
- Consistent colours
- Clear labels

## Mistake Avoided

Pie charts were avoided because they make it harder to compare similar values.

---

# 5. Shipping Performance

## Business Question

Which shipping method delivers products more efficiently?

## Chart Type

Horizontal Bar Chart

## Why This Chart?

The chart allows quick comparison of average delivery days across shipping modes.

## Fields Used

- Y-axis: Ship Mode
- X-axis: Average Delivery Days

## Design Principle Applied

- Simple comparison
- Clear measurement scale
- Minimal clutter

## Mistake Avoided

Complex visualisations were avoided because shipping performance only requires straightforward comparison.

---

# 6. Discount vs Profit

## Business Question

How does discount influence profit?

## Chart Type

Scatter Plot

## Why This Chart?

A scatter plot is the most suitable chart for examining relationships between two numerical variables and identifying patterns or outliers.

## Fields Used

- X-axis: Discount
- Y-axis: Profit
- Color: Category

## Design Principle Applied

- Relationship analysis
- Pattern recognition
- Clear distribution of data points

## Mistake Avoided

Line charts were avoided because the data does not represent a time sequence.

---

# 7. Return Analysis

## Business Question

Which product categories experience higher product returns?

## Chart Type

Horizontal Bar Chart

## Why This Chart?

The bar chart enables easy comparison of return counts across product categories.

## Fields Used

- Y-axis: Category
- X-axis: Return Flag
- Color: Category

## Design Principle Applied

- Easy comparison
- Simple interpretation
- Business-focused layout

## Mistake Avoided

Pie charts were avoided because they make comparisons between categories less accurate.

---

# 8. KPI Cards

## Business Question

What are the most important business metrics?

## Chart Type

KPI Cards

## Why This Chart?

KPI cards provide executives with immediate access to the most important performance indicators without requiring detailed analysis.

## KPIs Included

- Total Sales
- Total Profit
- Profit Margin

## Design Principle Applied

- Strong visual hierarchy
- Large readable numbers
- Positioned at the top of the dashboard

## Mistake Avoided

Large tables were avoided because executives require quick access to summary information.

---

# Overall Dashboard Design Principles

The dashboard follows several visualisation best practices:

- Appropriate chart selection for each business question.
- Consistent colour palette across all visualisations.
- Clear titles and labels.
- Logical dashboard layout.
- Minimal visual clutter.
- Interactive filters for exploration.
- Dashboard actions for cross-filtering.
- KPI cards positioned prominently.
- Readable fonts and spacing.
- Executive-friendly presentation focused on decision-making.