# Financial Trend Analysis Using Nasdaq Data Link API

## Project Overview
This project explores company-level and regional financial performance using data retrieved from the Nasdaq Data Link API. The analysis focuses on **accrued expenses turnover** as a proxy for short-term expense management efficiency and liquidity behavior over time.

Using Python and pandas, the project examines both **temporal trends** and **cross-sectional differences** across companies and countries, highlighting how firm-specific practices and regional composition influence observed financial metrics.

## Objectives
- Analyze the historical trend of accrued expenses turnover across selected companies
- Compare expense turnover behavior across different countries and regions
- Identify stability, volatility, and outliers in financial performance
- Demonstrate how aggregation choices (firm-level vs country-level averages) affect interpretation

## Data Source
- **Nasdaq Data Link API**
- Financial statement metrics for publicly listed companies
- Time range: multiple years (2010–2015)

## Methods & Tools
- Python (pandas, matplotlib)
- API-based data ingestion
- Time-series visualization
- Grouped aggregation and comparative analysis

## Key Insights
- Large, mature firms tend to show lower but more stable accrued expenses turnover, reflecting deliberate working-capital strategies rather than weak performance.
- High country-level averages can be driven by a small number of volatile firms, emphasizing the importance of outlier awareness.
- Regional comparisons are sensitive to firm composition, industry mix, and data availability.

## Limitations
- Uneven firm counts across countries
- Industry differences not explicitly controlled
- Metric interpretation depends on accounting practices and scale

## Next Steps
- Normalize comparisons by industry
- Extend analysis to additional liquidity and efficiency ratios
- Incorporate statistical measures (variance, rolling averages)

