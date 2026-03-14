# Case Study: Sales Performance Dashboard

## Objective

Build an interactive Power BI report on the AdventureWorks sample dataset that supports both executive-level oversight and operational drill-down, including simple what-if analysis for pricing.

## Approach

- **Data:** Used the standard AdventureWorks schema (sales, products, customers, geography, dates) with appropriate relationships and a single report.
- **Audience:** Designed for two use cases—(1) executives viewing KPIs and trends at a glance, and (2) analysts exploring products, customers, and regions with filters and hierarchies.
- **Guided scope:** Requirements and page structure were provided as part of a curriculum; implementation (DAX, layout, formatting, parameters) was done independently.

## Design Choices

| Area | Choice | Rationale |
|------|--------|-----------|
| **Structure** | Four pages: Executive, Map, Product Detail, Customer Detail | Separates “at a glance” view from detail analysis without overcrowding one canvas. |
| **KPIs** | Revenue, profit, order count as cards | Quick comparison and alignment with common business metrics. |
| **Geography** | Dedicated map page | Makes regional performance easy to see and compare. |
| **Drill-down** | Product and customer hierarchies | Supports “from summary to detail” exploration without multiple reports. |
| **What-if** | Price adjustment parameter | Demonstrates parameter-driven analysis for scenario-style questions. |

## Skills Demonstrated

- **Data modeling:** Working with star/snowflake-style schema and relationships in Power BI.
- **DAX:** Measures for KPIs, time intelligence, and parameter-driven calculations.
- **Report design:** Page layout, visual hierarchy, and consistent formatting.
- **Interactivity:** Filters, drill-down, cross-filtering, and what-if parameters.

## Outcome

A single `.pbix` report that opens in Power BI Desktop with no extra setup (using built-in sample data). The report is suitable as a portfolio sample of Power BI report development and DAX use in a guided, curriculum-based context.

## Possible Extensions

- Connect to a live or refreshed data source (e.g., SQL Server AdventureWorks).
- Add more what-if levers (e.g., volume, discount).
- Publish to Power BI Service and add row-level security or scheduled refresh for a fuller end-to-end story.
