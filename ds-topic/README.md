# Popular Data Science Questions

## Project Overview

This project analyzes questions from the Data Science Stack Exchange to determine which topics a data science education company should prioritize when developing new content.

Rather than relying on intuition, this analysis uses real user behavior data — including tag frequency, view counts, time trends, and favorite counts — to identify topics that demonstrate both broad popularity and disproportionate engagement.

---

## Data Sources

- 2019 question dataset (SEDE extract)
- Historical question dataset (all years prior to 2020)
- Key columns analyzed:
  - Tags
  - ViewCount
  - FavoriteCount
  - CreationDate

---

## Methodology

### 1. Popularity Analysis (2019 Snapshot)

- Cleaned tag strings into structured lists
- Computed tag frequency (most used)
- Computed total views per tag (most viewed)

Top recurring topics included:
- Machine Learning
- Python
- Deep Learning
- Neural Networks
- Classification
- NLP
- Keras
- Scikit-Learn
- TensorFlow
- Time Series

This established baseline mass interest.

---

### 2. Trend Analysis (Quarterly)

Using the full dataset:

- Classified posts by topic (e.g., Deep Learning, Recommender Systems)
- Grouped data quarterly
- Measured topic rate relative to total questions

Findings:
- Deep Learning showed sustained growth over time.
- Recommender Systems remained stable but did not accelerate.

This distinguished growing themes from mature or plateauing topics.

---

### 3. Engagement Analysis (Favorites & Lift)

To measure deeper user interest:

- Filtered posts with FavoriteCount > 1
- Computed tag frequency among favorited posts
- Calculated Lift:

  Lift = (FavRate / AllRate)

Interpretation:
- Lift > 1 → Overrepresented in favorited posts
- Lift ≈ 1 → Neutral
- Lift < 1 → Underrepresented

Specialized topics such as:
- Transfer Learning
- Attention Mechanisms
- Cost Functions
- Feature Scaling
- Transformer-related tags

showed disproportionate engagement relative to baseline frequency.

---

## Key Findings

1. Broad topics (Machine Learning, Python) dominate in volume.
2. Deep Learning exhibits sustained long-term growth.
3. Specialized, technically dense topics generate stronger bookmarking behavior.
4. High-engagement content is often implementation-heavy or architecture-focused.

---

## Business Implication

For a data science education company:

- Foundational content (ML, Python, DL basics) ensures mass reach.
- Specialized modules (transformers, transfer learning, optimization details) drive deeper engagement and differentiation.

A hybrid content strategy balancing breadth and depth is optimal.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- SQL (SEDE extraction)

---

## Future Improvements

- Compute average FavoriteCount per tag (not just threshold-based)
- Incorporate score (upvotes) into engagement analysis
- Cluster tags into thematic categories
- Perform statistical significance testing on lift
