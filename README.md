# Project 3 – Data Science Skills

**Course:** DATA 607 – Data Acquisition and Management  
**Author:** Akash Sourav

## Overview

This project explores which data science skills are most valued by employers using a dataset of 10,345 job postings. The analysis focuses on Python, SQL, Machine Learning, Deep Learning, and Cloud Computing.

## Dataset

**Source:** [AI and Data Science Job Market Dataset (2020–2026)](https://github.com/Musawir456/ai-and-data-science-job-market-dataset-2020-2026)

The dataset includes job titles, industries, locations, technical skills, and salary information.

## Tools Used

- R, tidyverse, ggplot2
- SQLite, DBI, RSQLite
- Quarto

## Methodology

The data is imported into R, cleaned, and organized into three normalized SQLite tables: `jobs`, `skills`, and `job_skills`. The analysis examines skill frequencies, compares requirements across job categories, and checks for missing values, duplicates, and potential outliers.

## Reproducibility

1. Clone or download this repository.
2. Install the required R packages:

```r
install.packages(c("tidyverse", "DBI", "RSQLite", "knitr"))
```

3. Open `project3.qmd` in RStudio and click **Render**.

The SQLite database is generated automatically from the CSV file stored in the `data/` folder.

## Conclusion

This project uses job-posting data to explore employer demand for technical skills. Skill frequency provides an indication of demand but does not necessarily represent the overall value of a skill.

## AI Assistance

OpenAI ChatGPT (GPT-6) assisted with coding, troubleshooting, and documentation.
