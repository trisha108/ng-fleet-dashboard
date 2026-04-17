# National Grid EV Fleet Transition Dashboard

## Overview
This dashboard was built as part of interview preparation for the Associate Analyst, Systems and Reporting role on National Grid's Graduate Development Program. It demonstrates the kind of data analysis, KPI reporting, and systems thinking the role involves — specifically around National Grid's publicly stated commitment to 100% electric fleet by 2030.

## What It Shows
The dashboard has five tabs covering:
- Fleet electrification progress against National Grid's 2026 and 2030 targets
- Charging infrastructure gap analysis across 8 US depot locations in New York and Massachusetts
- EV charging efficiency KPIs and off-peak compliance by depot
- A priority list of vehicles recommended for EV swap based on age, mileage, and maintenance risk

## Data Sources
The fleet data (500 vehicles across 8 depots) is synthetic, modelled on publicly available utility fleet compositions and anchored to real confirmed figures:
- **175 EVs** currently in National Grid's US fleet *(National Grid, October 2024)*
- **12.8 year** average US fleet age *(Expert Market, 2025)*
- **$0.08/kWh off-peak, $0.18/kWh peak** — real New York utility electricity rates
- **404g CO₂/mile** — real EPA average for ICE vehicles

All targets referenced (60% electrification by 2025/26, 100% light-duty EV by 2030) are drawn directly from National Grid's own published reporting.

## Built With
- Python (pandas, numpy) — data pipeline
- Chart.js — interactive charts
- HTML / CSS — dashboard interface

## Author
Trisha — GDP Candidate, Associate Analyst Systems and Reporting, National Grid
