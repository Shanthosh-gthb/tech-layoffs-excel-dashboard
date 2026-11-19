# Tech Layoffs Dashboard (Excel)

An Excel dashboard analysing global company layoffs from **March 2020 to July 2025**, built with PivotTables, PivotCharts and slicers.

## Dataset
| Metric | Value |
|---|---|
| Total layoff events | 2,673 |
| Companies affected | 1,902 |
| Countries | 54 |
| Total employees laid off | 752,040 |
| Average per event | ~281 |
| Largest single event | 22,000 |

**Columns:** Event ID, Company, HQ City, Country, Industry, Funding Stage, Laid-off count, Layoff Date, Year, Month, Week of year, Quarter.

## Workbook Structure
| Sheet | Purpose |
|---|---|
| `Layoffs` | Source data (2,673 rows) |
| `KPI's and Slicers` | KPI cards and slicer controls |
| `Charts` | PivotTables feeding each chart |
| `Report` | Final dashboard layout |

## Charts
- Yearly Layoff Trends
- Monthly Layoff Trends
- Layoffs by Industry
- Top 10 Companies by Layoffs
- Geographical Distribution of Layoffs
- Layoffs by Funding Stage
- Top 10 Industries by Layoff Frequency
- Industry-wise Layoff Trends by Year

## Quick Findings
- **2023** was the peak year with 264,220 layoffs, followed by 2022 (165,269) and 2024 (152,922).
- Largest layoffs by company: Intel (38,115), Microsoft (30,013), Amazon (27,940), Meta (24,700), Tesla (14,500).
- The United States accounts for 1,687 of the 2,673 events, followed by India (235) and Canada (118).

## Tech Stack
- Microsoft Excel: PivotTables, PivotCharts, Slicers, data cleaning

## Repository Structure
```
tech-layoffs-excel-dashboard/
├── dashboard/
│   └── Tech_Layoffs_Dashboard.xlsx
├── data/
│   └── layoffs_raw.csv          # CSV export of the Layoffs sheet
├── screenshots/                 # add dashboard screenshots here
├── .gitattributes
├── .gitignore
└── README.md
```

## How to Use
1. Download `dashboard/Tech_Layoffs_Dashboard.xlsx`.
2. Open it in Microsoft Excel (slicers need desktop Excel 2013+).
3. Go to the `Report` sheet and use the slicers to filter.

## Screenshots
Add a screenshot of the `Report` sheet to `screenshots/dashboard.png`, then uncomment:

<!-- ![Dashboard](screenshots/dashboard.png) -->

## Author
**Shanthosh Adhitya T** - Coimbatore, India
