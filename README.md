# GEOG5415M-final-project-201958463
# GEOG5415M Final Project — Housing affordability inequality (England, 2008–2024)

This repository contains my final project for **GEOG5415M**.

## Research question
1) How does housing affordability (price-to-earnings) vary across **IMD 2019 deprivation quintiles** over **2008–2024** in England?
2) What is the **spatial pattern** of affordability across England **LADs in 2024**?

## Data (open sources)
- UK House Price Index (UK HPI): October average prices (P_oct)
- ASHE: median annual gross earnings (residence-based, full-time)
- IMD 2019: deprivation quintile grouping (England)
- ONS LAD boundaries (May 2024, UK BFC): used for the 2024 map

> Note: Full input datasets are included in the submitted coursework ZIP as required.

## Methods (brief)
- Construct affordability indicator: **price-to-earnings = P_oct / median annual earnings**
- Summarise by IMD quintile using the **median** each year (2008–2024)
- Map LAD affordability in **2024** (values capped at the 95th percentile for readability)

## Outputs
- `fig_nonspatial_trend_imd_quintiles_2008_2024.png` — affordability trends by deprivation quintile
- `fig_spatial_price_to_earnings_2024.png` — 2024 LAD affordability map (England)

## Reproducibility
Run the notebook top-to-bottom in **Google Colab**:
1. Open the `.ipynb`
2. Ensure the input files are placed under `data/raw/` (including the LAD boundary GeoJSON)
3. Run all cells to reproduce figures in `outputs/figures/`

## Author / ID
Student ID: **201958463**
