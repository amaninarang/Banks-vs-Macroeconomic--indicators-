# Banks-vs-Macroeconomic--indicators-
## A Collaborative Data & Financial Analysis Project
Contributor: Amani Narang — Inflation Analysis Lead
## Project Summary
This project analyzes how major U.S. investment banks (Goldman Sachs, JPMorgan, Morgan Stanley, Bank of America, Citigroup) respond to key macroeconomic indicators between 2020 and 2024.
  - Monthly stock returns
- Inflation (YoY CPI) trends (my section)
- GDP growth
- Treasury yield spreads (10Y–2Y & 10Y–3M)
- Correlations between banks and macro trends
- Regression of bank returns vs. S&P 500
- Rolling correlations and visualization-based insights

The project integrates time-series analysis, macroeconomics, financial modeling, data visualization, and statistical techniques.
## Collaboration Note
This was a group project.

The repository contains the full combined notebook for reference.
## My Individual Contribution: Inflation Analysis (CPI YoY)
I led the full inflation section, including:
- Extracting CPI data from FRED
- Cleaning and resampling inflation into YoY rates
- Merging inflation with bank price data
- Correlation analysis: inflation vs. stock price
- Determining statistical significance (p-values)
- Visualizing inflation with dual-axis normalized bank charts
- Building a correlation heatmap of inflation vs. each bank
- Summarizing key findings around inflation sensitivity
  
My work demonstrates macroeconomic interpretation, data wrangling, statistical testing, and financial visualization.
## Key Findings from My Inflation Analysis
- Inflation peaked at 9.0% in June 2022
- Morgan Stanley and Bank of America showed positive and statistically significant correlations with inflation
- Citigroup and JPMorgan showed weak or negative correlations
- Inflation shocks aligned with major stock volatility (2020 crash, 2022 tightening cycle)
- Banks displayed different sensitivity profiles, highlighting varying business models and risk exposure
## Technical Stack
### Languages & Libraries:
- Python (Pandas, NumPy, SciPy, StatsModels, Seaborn, Matplotlib)
- yfinance
- FRED API (fredapi, pandas-datareader)
- Tabulate
- Google Colab / Jupyter Notebook
## Example Key Insights (Across Full Project)
- Investment banks tend to rise with economic growth (GDP) but react differently to inflation and rates.
- The 10Y–2Y yield spread inversion coincided with increased volatility post-2022.
- Morgan Stanley delivered the strongest return (+181%), while Citigroup lagged (+13.7%) from Feb 2020–2024.
- Rolling correlations highlight how economic shocks (COVID, inflation spike) change bank sensitivity through time.
