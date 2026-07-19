# Target Corporation 3-Statement Model & DCF Valuation

A fully linked three-statement financial model and DCF valuation for Target Corporation
(NYSE: TGT), covering FY2021A–FY2025A actuals and FY2026E–FY2030E projections. Includes
a WACC build, Gordon-growth DCF with an exit-multiple cross-check, a formula-driven
sensitivity grid, and a trading-comps comparison.

## Files

- `model/TGT_3_Statement_DCF_Model.xlsx` — the model, 9 tabs
- `model/TGT_Investment_Thesis_Memo.docx` — one-page investment thesis memo
- `data/TGT_historical_financials.xlsx` — source data pulled and verified from Target's
  10-K filings, used to build the model's historical actuals

## Data sources

- Target Corporation Forms 10-K for FY2021–FY2025, SEC EDGAR (CIK 0000027419)
- FY2023 balance sheet: Target's 2023 Form 10-K, filed March 13, 2024, Consolidated
  Statements of Financial Position
- Market and WACC inputs as of July 2, 2026
- U.S. Treasury 10-year rate; Yahoo Finance / Google Finance beta; StockAnalysis.com
  peer statistics

## Methodology

Revenue grows 1.0% in FY2026E and gradually reaches 3.0% by FY2029E–FY2030E. Gross
margin stays near 28%, while SG&A improves from 20.5% to 20.1% of revenue. Working
capital accounts are driven off revenue or COGS ratios. PP&E rolls forward through
capex and depreciation; retained earnings rolls through net income and dividends;
APIC grows with stock-based compensation. Ending cash comes from the cash flow
statement and links to the balance sheet, it isn't a plug.

The DCF discounts FY2026E–FY2030E unlevered free cash flow at an 8.27% WACC. Terminal
value uses a 2.0% perpetuity growth rate, with an 8.0x exit EV/EBITDA method as a
cross-check. The sensitivity grid rebuilds the valuation independently in every cell.

FY2021A/FY2022A revenue combines Target's original "Sales" + "Other revenue" lines to
match the single "Net sales" line used from FY2023A onward.

## Key findings

- Base-case WACC: **8.27%**
- Gordon-growth implied share price: **$99.53**
- Current share price (July 2, 2026): **$130.21**
- Implied downside: **23.6%**
- Exit-multiple cross-check: **$115.47 per share**
- Balance check: **$0 in every year, FY2021A–FY2030E**

The base case suggests Target's shares are priced above conservative intrinsic value,
driven by modest revenue recovery, a limited margin expansion path, and a terminal
value constrained by the 8.27% WACC and 2.0% long-run growth assumption.

## Limitations

- Forecast assumptions are simplified annual drivers, not management guidance or a
  detailed store/category build.
- Debt balances, lease liabilities, interest expense, and share count are held flat
  through the projection period.
- No projected debt issuance, repayment, or share repurchases.
- Book debt is used as a proxy for market debt.
- Peer medians aren't treated as a primary valuation method: Walmart, Costco, and TJX
  carry premium growth and quality multiples that aren't directly comparable to
  Target's current profile.
- Valuation is highly sensitive to WACC and terminal growth; use the sensitivity tab
  to frame a range rather than imply false precision.
