# Starbucks (SBUX): Five-Year Financial Model and DCF Valuation

A fully linked financial model of Starbucks Corporation (NASDAQ: SBUX), built in Excel. It takes the company's reported FY2023 to FY2026 results, projects FY2027 to FY2031, and values the business with a discounted cash flow (DCF).

- **Base year:** FY2026 actual (year ended 27 September 2026)
- **Forecast period:** FY2027E to FY2031E
- **Valuation date:** November 2026
- **Currency:** US$ millions, except per-share data

## What's in this repo

| File | What it is |
|---|---|
| `Starbucks_DCF_Model_FY2026.xlsx` | The full model: three statements, DCF, scenarios and ratios |
| `Harshit_Portfolio_Overview.docx` | A short overview of my wider analytics and finance portfolio |

## Tabs in the workbook

| Tab | What it does |
|---|---|
| Cover | Purpose, how to use the model, colour key |
| Assumptions | Every driver (growth, margins, working capital, capex). The Bear / Base / Bull switch is here |
| Income Statement | FY2023A to FY2026A actuals and FY2027E to FY2031E projections |
| Balance Sheet | Linked to the other statements. Cash is the plug, and a check row proves Assets = Liabilities + Equity (it is zero in every year) |
| Cash Flow | Operating, investing and financing cash flows, linked to the other two statements |
| DCF | WACC build, free cash flow to the firm (FCFF), terminal value, sensitivity table and an exit-multiple cross-check |
| Scenario Summary | A full valuation for Bear, Base and Bull side by side |
| Ratio Analysis | Profitability, growth, liquidity, leverage, efficiency and valuation ratios, plus a written valuation call |

## How to use it

1. Open the **Assumptions** tab and pick a scenario (Bear, Base or Bull) in the yellow cell.
2. All statements, the DCF and the ratios update from that one switch.
3. Update the market inputs on the **DCF** tab (share price, risk-free rate, beta) to today's values.
4. Open **Scenario Summary** to compare all three valuations.

Colour key: blue is a hardcoded input or reported actual, green is a link to another tab, black is a formula. Yellow fill marks a key input you can change.

> **Note:** the file is saved with the **Bull** scenario switched on, so the DCF tab opens on the Bull result. Set the Assumptions scenario cell to **Base** to see the central case.

## Key results

Implied value per share against a market price of about $103:

| Scenario | Implied share price | Versus market |
|---|---|---|
| Bear | $29.11 | -72% |
| Base | $42.34 | -59% |
| Bull | $59.42 | -42% |

DCF setup (same for all three scenarios; only the operating drivers change):

- Cost of equity: 10.0% (risk-free rate 4.8% + beta 0.95 x equity risk premium 5.5%)
- After-tax cost of debt: about 2.9%
- WACC: about 9.3% (roughly 90% equity, 10% debt)
- Terminal growth rate: 2.5%
- Diluted shares: 1,143.4 million

The exit-multiple cross-check (15x EV/EBITDA) and the WACC vs terminal growth sensitivity table sit on the DCF tab. They show the range of plausible values, not a single point.

## What the model says

- **The price already assumes a strong recovery.** Starbucks trades at roughly 47x trailing earnings. Even the Bull case values the shares well below today's price, so the market is pricing in a fast and full turnaround.
- **FY2025 was the low point.** Operating margin fell to 7.9% and recovered to 9.7% in FY2026. The forecast assumes margins stay near FY2026 levels, not a return to the mid-teens of FY2023.
- **Negative equity is normal here.** Years of buybacks leave Starbucks with a shareholders' deficit, so return on equity and debt-to-equity are marked "n/m". Leverage is read through net debt / EBITDA and interest coverage instead.
- **Current ratio below 1.0x is not a warning sign.** Customers pay on the spot, receivables are small, and gift-card balances help fund the business.

## Sources and limits

- Historical figures come from Starbucks' reported FY2023 to FY2026 filings.
- Market inputs (share price, risk-free rate, beta, equity risk premium) are early November 2026 estimates. Refresh them before relying on the output.
- This is a modelling and learning project. It is not investment advice.

*Prepared by Harshit Maheshwari.*
