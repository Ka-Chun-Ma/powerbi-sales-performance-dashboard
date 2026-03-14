# Sales Performance Dashboard (Power BI)

### What this project demonstrates

- **End-to-end Power BI:** data modeling on a multi-table schema (AdventureWorks), DAX measures for KPIs and trends, and report design with clear layout and interactivity.
- **Executive and operational use:** KPI cards, trend charts, regional map, product/customer drill-down, and what-if style price analysis—built for both at-a-glance and exploratory use.
- **Portfolio context:** Guided (curriculum-based) project; requirements and structure were given; implementation, DAX, and formatting were done independently.

---

## Overview

This dashboard gives a single view of sales performance with drill-down and what-if analysis. It shows competency in data modeling and relationships, DAX (KPIs, trends, calculated logic), report design and hierarchy, and visualization (maps, cards, charts, cross-filtering). The report was built as part of guided learning using the standard AdventureWorks dataset.

---

## Dashboard Contents

| Page | Purpose |
|------|---------|
| **Executive Dashboard** | High-level KPIs (revenue, profit, orders), trend analysis, and summary visuals |
| **Regional Map** | Geographic view of sales performance by region |
| **Product Detail** | Product-level analysis with drill-down and category hierarchy |
| **Customer Detail** | Customer segmentation and detail analysis |

**Features:**

- **KPI cards** for revenue, profit, and order count
- **Trend analysis** over time (e.g., line or area charts)
- **Product and customer drill-down** (hierarchies and filters)
- **What-if style analysis** for price adjustment impact (parameter/slider-driven)

---

## Repository Structure

```
powerbi-sales-performance-dashboard/
├── README.md                 # This file
├── AdventureWorks Report.pbix # Power BI report (requires Power BI Desktop to open)
├── docs/
│   ├── case-study.md         # Short case study and design notes
│   ├── screenshot-captions.md # Suggested captions for screenshots
│   └── recruiter-summary.md  # One-paragraph summary for recruiters
└── screenshots/              # Dashboard screenshots for portfolio/README
    ├── Page 1 - Exec Dashboard.png
    ├── Page 2 - Map.png
    ├── Page 3 - Product Detail.png
    └── Page 4 - Customer Detail.png
```

---

## How to Use

1. **View the report:** Open `AdventureWorks Report.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows). The report uses the built-in AdventureWorks sample data; no separate data source setup is required if using the standard sample.
2. **Screenshots:** See `screenshots/` for page-by-page views. Suggested captions are in `docs/screenshot-captions.md`.
3. **Case study & summary:** See `docs/case-study.md` for context and `docs/recruiter-summary.md` for a concise recruiter-facing summary.

---

## Tools & Data

- **Tool:** Microsoft Power BI Desktop  
- **Data:** AdventureWorks sample dataset (standard Microsoft sample)  
- **Concepts used:** Data model relationships, DAX measures, parameters (what-if), drill-down, filters, and basic report layout/theming  

---

## License & Attribution

- **AdventureWorks** sample database and data are from Microsoft (sample/tutorial use).
- This report is shared as a portfolio piece. Feel free to open and explore the `.pbix`; reuse of design or DAX is at your own discretion with appropriate attribution.

---

*Suitable for Data Analyst portfolios. For a short case study and recruiter summary, see the `docs/` folder.*
