# Massachusetts Migration Analysis Dashboard

Interactive visualization of Massachusetts migration patterns using the latest Census Bureau Vintage 2025 data (released January 27, 2026).

## 🔗 Live Demo

**[View the Interactive Dashboard](https://yourusername.github.io/ma-migration-analysis/)**

## 📊 Key Findings

### Cumulative Totals (2020-2025)
| Metric | Value |
|--------|-------|
| Residents LEFT for other states | **-137,702** |
| Immigrants ARRIVED | **+296,081** |
| Net Migration | **+158,379** |
| Emergency Shelter Spending | **$1.83 Billion** |

### The Massachusetts Paradox
- **Without immigration, MA would have LOST ~112,000 people since 2020**
- Immigration covered the resident exodus **twice over**
- But now both trends are reversing:
  - Immigration ↓37% (90K → 57K in 2024-25)
  - Exodus ↑74% (19K → 33K in 2024-25)
  - Census projects another 75% immigration drop by July 2026

### Congressional Seat at Risk
If Massachusetts population drops below ~6.79M by 2030, it loses its 9th Congressional seat.

| Scenario | 2030 Population | Loses Seat? |
|----------|-----------------|-------------|
| Current Trend | 7.15M | No |
| **LIKELY** | **7.03M** | **Close** |
| Pessimistic | 6.87M | **YES** |
| Worst Case | 6.70M | **YES** |

## 📈 Dashboard Features

The interactive dashboard includes 5 tabs:

1. **📊 Overview** - Key metrics, migration bar chart, summary
2. **📅 Annual Data** - Year-by-year migration table and chart
3. **📈 Cumulative** - Running totals since 2020
4. **🔮 2030 Projection** - Population scenarios with seat loss threshold
5. **❓ Why Leave** - BU Study findings on outmigration drivers

## 🗂️ Data Sources

- **U.S. Census Bureau Vintage 2025** (Released Jan 27, 2026)
  - [Press Release](https://www.census.gov/newsroom/press-releases/2026/population-growth-slows.html)
  - [Methodology Blog](https://www.census.gov/newsroom/blogs/random-samplings/2026/01/historic-decline-in-net-international-migration.html)
- **IRS Statistics of Income (SOI) Migration Data**
- **Boston University Finance Study (2024)** - Outmigration drivers
- **Tax Foundation** - State tax competitiveness rankings
- **Center for Immigration Studies** - Massachusetts welfare cost analysis

## 🛠️ Technical Details

This is a standalone HTML file using:
- React 18.2
- Recharts 2.10
- Tailwind CSS
- Babel (for JSX transformation)

No build process required - just open `index.html` in a browser.

## 📁 Files

```
ma-migration-analysis/
├── index.html          # Main dashboard (standalone)
├── README.md           # This file
└── data/
    └── migration_data.json  # Raw data (optional)
```

## 🚀 Deployment

### GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set Source to "main" branch
4. Your dashboard will be live at `https://yourusername.github.io/ma-migration-analysis/`

### Local

Just open `index.html` in any modern browser.

## 📋 Raw Data

### Annual Migration (Fiscal Years)

| Period | Domestic | International | Net |
|--------|----------|---------------|-----|
| 2020-21 | -1,762 | +1,762 | 0 |
| 2021-22 | -48,000 | +72,892 | +24,892 |
| 2022-23 | -35,400 | +74,610 | +39,210 |
| 2023-24 | -19,200 | +90,217 | +71,017 |
| 2024-25 | -33,340 | +56,600 | +23,260 |
| **TOTAL** | **-137,702** | **+296,081** | **+158,379** |

### Why Residents Leave (BU Study 2024)

1. **Taxes** (100) - MA ranks 43rd in tax competitiveness
2. **Housing Costs** (95)
3. **Healthcare Expenses** (85)
4. **Traffic** (70)

Plus economist Klepper-Smith's "Four T's": Taxes, Temperature, Traffic, and Targeting (of blue states for federal spending cuts).

## ⚠️ Caveats

- Census methodology includes estimates and revisions
- 2023-24 outmigration was revised DOWN 32% in Vintage 2025
- State-level data is distributed by formula from national totals
- Projections are scenarios, not predictions

## 📄 License

MIT License - Feel free to use, modify, and share.

## 🙏 Acknowledgments

Data compiled from public sources. Analysis inspired by Boston Globe reporting on MA outmigration trends.

---

*Last updated: January 31, 2026*
