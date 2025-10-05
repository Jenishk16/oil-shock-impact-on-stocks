# Quantitative Analysis: Impact of Crude Oil on Indian Equity Sectors
### Overview
This project investigates how fluctuations in crude oil prices (WTI futures) affect selected Indian stocks across different sectors — airlines, paints, chemicals, and energy companies.
The analysis combines time-series data and event based study to understand both short-term and long-term oil sensitivities.

### Objectives
1. Quantify the relationship between oil returns and stock returns.
2. Examine rolling correlations to capture time-varying co-movements.
3. Study event impacts (e.g., 2020 COVID crash, 2022 oil spike).

### Tools & Libraries
1. Python: pandas, numpy, matplotlib, seaborn
2. Econometrics: statsmodels, arch
3. Data Source: Yahoo Finance

### Methodology
1. Data Collection and Preprocessing
   a. Downloaded daily closing prices from Yahoo Finance
   b. Computed log or percentage daily returns
2. Exploratory Analysis
   a. Correlation matrix across assets
   b. Cumulative returns visualization
3. Rolling Correlation
  a. 90-day rolling window between Oil and each stock
  b. Plotted dynamic correlations over time
  c. Computed average and median rolling correlations to summarize behavior
4. Event Study
  a. Analyzed oil shock events:
     i. March 2020 (COVID crash & oil war)
     ii. March 2022 (Russia–Ukraine crisis)

### Key Findings
1. ONGC exhibits the highest positive correlation with crude oil prices, reflecting its position in the upstream oil sector
2. IndiGo, IOC, and Asian Paints show negative correlations, as these sectors are dependent on oil as a key input material
3. Following major oil-related events, ONGC maintained a positive correlation with oil prices, whereas the other stocks displayed negative correlations, consistent with their cost sensitivities.
4. Overall analysis indicates no strong long-term correlation between oil prices and these selected Indian equities.


