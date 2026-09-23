# Excel Practice: Financial Modelling & Data Analysis

This folder holds Excel exercises I completed to build core skills used in Data Analyst, BI Analyst, and Finance Analyst work — financial statement modelling and large-dataset summarisation with PivotTables/Slicers. These are guided practice exercises (not live client or company data), included here to show hands-on repetition with the tools, not as a standalone analytical project. For an end-to-end independent project, see [Indonesia Financials Analysis](https://github.com/egimaulanamalik/indonesia-financials-analysis) and the accompanying [Tableau dashboard](https://public.tableau.com/app/profile/muhammad.egi.maulana.malik/viz/ComparativeAnalysisofSelectedIndonesianListedCompanies2022-2025/Overview).

## Files

### 1. `A_3-Statement_Model__P_L__BS__CF_.xlsx`
**A linked 3-statement financial model (P&L, Balance Sheet, Cash Flow).**

- Built a forecast (2017–2021) driven off historical actuals (2014–2016), with a scenario switch (e.g. "Best case") that flows through all three statements
- Linked supporting schedules — Fixed Asset roll-forward, Financial Liabilities (debt) schedule, and Equity schedule — into the core statements so the model updates consistently when an assumption changes
- Calculated year-over-year variance (%) on revenue and cost lines
- **Skills demonstrated:** financial statement linkage, formula-driven forecasting, schedule building, scenario logic, working with `$ in million` formatted multi-year data

### 2. `Build_an_FMCG_Model_-_Using_PIVOT___Slicers.xlsx`
**Sales & margin analysis on an ~88,000-row FMCG transactional dataset.**

- Summarised raw transaction-level data (volume, gross sales, discounts, net sales, COGS, distribution, warehousing) by brand and by month/year using PivotTables
- Added Slicers for interactive filtering across brand, client, and period
- Built a summary "Structure" sheet that bridges Volume → Gross Sales → Net Sales → Gross Profit → Full Delivered Margin, with year-over-year absolute and % variance
- **Skills demonstrated:** PivotTables on large datasets, Slicers for interactive filtering, building a margin/P&L bridge, YoY variance analysis

## Why this is here

I'm targeting remote Data Analyst / BI Analyst / Finance Analyst / Business Analyst roles and building my portfolio around SQL, Python, and Tableau, with Excel as the foundation I learned first. These files show consistent practice with the modelling and analysis patterns (statement linkage, pivoting large datasets, variance analysis) that carry over directly into SQL and BI tool work.
