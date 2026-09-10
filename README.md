# Data Science Salaries Analysis

## Overview

This project explores a dataset of data science salaries from 2020 to 2023. The goal is to uncover patterns in compensation based on experience level, employment type, remote ratio, company size, location, and job title.

The analysis includes data cleaning, feature engineering, exploratory data analysis, visualization, correlation analysis, and trend analysis using Python.

## Dataset

- File: `ds_salaries.csv`
- Rows: 3,755
- Columns: 11
- Key fields:
  - `work_year`
  - `experience_level`
  - `employment_type`
  - `job_title`
  - `salary_in_usd`
  - `employee_residence`
  - `remote_ratio`
  - `company_location`
  - `company_size`

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

## Workflow

1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Removed 1,171 duplicate rows.
4. Performed feature engineering:
   - `is_same_country`
   - `experience_year`
   - `start_year`
5. Conducted exploratory data analysis:
   - Categorical and structural analysis
   - Salary vs remote work
   - Experience and career progression
   - Company size and location analysis
   - Job title analysis and word cloud
   - Correlation heatmap
   - Salary trends over time
6. Extracted key insights and visualizations.

## Key Insights

- Full-time roles dominate the dataset, especially Senior and Mid-level positions.
- The United States has the highest number of records, with medium-sized companies being the most common.
- Cross-border employees have a much higher remote ratio than same-country employees.
- Medium-sized companies pay the highest average salary, followed by large companies.
- Experience level is the strongest predictor of salary.
- Remote ratio has only a weak correlation with salary.
- Salaries increased from 2020 to 2023, with full-time roles showing the steepest growth.
- Leadership and specialized roles, such as Data Science Tech Lead and Cloud Data Architect, are the highest paid.
- More experienced workers are more likely to be fully remote.
- Israel, Malaysia, and Puerto Rico appear with high average salaries, though small sample sizes may affect these results.

## Files

- `ds_salaries_analysis.ipynb` — main analysis notebook
- `ds_salaries.csv` — dataset
- `requirements.txt` — dependencies
- `README.md` — project summary

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
