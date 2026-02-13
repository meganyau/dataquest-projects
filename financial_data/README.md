# Financial Trend Analysis Using Nasdaq Data Link API

## Project Overview
This project analyzes company-level and regional financial performance using data retrieved from the Nasdaq Data Link API. The focus is on **accrued expenses turnover** as a proxy for short-term expense management efficiency and liquidity behavior over time.

The analysis examines both **temporal trends** and **cross-sectional differences**, highlighting how firm-level practices and regional composition influence financial metrics.

## Objectives
- Evaluate historical trends in accrued expenses turnover
- Compare expense turnover across countries and regions
- Identify stability, volatility, and outliers
- Assess how aggregation choices (firm-level vs. country-level averages) affect interpretation

## Data Source
- Nasdaq Data Link API
- Financial statement metrics for publicly listed companies
- Time range: 2010–2015

## Methods & Tools
- Python (pandas, matplotlib)
- API-based data ingestion
- Time-series visualization
- Grouped aggregation and comparative analysis

## Key Insights
- Large, mature firms exhibit lower but more stable turnover ratios, consistent with structured working-capital strategies.
- Country-level averages can be skewed by a small number of volatile firms, underscoring the importance of outlier awareness.
- Regional comparisons are highly sensitive to firm composition and industry mix.

## Limitations
- Uneven firm counts across countries
- Industry effects not explicitly controlled
- Accounting differences may influence comparability

## Next Steps
- Normalize comparisons by industry
- Extend to additional liquidity and efficiency ratios
- Incorporate rolling averages and variance analysis

