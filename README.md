# Apple vs. Microsoft Valuation Comparison

## Project Overview

This project presents a full valuation comparison between **Apple Inc.** and **Microsoft Corporation** using multiple valuation methods, including comparable company analysis, DCF valuation, 3-statement modeling, sensitivity analysis, and valuation range analysis.

The workbook combines previously built Apple and Microsoft DCF models and 3-statement models with additional market data, valuation multiples, charts, and written summaries. The goal of the project is to compare both companies from an operating, profitability, and valuation perspective.

This project was created as part of a financial modeling portfolio to demonstrate Excel-based valuation, financial statement modeling, DCF analysis, sensitivity analysis, chart creation, and investment-style summary writing.

---

## Workbook Included

* `Apple vs. Microsoft valuation comparison.xlsx`

The workbook includes:

* Cover page
* Apple vs. Microsoft comps table
* Valuation and profitability summary
* DCF comparison
* Apple DCF model
* Microsoft DCF model
* Apple 3-statement model
* Microsoft 3-statement model
* DCF sensitivity analysis
* Valuation range chart
* Supporting charts and written summaries

---

## Comparable Company and Valuation Summary

The comparable company analysis compares Apple and Microsoft using market data, financial data, and valuation multiples.

Metrics included:

* Share price
* Market capitalization
* Enterprise value
* Sales
* EBITDA
* EBIT
* Earnings
* EV/Sales
* EV/EBITDA
* EV/EBIT
* P/E

This section shows that Microsoft trades at a higher EV/Sales multiple, while Apple trades at higher EV/EBITDA, EV/EBIT, and P/E multiples. This suggests Apple is more expensive on profit-based valuation metrics, while Microsoft receives a higher valuation per dollar of revenue.

Microsoft also shows stronger profitability, with better EBITDA and net margins, suggesting it converts revenue into profit more efficiently than Apple.

![Comparable Company Analysis Part 1](screenshots/comps-table-part-1.png)

---

## DCF Comparison and Charts

The DCF comparison summarizes the implied share price, current share price, upside/downside, terminal growth rate, discount rate, terminal value, implied equity value, and implied enterprise value for both companies.

### Apple DCF Output

* Current share price: `$231.27`
* DCF implied share price: `$236.73`
* Upside/downside: `2.36%`
* Terminal growth rate: `4.00%`
* Discount rate: `7.50%`
* Selected terminal value: `$4,436,337 million`
* Implied equity value: `$3,578,355 million`
* Implied enterprise value: `$3,598,934 million`

Apple appears slightly undervalued under the selected base-case assumptions. However, Apple’s valuation is more dependent on optimistic assumptions, including a lower discount rate and higher terminal growth rate.

### Microsoft DCF Output

* Current share price: `$384.41`
* DCF implied share price: `$414.03`
* Upside/downside: `7.71%`
* Terminal growth rate: `2.50%`
* Discount rate: `9.00%`
* Selected terminal value: `$3,995,350 million`
* Implied equity value: `$3,090,748 million`
* Implied enterprise value: `$3,121,094 million`

Microsoft appears modestly undervalued under the selected base-case assumptions and shows stronger relative upside compared to Apple.

![DCF Comparison Charts and Summary](screenshots/comps-table-part-2.png)

---

## Apple and Microsoft 3-Statement Models

The workbook includes previously built 3-statement models for both Apple and Microsoft. These models provide the financial statement foundation for the DCF valuations.

Each 3-statement model includes:

* Income statement
* Balance sheet
* Cash flow statement
* Supporting assumptions
* Forecasted financial line items

The 3-statement models support the DCF valuation process by helping estimate future free cash flow, profitability, capital expenditures, working capital needs, and valuation outputs.

---

## DCF Sensitivity Analysis

The sensitivity analysis shows how Apple’s and Microsoft’s implied share prices change under different discount rate and perpetual growth assumptions.

The rows represent the **discount rate**. Higher discount rates reduce valuation because future cash flows are discounted more heavily.

The columns represent the **perpetual growth rate**. Higher perpetual growth assumptions increase valuation because the terminal value becomes larger.

The top-left value in each sensitivity table represents the linked base-case DCF implied share price from the model.

For Apple, the sensitivity table shows that valuation is highly dependent on discount rate and terminal growth assumptions. At a `9.0%` discount rate and `3.0%` perpetual growth rate, Apple’s implied value is `$182.04` per share, which is below its current share price of `$231.27`. This suggests Apple appears overvalued under more conservative assumptions. However, Apple’s linked base-case DCF implied value is `$236.73`, reflecting a lower discount rate and higher terminal growth rate.

For Microsoft, the sensitivity table shows stronger support for the current market price. At a `9.0%` discount rate and `2.5%` perpetual growth rate, Microsoft’s implied value is `$414.03` per share, compared to its current share price of `$384.41`. This suggests Microsoft appears modestly undervalued under the base-case assumptions.

Overall, the sensitivity tables show that valuation conclusions depend heavily on assumptions. Lower discount rates and higher perpetual growth rates increase implied share prices, while higher discount rates and lower perpetual growth rates reduce implied share prices.

![DCF Sensitivity Analysis](screenshots/sensitivity-analysis-table.png)

---

## Valuation Range Analysis

The valuation range chart compares Apple and Microsoft across multiple valuation methods.

Valuation methods included:

* 52-week trading range
* Comparable company valuation
* DCF sensitivity range
* DCF base case range
* Analyst target range

This section helps show where each company’s valuation falls across different valuation approaches. Microsoft shows stronger upside across most valuation methods, especially comparable company valuation, DCF sensitivity, and analyst target ranges. Apple still shows potential upside in some cases, but its valuation appears more dependent on favorable assumptions.

![Valuation Range Chart](screenshots/valuation-range-chart.png)

---

## Key Findings

### Apple

Apple has the larger market capitalization and trades at higher EV/EBITDA, EV/EBIT, and P/E multiples. This suggests Apple is more expensive based on profit-based valuation metrics.

The Apple DCF model shows slight upside under the selected base-case assumptions. However, Apple’s valuation is more dependent on favorable assumptions, especially the lower discount rate and higher terminal growth rate used in the model.

Under more conservative sensitivity assumptions, Apple’s implied share price falls below the current market price, suggesting the stock may be closer to fairly valued or overvalued depending on the assumptions used.

### Microsoft

Microsoft trades at a higher EV/Sales multiple, suggesting the market places a higher value on each dollar of Microsoft revenue. Microsoft also shows stronger EBITDA and net margins, meaning it converts revenue into profit more efficiently than Apple.

The Microsoft DCF model shows stronger relative upside than Apple under the selected assumptions. Microsoft also appears stronger across several valuation range outputs, including comparable company valuation, DCF sensitivity analysis, and analyst target ranges.

### Overall Conclusion

This valuation comparison suggests that Microsoft has the stronger valuation profile across most of the selected methods. Microsoft shows stronger profitability, higher DCF upside, and stronger support across valuation ranges.

Apple remains a high-quality company, but its valuation appears more dependent on favorable assumptions, including a lower discount rate and higher terminal growth rate.

---

## Skills Demonstrated

This project demonstrates the following financial modeling and Excel skills:

* 3-statement financial modeling
* DCF valuation
* Free cash flow forecasting
* Terminal value analysis
* Discount rate and terminal growth assumptions
* Enterprise value to equity value bridge
* Comparable company analysis
* Trading multiple analysis
* EV/Sales, EV/EBITDA, EV/EBIT, and P/E analysis
* Sensitivity analysis
* Valuation range analysis
* Financial chart creation
* Excel formatting and presentation
* Investment-style summary writing
* Data organization and workbook structuring

---

## Data Sources and Assumptions

Historical financial data was sourced from company filings, Yahoo Finance, and previously built Apple and Microsoft 3-statement and DCF models. Market data, including current share prices and analyst target ranges, was based on online research as of the model date.

Forecast assumptions, discount rates, terminal growth rates, valuation ranges, and other model inputs were developed using educated and realistic assumptions for educational and portfolio purposes. Some assumptions are hypothetical and are meant to demonstrate financial modeling methodology rather than provide a formal investment recommendation.

---

## Important Notes

This project is for educational and portfolio purposes only. It is not intended to be investment advice or a recommendation to buy, sell, or hold any security.

The valuation outputs depend heavily on the assumptions used in the model. Changes in discount rates, terminal growth rates, revenue growth, margins, capital expenditures, working capital, and share count can significantly impact the implied share price.

---

## How to Use the Workbook

1. Open the Excel workbook.
2. Start with the cover page for a high-level overview.
3. Review the comps table to compare valuation multiples.
4. Review the Apple and Microsoft 3-statement models.
5. Review the Apple and Microsoft DCF models.
6. Review the sensitivity analysis to understand how assumptions impact valuation.
7. Review the valuation range chart to compare outputs across different valuation methods.
8. Read the written summaries to understand the key conclusions.

---

## Project Status

Completed as a portfolio project.

Future improvements could include adding a broader peer group such as Alphabet, Amazon, Meta, Nvidia, Adobe, Oracle, and Salesforce to create a more complete comparable company analysis.
