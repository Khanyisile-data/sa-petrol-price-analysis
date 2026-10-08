# Petrol Price in South Africa: A 20-Year Breakdown (2006–2026)

An analysis of what actually goes into the price of a litre of petrol in South Africa — where every cent comes from, how it's changed over two decades, and what's driven the growth.

## Key Findings

- The petrol price rose from **R5.49** (Jan 2006) to **R25.58** (Aug 2026) per litre
- **51.7%** of that increase came from the Basic Fuel Price (crude oil + exchange rate + freight)
- **27.5%** came from government taxes and levies (fuel tax + RAF + slate levy)
- **13.5%** came from the retail margin
- The 2008 oil spike and 2020 COVID crash are both visible in the long-term trend

## Charts

1. **Pump price over time (2006–2026)** — the full 20-year trend
2. **Component decomposition** — every cent broken down into its 13 components
3. **BFP vs. government levies** — how the two biggest slices have grown
4. **Government's cut** — fuel tax, RAF levy, and slate levy stacked over time

## Methodology

The pump price was decomposed into 13 components sourced from [DataDesk (DS0150)](https://datadesk.co.za). I validated the sum of components against the reported pump price: mean discrepancy of **+8.37 cents/litre** (max 27 cents, December 2017). The remaining gap is likely an unpublished levy or rounding in the source data.

## Data Source

- **DataDesk DS0150** — Petrol price in South Africa since 2006
- 249 monthly records, Jan 2006 – Sep 2026 (Sep 2026 excluded due to incomplete breakdown)

## How to Reproduce

1. Open the notebook in Google Colab: `sa-petrol-price-analysis.ipynb`
2. Upload `petrol-price.csv` when prompted
3. Run all cells

**Requirements:** `pandas`, `matplotlib`

## Author

[Khanyisile](https://github.com/Khanyisile-data) — Data analysis portfolio project
