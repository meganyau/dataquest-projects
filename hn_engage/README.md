# Hacker News Engagement Analysis

Exploratory analysis of Ask HN and Show HN posts to compare average comment engagement and identify time-based indicators of higher discussion activity.

**Notebook:** `hn_engagement.ipynb`  

## Methods

- Focus on Ask HN and Show HN posts only.
- Compute average comment counts by post type.
- Parse timestamps using `datetime` and aggregate by hour.
- Calculate average comments per hour to identify peak engagement windows.

## Key findings

- **Content type:** Ask HN posts receive higher average comments (~14) compared to Show HN posts (~10), indicating stronger discussion-driven engagement.
- **Timing:** Engagement peaks around 3 PM, followed by 2 PM and 8 PM.
- **Optimal windows:** Mid-afternoon (2–4 PM) and early evening (8–9 PM) show the highest average comment activity.

## Data source

Hacker News dataset (Y Combinator / Dataquest project dataset).
