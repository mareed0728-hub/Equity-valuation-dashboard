# Equity Valuation Dashboard

**Live app:** https://equity-valuation-dashboard-ck3zg4j9nr4xgzfr9bgxhs.streamlit.app/

<img width="1432" height="812" alt="Football field valuation chart" src="https://github.com/user-attachments/assets/8154b264-e944-4796-9240-eb954014ac0a" />


An interactive Streamlit dashboard that values a public company using a discounted cash flow (DCF) model, comparable-company analysis, and sensitivity testing. Enter any ticker to pull its financial statements and market data from Yahoo Finance.

## Features

- **Fundamentals & FCF:** Revenue, net income, operating income, free cash flow, and key ratios across recent fiscal years
- **DCF Valuation:** CAPM cost of equity, WACC, projected free cash flow, terminal value, and intrinsic value per share, with adjustable assumptions in the sidebar
- **Comparable Companies:** Peer P/E, EV/EBITDA, and P/S multiples with implied share values
- **Sensitivity Analysis:** WACC vs. terminal growth heatmap showing how the valuation changes
- **Valuation Summary:** Football field chart comparing DCF, comps, and the 52-week trading range
- **Investment Analysis:** Written conclusion tied to the model results

## Built With

Python, Streamlit, yfinance, pandas, NumPy, Plotly

## Run Locally


## Disclaimer

For educational purposes only. Not investment advice. Data comes from Yahoo Finance and may be delayed or incomplete.
