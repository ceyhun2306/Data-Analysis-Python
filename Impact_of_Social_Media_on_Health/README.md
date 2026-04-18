# Social Media Impact on Student Mental Health 📊

## Overview
This project analyzes how digital platform usage affects the mental
health, sleep patterns, and academic performance of students.
The analysis goes beyond basic visualization — every finding is backed
by statistical evidence and cause-effect reasoning.

## Dataset
- **Source:** Kaggle
- **Size:** 1,705 students, 11 features
- **Target variable:** Mental Health Score (4–9)
- **Key features:** Daily usage hours, sleep hours, platform used,
  academic level, overall impact

## Key Findings
- Daily screen time is the strongest predictor of mental health
  (r = -0.83) — students using platforms 6+ hours score ~5/9,
  while those under 3 hours score ~8/9
- A compounding chain was identified: more screen time → less sleep
  → worse mental health (r = -0.82 between usage and sleep)
- A critical threshold exists at ~6 hours — beyond this point,
  even adequate sleep fails to offset negative mental health outcomes
- Platform choice has a statistically significant but minor effect
  (ANOVA, p < 0.05) — LinkedIn users score highest, TikTok lowest,
  but the gap is only 0.67 points vs. 3 points driven by usage hours

## Sample from project

<img width="1776" height="592" alt="download" src="https://github.com/user-attachments/assets/3740dc0a-da6a-4183-bc91-cca217152e7c" />

- Avg_Daily_Usage_Hours shows a strong negative correlation with
  Mental_Health_Score (r = -0.83) — the strongest relationship in
  the dataset. Students spending 2–3 hours daily report noticeably
  higher mental well-being, while 6+ hours is associated with
  significantly lower scores.

- Sleep_Hours_Per_Night shows a strong positive correlation with
  Mental_Health_Score (r = 0.79) — more sleep consistently leads
  to better mental health outcomes.

- Critically, Usage_Hours and Sleep_Hours are also strongly negatively
  correlated (r = -0.82), suggesting that excessive screen time
  reduces sleep, which in turn further damages mental health.
  This indicates a compounding effect: more usage → less sleep →
  worse mental health.

- These three variables form a clear chain of influence, making
  daily usage hours the primary behavioral risk factor in this dataset.


## Methodology
- Exploratory Data Analysis (univariate, bivariate, multivariate)
- Correlation analysis & heatmaps
- Hypothesis testing: T-test, One-Way ANOVA, Pearson Correlation
- Visualization: histograms, violin plots, scatter plots, bar charts

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (hypothesis testing)
