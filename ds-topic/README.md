# Popular Data Science Questions

Exploratory analysis of Data Science Stack Exchange posts to identify high-impact topics for a data science education company based on popularity, trend growth, and engagement.

**Notebook:** `ds-stackexchange-topic-analysis.ipynb`  
**Data:** SEDE Data Science Stack Exchange extracts (2019 + historical dataset)

## Methods

- Cleaned and parsed tag strings into structured lists.
- Measured tag frequency and total views (2019 snapshot).
- Analyzed quarterly topic trends across historical data.
- Filtered posts with FavoriteCount > 1 and computed Lift:

  Lift = FavRate / AllRate

## Key findings

- Broad topics (Machine Learning, Python) dominate in overall volume.
- Deep Learning shows sustained long-term growth.
- Recommender Systems remain stable but not accelerating.
- Specialized topics (e.g., transfer learning, attention mechanisms, optimization concepts) show disproportionate engagement.

## Business implication

Foundational content ensures mass reach, while advanced, technically dense modules drive stronger user engagement. A hybrid strategy balancing breadth and depth is optimal.

## Tools used

Python, Pandas, Matplotlib, Seaborn, SQL (SEDE extraction)

## Future improvements

- Use average FavoriteCount per tag for stronger engagement metrics
- Incorporate upvote score analysis
- Cluster tags into thematic categories
- Test statistical significance of lift
