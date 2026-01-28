# Indicators of Heavy Traffic on I-94 (Westbound)

Exploratory analysis of hourly traffic volume at a single westbound station on I-94 (Minneapolis–St. Paul) to identify time-based indicators of heavy traffic.

- **Notebook:** `I94_traffic.ipynb`
- **Data:** `Metro_Interstate_Traffic_Volume.csv` 

## Methods
- Focus on **daytime** (07:00–19:00) to avoid overnight skew.  
- Aggregate by **month, weekday, and hour**, plot distributions and rush-hour profiles.  
- Compute simple correlations on numeric weather/time fields.

## Key findings
- **Rush hours:** business-day peaks around **~07:00** and **~16:00–17:00** reach ≈ **6.2k** cars/hour; weekends plateau near **~4.3k** midday.  
- **Seasonal:** higher **Mar–Oct**, dip in **July**, taper into December.  
- **Weather:** weak incremental signal compared with calendar/time features.


## Data source
Metro Interstate Traffic Volume dataset (MN DOT / UCI ML-style release). 


