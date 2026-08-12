%%writefile dcf_theory.md

# DCF Theory

## What is DCF?

Discounted Cash Flow (DCF) valuation estimates the present value of a company's future cash flows.

The basic idea is that money received in the future is worth less than money received today.

## FCFF

A simplified FCFF formula is:

FCFF = EBIT(1 - Tax Rate) + D&A - CapEx - Change in NWC

Where:

- EBIT = Earnings Before Interest and Taxes
- Tax Rate = Corporate tax rate
- D&A = Depreciation and Amortization
- CapEx = Capital Expenditures
- Change in NWC = Change in Net Working Capital

## WACC

WACC represents the weighted average cost of the capital used to finance a company.

WACC = [E/(D+E)] × Re + [D/(D+E)] × Rd × (1-T)

Where:

- E = Market value of equity
- D = Market value of debt
- Re = Cost of equity
- Rd = Cost of debt
- T = Tax rate

## Terminal Value

Using the Perpetuity Growth Method:

TV = FCF_n(1+g)/(WACC-g)

Where:

- FCF_n = Free cash flow in the final forecast year
- g = Long-term perpetual growth rate
- WACC = Weighted Average Cost of Capital

## Enterprise Value

Enterprise Value is approximately:

PV of forecast FCFF + PV of Terminal Value

## Equity Value

Equity Value = Enterprise Value - Debt + Cash

## Intrinsic Value Per Share

Intrinsic Value Per Share = Equity Value / Shares Outstanding

## Important Assumption

The Perpetuity Growth Method requires:

WACC > g

The long-term growth rate should generally be a conservative assumption rather than an extremely high growth rate.
