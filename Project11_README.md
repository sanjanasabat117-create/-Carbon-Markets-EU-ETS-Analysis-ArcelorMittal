# Carbon Markets & EU ETS Analysis — ArcelorMittal

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-10_Sheets-217346?logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Carbon%20Markets-green)
![Data](https://img.shields.io/badge/Data-Real%20%7C%20Official%20Sources-brightgreen)
![Status](https://img.shields.io/badge/Status-Complete-success)

## Overview

This project analyses ArcelorMittal's position within the **EU Emissions Trading System (EU ETS)** using real data from the company's official Sustainability Report 2025 and live EU Allowance (EUA) price data. The analysis covers carbon compliance exposure, cost scenarios, and decarbonisation ROI — skills directly applicable to ESG reporting, carbon advisory, and sustainability consulting roles.

> **All data is sourced from publicly available official reports.**
> ArcelorMittal Sustainability Report 2025 + EUA price data from Investing.com

---

## Business Problem

Steel manufacturing is one of the most emissions-intensive industries globally. ArcelorMittal, as one of the world's largest steel producers and a major EU ETS participant, faces a material financial exposure from carbon allowance prices. This project answers three key questions:

1. What is ArcelorMittal's current ETS compliance position?
2. What is the carbon cost exposure under different EUA price scenarios?
3. What is the financial return on investing in decarbonisation technologies?

---

## Project Structure

```
Carbon-Markets-EU-ETS-Analysis-ArcelorMittal/
│
├── data/
│   └── Carbon_Markets_EU_ETS_ArcelorMittal_Data.xlsx   # 10-sheet workbook (real data)
│
├── charts/
│   ├── chart1_eua_price_trend.png                       # EUA price history & forecast
│   ├── chart2_am_emissions.png                          # ArcelorMittal emissions trend
│   ├── chart3_compliance_cost.png                       # Compliance cost by scenario
│   ├── chart4_eaf_bf_breakeven.png                      # EAF vs BF-BOF breakeven analysis
│   ├── chart5_decarbonisation_roadmap.png               # Technology roadmap
│   ├── chart6_risk_opportunity.png                      # Risk-opportunity matrix
│   └── chart7_recent_eua_prices.png                     # Recent EUA spot prices
│
├── notebooks/
│   └── carbon_markets_analysis.py                       # Full Python analysis script
│
└── README.md
```

---

## Key Findings

| Metric | Value | Source |
|--------|-------|--------|
| ArcelorMittal Total GHG (2024) | ~170 MtCO₂e | AM SR 2025 |
| EU Operations Scope 1 (est.) | ~55–65 MtCO₂e | AM SR 2025 |
| EUA Price (2024 avg) | ~€62–65/tonne | Investing.com |
| Carbon Cost @ €65/t (EU ops) | ~€3.5–4.2 Billion | Calculated |
| EAF vs BF-BOF Breakeven EUA | ~€85–95/tonne | Analysis |
| Free Allocation (Phase 4) | Declining annually | EU ETS rules |
| Net Zero Target | 2050 (1.5°C pathway) | AM SR 2025 |

---

## Excel Workbook — 10 Sheets

| Sheet | Contents |
|-------|----------|
| 1. Company Overview | ArcelorMittal profile, operations, EU footprint |
| 2. EUA Price Data | Historical EUA prices (2018–2024), trend analysis |
| 3. Emissions Data | Scope 1, 2, 3 emissions (real data, FY2021–2024) |
| 4. Allowance Position | Free allocation vs verified emissions gap |
| 5. Cost Scenarios | Carbon cost at €50 / €75 / €100 / €150 per tonne |
| 6. Technology Roadmap | BF-BOF to EAF/DRI-EAF transition timeline |
| 7. EAF Breakeven Analysis | Price point at which green steel becomes viable |
| 8. MACC Curve | Marginal Abatement Cost Curve by lever |
| 9. Risk & Opportunity | Financial risk matrix under TCFD framework |
| 10. Summary Dashboard | Key metrics and visual summary |

---

## Charts Preview

### EUA Price Trend & Carbon Cost Exposure
Tracks EU Allowance price movements from 2018 to 2024 and models forward scenarios at €50, €75, €100, and €150/tonne — showing how ArcelorMittal's compliance cost changes under each scenario.

### EAF vs BF-BOF Breakeven
Identifies the carbon price at which Electric Arc Furnace (EAF) technology becomes financially preferable to traditional Blast Furnace-Basic Oxygen Furnace (BF-BOF) operations — a critical decision metric for steel decarbonisation capex.

### Marginal Abatement Cost Curve
Ranks decarbonisation levers (energy efficiency, fuel switching, green hydrogen DRI, CCS) by cost per tonne abated, informing capital allocation priorities.

---

## Technical Skills Demonstrated

- **Carbon Accounting** — EU ETS mechanics, free allocation, verified emissions, compliance gaps
- **Financial Modelling** — Scenario analysis, breakeven modelling, NPV of decarbonisation investments
- **Data Analysis** — Python (Pandas, Matplotlib, Seaborn), Excel (advanced formulas, scenario tables)
- **ESG Frameworks** — TCFD climate risk, GHG Protocol, SBTi 1.5°C pathway alignment
- **Industry Knowledge** — Steel sector decarbonisation, BF-BOF vs EAF/DRI-EAF transition economics

---

## Data Sources

| Source | Data Used |
|--------|-----------|
| [ArcelorMittal Sustainability Report 2025](https://corporate.arcelormittal.com/sustainability) | GHG emissions, Net Zero targets, decarbonisation investments |
| [Investing.com — EUA Carbon Price](https://www.investing.com/commodities/carbon-emissions) | Historical EU Allowance spot prices (2018–2024) |
| EU ETS Phase 4 Rules (2021–2030) | Free allocation benchmarks, cap trajectory |
| GHG Protocol Corporate Standard | Scope 1/2/3 accounting methodology |

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/sanjanasabat117-create/-Carbon-Markets-EU-ETS-Analysis-ArcelorMittal.git
cd -Carbon-Markets-EU-ETS-Analysis-ArcelorMittal

# Install dependencies
pip install pandas openpyxl matplotlib seaborn numpy

# Run analysis
python notebooks/carbon_markets_analysis.py
```

---

## Relevance to ESG Roles

This project is directly relevant to:
- **Carbon Advisory / Net Zero Consulting** — scenario modelling, MACC curves, transition risk
- **ESG Reporting Specialist** — GHG protocol application, TCFD risk disclosure
- **Sustainability Analyst** — real company data analysis, EU regulatory compliance
- **Climate Risk Analyst** — physical and transition risk quantification under TCFD

---

## Author

**Sanjana Sabat**
ESG & Sustainability Analyst | Bengaluru, India
📧 sanjanasbat117@gmail.com

---

*This project uses publicly available data from official sustainability reports and market data providers. All analysis and interpretations are the author's own.*
