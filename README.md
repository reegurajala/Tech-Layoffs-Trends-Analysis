# Tech Layoffs Analysis (2020–2026)

## Overview
An end-to-end SQL and Python analysis of global tech layoffs from 2020 to 2026 using data sourced from layoffs.fyi. The project investigates which industries, companies, and geographies drove the mass layoff wave that began during COVID-19 and has continued through 2026.

**Business Question:** Which industries, companies, and time periods drove the most layoffs, and what patterns emerge from the data?

## Dataset
- **Source:** layoffs.fyi via Kaggle
- **Link:** https://www.kaggle.com/datasets/swaptr/layoffs-2022
- **Records:** 4,361 layoff events
- **Coverage:** March 2020 – April 2026
- **Note:** Dataset is actively maintained and updated regularly

## Tools & Technologies
- Python (pandas, matplotlib, seaborn)
- SQL (SQLite)
- Jupyter Notebook

## Key Findings
1. **2023 was the peak year** with 264,320 layoffs across 749 companies — nearly double 2022
2. **Amazon leads all companies** with 58,124 total layoffs across 13 separate rounds of cuts
3. **Post-IPO companies account for the majority** of total layoffs at 564,932 — 7x more than any other stage
4. **The United States dominates globally** with 637,509 layoffs — nearly 10x India in second place
5. **2026 is on pace to exceed 2024** with 92,272 layoffs recorded in just the first 4 months
6. **The November 2022 spike** marks the beginning of the mass tech layoff wave, coinciding with Meta's 11,000 person reduction

## SQL Concepts Demonstrated
- Aggregations and GROUP BY
- Window functions (DENSE_RANK, SUM OVER, PARTITION BY)
- Common Table Expressions (CTEs)
- Nested CTEs for multi-step analysis
- Date formatting and time-series aggregation
- NULL handling and filtering

## How to Run
1. Download the dataset CSV from the Kaggle link above
2. Clone this repository and open the notebook in Jupyter
3. Place `layoffs.csv` in the same folder as the notebook
4. Run all cells in order
