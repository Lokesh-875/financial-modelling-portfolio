# Asian Paints Ltd — Financial Modelling & Valuation

**NSE/BSE: ASIANPAINT | BSE Code: 500820 | Sector: Paints & Home Décor**

## Overview
Asian Paints Ltd is an Indian multinational paint company engaged in manufacturing, selling, and distribution of paints, coatings, and home décor products. This project builds a full 3-statement financial model and DCF valuation to estimate intrinsic value and compare it against the market price.

*(Insert screenshot: One Page Profile / Teaser sheet)*

## Key Historical Metrics (FY22–FY26)

| Metric | FY22 | FY23 | FY24 | FY25 | FY26 |
|---|---|---|---|---|---|
| Total Sales (₹ Cr) | 29,101 | 34,489 | 35,495 | 33,906 | 35,584 |
| Sales Growth (YoY) | 34.0% | 18.5% | 2.9% | -4.5% | 4.9% |
| Gross Margin | 29.2% | 31.1% | 35.2% | 32.9% | 33.9% |
| EBITDA Margin | 16.5% | 18.2% | 21.4% | 17.7% | 18.8% |
| EPS (₹) | 32.16 | 43.74 | 57.94 | 38.68 | 45.82 |

**Observation:** Revenue growth has slowed and become volatile post-FY23 (even declining in FY25), while margins have also compressed from their FY24 peak — a trend worth flagging to management/investors as input pricing or competitive pressure.

## Valuation (DCF — FCFF Method)

*(Insert screenshot: DCF sheet)*

| Assumption | Value |
|---|---|
| WACC | 12.24% |
| Terminal Growth Rate | 5.0% |
| Expected Growth (forecast period) | 10.0% |

| Output | Value |
|---|---|
| PV of FCFF (explicit period) | ₹14,492 Cr |
| PV of Terminal Value | ₹30,457 Cr |
| Value of Operating Assets | ₹44,950 Cr |
| **Equity Value per Share** | **₹438.85** |
| Current Market Price | ₹2,645.20 |

**Finding:** The DCF-implied intrinsic value is roughly 5x below the current market price. This is a classic case where a plain FCFF model likely understates value for a quality compounder with strong brand equity and distribution moat — assumptions like a 5% terminal growth rate don't fully capture that. Cross-checked against comparable company multiples (EV/EBITDA, P/E) in the Comps Valuation and Football Field sheets to sanity-check this gap.

## What this project demonstrates
- Building fully-linked 3-statement models from scratch
- CAPM/beta regression for cost of equity, WACC construction
- DCF mechanics: mid-year convention, terminal value sensitivity tables
- Critical evaluation of model outputs rather than taking DCF at face value

## Files
- `Asian_Paints_Project.xlsx` — full model (19 sheets: historicals, ratios, forecasts, WACC, DCF, comps, football field, VaR, DuPont, Altman's Z-Score)

*(Replace the bracketed screenshot notes above with actual PNG exports of your One Page Profile and DCF sheets before publishing)*
