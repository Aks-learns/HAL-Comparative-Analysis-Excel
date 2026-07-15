# HAL Comparative Financial Analysis

A financial and strategic benchmarking of **Hindustan Aeronautics Limited (HAL)**
against **Dassault Aviation** and **Lockheed Martin**, built entirely from
publicly disclosed filings. Produced as a self-directed project during an
internship with HAL's LCA Tejas Division (2026).

> **Note:** This project uses **public-domain data only** (annual reports, SEC /
> Euronext / BSE–NSE filings, investor disclosures). It contains no internal,
> proprietary, or confidential HAL information. It is an academic analysis and
> **not investment advice**.

## Overview

The three companies report in three currencies (INR, EUR, USD) and under three
accounting frameworks (Ind AS, IFRS, US GAAP), so the comparison is deliberately
**ratio-led** across a five-year window (HAL FY2022–FY2026; peers 2021–2025).

**Key findings**
- HAL leads on net margin (~27.5%) with a near debt-free, net-cash balance sheet.
- Its main weakness is working-capital intensity (inventory ~780 days;
  cash-conversion cycle 700+ days).
- Dassault's reported margin roughly halves once Thales equity income is stripped out.
- Lockheed's high ROE is largely a leverage/buyback effect, not operational strength.

## Contents

| File | Description |
|------|-------------|
| `HAL_Comparative_Financial_Analysis.docx` / `.pdf` | 30-page benchmarking report |
| `HAL_Financial_Analysis_Workbook.xlsx` | Interactive financial model (see below) |
| `/charts` | Figures used in the report |
| `README.md` | This file |

## The Excel model

A multi-sheet model with:
- Source data for all three companies (blue = editable inputs)
- Ratio, common-size, and DuPont sheets (live formulas)
- Driver-based **5-year forecast** of HAL
- **DCF valuation** with a sensitivity heatmap
- **Relative-valuation comps** (EV/EBITDA, P/E, EV/Sales)
- **Bull / Base / Bear** scenario switching
- A working-capital scenario tool

## Methodology

Ratio and trend analysis, common-size statements, DuPont decomposition, an
ex-Thales adjustment for Dassault, and a benchmarking scorecard. FX is used only
for indicative scale context; all comparisons are currency-neutral.

## Tools

Excel (financial modelling, DCF, scenario analysis) · Python (matplotlib) ·
Power BI · data from public filings.

## Author

**Akshat Kumar Shaw** — BBA (Finance & Economics), CHRIST (Deemed to be University), Bengaluru
📧 akshatshaw6@gmail.com

## Disclaimer

Based solely on publicly available information. Not investment advice. All
trademarks belong to their respective owners.
