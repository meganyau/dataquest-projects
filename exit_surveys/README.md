# Exit Surveys (DETE & TAFE): Dissatisfaction vs Tenure & Age

Exploratory analysis of employee exit surveys from two Queensland public sector institutions to examine whether resignation due to dissatisfaction varies by tenure and age.

**Notebook:** `exit_surveys.ipynb`  
**Data:** DETE (Department of Education, Training and Employment) and TAFE (Technical and Further Education) exit survey datasets, Queensland, Australia  

## Methods

- Cleaned and standardized tenure and age categories across datasets.
- Filtered to resignation cases only.
- Created dissatisfaction indicator from survey responses.
- Grouped by tenure and age to compute dissatisfaction proportions.
- Visualized trends using bar charts and category comparisons.

## Key findings

- Employees with longer tenure (≥7 years) show higher dissatisfaction rates, peaking in the 7–10 year range.
- Short-tenure employees show lower dissatisfaction.
- Age has a weaker relationship; the 50+ group shows slightly higher dissatisfaction, though small sample sizes limit interpretation.

## Interpretation

Tenure appears to be a stronger indicator of dissatisfaction-related resignation than age, suggesting that long-term employee experience may influence exit decisions more than demographic factors alone.

## Tools used

Python, Pandas, NumPy, Matplotlib

## How to run

Python 3.11; install `pandas`, `numpy`, and `matplotlib`.  
Open the notebook and run all cells.
