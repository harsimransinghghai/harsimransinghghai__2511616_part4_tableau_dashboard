# Part 4: Tableau Executive Dashboard & Data Storytelling

## Business Problem Summary

This project develops an executive Tableau dashboard for a retail leadership team to monitor sales performance, profitability, customer segments, category performance, shipping efficiency, discount impact, and product return patterns. The objective is to transform transactional sales data into meaningful business insights that support strategic decision-making through interactive data visualization.

---

## Dataset Description

The analysis uses the provided retail sales dataset (`dashboard_sales_data.xlsx`) containing transactional information across multiple business dimensions, including:

- Order and shipping dates
- Geographic information (Region and State)
- Customer segments
- Product categories and sub-categories
- Sales and profit
- Discounts
- Shipping mode
- Return status
- Delivery duration

The dataset contains both categorical and numerical variables suitable for business intelligence analysis.

---

## Tableau Workbook Description

The Tableau packaged workbook (`executive_dashboard.twbx`) presents an interactive executive dashboard designed for senior management.

The dashboard enables users to explore business performance across multiple dimensions through linked visualisations, KPI summary cards, interactive filters, and dashboard actions.

---

## Calculated Fields Created

| Calculated Field | Purpose |
|------------------|---------|
| Profit Margin | Calculates profit as a percentage of total sales. |
| Cost | Estimates total cost by subtracting profit from sales. |
| Average Order Value | Calculates the average sales value per unique order. |
| Return Rate | Measures returned orders as a proportion of total orders. |
| Shipping Delay Bucket | Groups delivery performance into Fast, Normal, and Delayed categories. |

---

## Dashboard Components

The executive dashboard contains the following analytical views:

- Monthly Sales Trend
- Regional Performance
- Category Profitability
- Customer Segment Performance
- Shipping Performance
- Discount vs Profit Analysis
- Return Analysis

Additionally, the dashboard includes executive KPI cards displaying:

- Total Sales
- Total Profit
- Profit Margin

---

## Filters and Dashboard Interactions

The dashboard provides interactive filtering through:

- Region
- Category
- Customer Segment

A dashboard filter action has also been implemented, allowing users to select values within one visualisation and automatically update the remaining charts. This enables efficient exploratory analysis and improves executive decision-making.

---

## Key Business Insights

The dashboard highlights several important business findings:

- Sales performance varies across regions.
- Profitability differs considerably between product categories.
- Customer segments contribute differently to revenue generation.
- Higher discount levels may reduce profitability.
- Shipping performance varies by shipping mode.
- Product returns are concentrated within specific categories.
- Sales trends reveal seasonal fluctuations.
- Interactive filtering enables detailed regional and customer-level analysis.

---

## Dashboard Story Summary

The dashboard provides a complete overview of retail business performance by integrating sales, profitability, customer behaviour, shipping efficiency, and return patterns into a single executive interface.

The visualisations support leadership in identifying high-performing business areas, recognising operational risks, and prioritising improvement opportunities through evidence-based decision-making.

---

## Assumptions and Limitations

### Assumptions

- Dataset values are accurate and complete.
- Sales and profit figures are correctly recorded.
- Return indicators accurately represent returned orders.
- Delivery days correctly reflect shipping performance.

### Limitations

- Dashboard findings identify associations rather than causal relationships.
- External business factors such as competitor activity, economic conditions, and marketing campaigns are not included.
- The dashboard represents historical performance and should be complemented with future forecasting for strategic planning.

---

## Screenshots Included

The repository includes the following evidence:

- `full_dashboard.png`
- `sales_trend_view.png`
- `regional_performance_view.png`
- `category_profitability_view.png`
- `filter_interaction_view.png`

---

## Repository Structure

```text
part4_tableau_dashboard/
├── data/
│   └── dashboard_sales_data.xlsx
├── tableau/
│   └── executive_dashboard.twbx
├── outputs/
│   ├── dashboard_story.md
│   ├── business_insights.md
│   └── chart_selection_justification.md
├── screenshots/
│   ├── full_dashboard.png
│   ├── sales_trend_view.png
│   ├── regional_performance_view.png
│   ├── category_profitability_view.png
│   └── filter_interaction_view.png
└── README.md
```