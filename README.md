# Task Planning and Completion Analysis

A personal Data Science project analyzing my daily task planning and completion behavior over three months (November 2025 – February 2026), while also clearing 20 long-standing backlog items.

This project served both as a productivity experiment and a practical application of data cleaning, exploratory data analysis (EDA), and statistical hypothesis testing.

## Project Overview

- **Time period**: November 4 2025 – February 7 2026 (96 days)
- **Main datasets**:
  - `daily_plan_table.csv` — daily tasks & planning records
  - `backlog_table.csv` — long-term backlog items (20 tasks)
- **Objective**: Investigate relationships between planning behavior, task streaks and completion, backlog reduction, and personal productivity patterns
- **Outcome**: Successfully rejected all three null hypotheses → found statistically significant relationships
- **Final grade**: 100/100 (academic evaluation)

## Research Questions / Hypotheses Tested

1. Does creating a daily task plan influence planning streak?
   → Tested with **Point-Biserial Correlation**

2. Does planning streak length affect completion rate?
   → Tested with **Pearson Correlation Analysis**

3. Does daily planning reduce backlog tasks? 
   → Tested with **One-tailed Binomial Test**

All three null hypotheses were rejected (p < 0.05).

## Tech Stack & Libraries

- **Language**: Python 3
- **Core libraries**:
  - pandas → data cleaning & transformation
  - numpy → numerical operations
  - scipy → statistical tests
  - matplotlib + seaborn → visualization
- **Analysis types**: EDA, descriptive statistics, correlation analysis, hypothesis testing
