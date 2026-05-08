# TTC Bus Delay Analysis Dashboard

An end-to-end data analytics project analyzing **69,000+ TTC bus delay records** across 100+ routes using Python and Power BI.

---

## Project Overview

This project analyzes Toronto Transit Commission (TTC) bus delay data to identify operational risk indicators, recurring incident clusters, and performance inefficiencies across the network. The findings are presented through an interactive 3-page Power BI dashboard designed to support performance monitoring and data-driven decision-making.

---

## Key Findings

- **69,037** delay incidents analyzed across **100+ routes**
- **977 outliers flagged** (1.4% of records) during data validation — predominantly coded **MFDV**
- **Kennedy Station** recorded the highest incident count with **2,158 delays**
- **Peak delay hours**: 3PM – 5PM (afternoon rush)
- **Route 102 Markham Road** had the highest average delay duration
- **29 Dufferin** recorded the highest total delay volume across the network
- Average delay per incident: **20.72 minutes**
- Total network delay: **1,000,000+ minutes**

---

## Dashboard Pages

### Page 1 — Route Performance & Operational Risk
- Top 10 Routes by Average Delay
- High Risk Routes: Avg Delay vs Incident Frequency (scatter plot)
- Total Delay & Incidents by Route
- Interactive route slicer

### Page 2 — Data Validation & Outlier Detection
- KPI cards: Total Records, Outliers Flagged, Clean Records
- Flagged Outlier Records table (sorted by worst delays)

### Page 3 — Network-Wide KPIs & Patterns
- KPI cards: Total Incidents, Avg Delay per Incident, Total Delay Minutes
- Delay Frequency by Hour of Day (line chart)
- Top 10 Stations by Incident Count
- Interactive date range slicer

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas) | Data cleaning, outlier detection, aggregation |
| Power BI (Web) | Interactive dashboard development |
| GitHub | Version control and portfolio hosting |

---

## Files

| File | Description |
|------|-------------|
| `TTC_Analytics.pbix` | Power BI dashboard file |
| `TTC_Bus_Delay_Cleaned.csv` | Cleaned dataset with outlier flags (69,037 records) |
| `route_summary.csv` | Pre-aggregated delay metrics by route |
| `station_summary.csv` | Pre-aggregated delay metrics by station |
| `hour_summary.csv` | Pre-aggregated delay metrics by hour |

---

## Data Source

TTC bus delay data sourced from the [City of Toronto Open Data Portal](https://open.toronto.ca/).

---

## Author

**Shubhra** — [GitHub Profile](https://github.com/Shubhra-08)
