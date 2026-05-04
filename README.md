# 🪨 Coal Resource Intelligence System (CRIS)

> A Power BI dashboard analyzing coal reserves, supply, and consumption patterns across Indian states using official NDAP datasets.

---

## 🔗 Live Dashboard

| Dashboard | Link |
|-----------|------|
| 📊 Reserves & Sustainability | [Open in Power BI ↗](https://app.powerbi.com/groups/me/reports/929cf054-7ca0-4eff-883f-c18b2e4d567e/c3444fd79967033038c9?experience=power-bi) |
| ⚡ Power BI Insights | [Open in Power BI ↗](https://app.powerbi.com/groups/me/insights/7cb3825d-c8df-429b-8ce5-9532d795ca57?insightsSource=Desktop&experience=power-bi) |

---

## 👤 Team Member

| Roll No | Name |
|---------|------|
| 161 | Tanu Sharma |

---

## 📁 Project Structure

```
CRIS-Dashboard/
├── 📊 CRIS_Dashboard.pbix          # Power BI Dashboard file
├── 📄 README.md                     # This file
├── 🌐 index.html                    # Beautiful project webpage
└── 📂 datasets/
    ├── Coal_Consumption.csv                    # 2988 rows · 2006-2020
    ├── Coal_Supply_Production_by_State.csv     # 830 rows  · 2006-2020
    └── Coal_Reserves_Production_by_State.csv   # 5417 rows · 2021
```

---

## 📊 Datasets

All datasets sourced from **NDAP — National Data and Analytics Platform, Ministry of Coal, Government of India**

| Dataset | Rows | Years | Description |
|---------|------|-------|-------------|
| Coal Consumption | 2,988 | 2006–2020 | State-wise sector consumption |
| Coal Supply Production | 830 | 2006–2020 | Company-wise supply by state |
| Coal Reserves Production | 5,417 | 2021 | Coal field reserves by depth |

---

## 📋 Dashboard Pages

### Page 1 — Executive Summary
- 4 KPI Cards (Consumption, Supply, Ratio, Depletion Index)
- Line chart — Consumption trend 2006–2020
- Map visual — India states with bubble size
- Year range slicer

### Page 2 — Consumption Analysis
- Stacked bar chart — State vs Sector breakdown
- Clustered bar — Top consuming states
- Donut chart — Sector share
- Coal type slicer (RAW / WASHED / LIGNITE)

### Page 3 — Supply Analysis
- Clustered bar — CIL / PRIVATE / OTHER PUBLIC by state
- Table — 60 companies with Yield %
- Pie chart — COOKING vs NON-COOKING vs LIGNITE
- Line chart — Supply trend by year

### Page 4 — Reserves & Sustainability
- Stacked bar — 129 coal fields by reserve type
- Gauge — Depletion Index (0–100%)
- Bar chart — Reserves by depth (0-300, 300-600, 600-1200)
- Treemap — State → Coal Field → Quantity

---

## 📐 KPI Measures (DAX)

```dax
Total_Consumption_MT = SUM(Coal_Consumption[Coal_Consumed_MT])

Total_Supplied_MT = SUM(Coal_Supply[Coal_Supplied_MT])

Supply_Ratio = DIVIDE([Total_Supplied_MT], [Total_Consumption_MT], 0)

Depletion_Index = 
    DIVIDE(
        CALCULATE(SUM(Coal_Reserves[Coal_Reserved_MT]), Coal_Reserves[Reserve_Type] = "Proved"),
        SUM(Coal_Reserves[Coal_Reserved_MT]), 0
    ) * 100

Company_Yield_Pct = 
    DIVIDE(
        SUM(Coal_Supply[Coal_Supplied_MT]),
        CALCULATE(SUM(Coal_Supply[Coal_Supplied_MT]), ALLEXCEPT(Coal_Supply, Coal_Supply[State])),
        0
    ) * 100

Avg_Depth_Factor = 
    DIVIDE(
        SUMX(Coal_Reserves, Coal_Reserves[Depth_Midpoint] * Coal_Reserves[Coal_Reserved_MT]),
        SUM(Coal_Reserves[Coal_Reserved_MT]), 0
    )

Total_Reserves_MT = SUM(Coal_Reserves[Coal_Reserved_MT])
```

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 🏛️ Data Source

**NDAP — National Data and Analytics Platform**
Ministry of Coal, Government of India
🔗 [https://ndap.gov.in](https://ndap.gov.in)

---

## 📌 Subject

**DABI — Data Analytics and Business Intelligence**
Practical No. 10

---

*© 2026 · CRIS Dashboard · DABI Practical 10*
