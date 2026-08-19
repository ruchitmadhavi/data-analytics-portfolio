# Cookie Cats A/B Test Analysis

## Overview

This project analyzes an A/B test from the mobile game **Cookie Cats** to understand how the placement of an in-game gate affects player engagement and retention.

The dataset contains player-level information from two test groups, where players were exposed to different gate placements.

## Objective

The main objective of this analysis is to compare player behavior between the two test groups and determine whether gate placement has an impact on player retention and engagement.

## Dataset

The dataset contains information about:

* Player ID
* Version / A/B test group
* Number of game rounds played
* 1-day retention
* 7-day retention

## Data Source

The dataset used in this project is the **Cookie Cats Mobile Games A/B Testing dataset**, originally provided through DataCamp and publicly available through Kaggle.

The dataset contains A/B test results from **90,189 players** and compares two groups:

* `gate_30`: First gate placed at level 30
* `gate_40`: First gate placed at level 40

The analysis focuses on player engagement and retention following the change in gate placement.

**Source:** [Kaggle - Mobile Games A/B Testing: Cookie Cats](https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats)

**Original source:** DataCamp

## Analysis Process

The analysis followed these steps:

1. Loaded and inspected the raw dataset.
2. Checked the data for missing values and inconsistencies.
3. Cleaned and prepared the dataset for analysis.
4. Created player activity categories based on the number of rounds played.
5. Calculated key performance indicators (KPIs).
6. Compared player behavior between the A/B test groups.
7. Created visualizations to identify patterns and differences.
8. Built an interactive Tableau dashboard to communicate the results.

## KPIs

The analysis focused on the following key performance indicators:

* Total Players
* Average Rounds Played
* 1-Day Retention Rate
* 7-Day Retention Rate
* Player Distribution by Rounds Played
* Retention by A/B Test Group

## Tools Used

* **Google Sheets** for data cleaning, transformation, categorization, and KPI calculations
* **Tableau** for data visualization and dashboard development

## Project Files

| File                       | Description                  |
| -------------------------- | ---------------------------- |
| `cookie_cats_raw_data.csv` | Original dataset             |
| `cookie_cats_cleaned.xlsx` | Cleaned and prepared dataset |
| `dashboard.twb`            | Tableau workbook             |
| `README.md`                | Project documentation        |

## Dashboard

The Tableau dashboard presents the key KPIs and visualizations used to compare player activity and retention between the A/B test groups.

## Key Findings

The analysis compares the two gate-placement groups across player engagement and retention metrics.

Specific findings from the analysis will be documented here based on the final KPI and dashboard results.

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from raw data preparation and KPI development to exploratory analysis and dashboard creation.

The analysis provides a structured comparison of player engagement and retention across the A/B test groups and demonstrates how data visualization can be used to communicate findings from an experiment.

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* KPI Development
* A/B Test Analysis
* Data Categorization
* Data Visualization
* Dashboard Development
