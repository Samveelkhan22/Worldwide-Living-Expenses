# Global Cost of Living Analysis

This repository contains an in-depth analysis of the **Global Cost of Living**, merging data from multiple sources such as cost of living indices, country codes, and salary data. The analysis aims to understand and visualize key trends in cost of living across different cities and countries worldwide.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Key Features](#key-features)
- [Project Structure](#project-structure)

## Project Overview

This project analyzes global cost of living indices, data scientist salaries, and levels salary data by combining multiple datasets. It also involves standardizing country names, handling missing country codes, and visualizing the distribution of cost of living data.

### Objective

The main objectives of this project are:
- To clean and standardize country names across datasets.
- To visualize the distribution of the Cost of Living Index.
- To analyze salary data across different countries and regions.
- To handle missing or incomplete data and merge country codes into the final dataset.

## Data Sources

The datasets used in this analysis include:
1. **Cost of Living Data**: Contains the cost of living index for various cities worldwide.
2. **Country Codes Data**: Provides the ISO Alpha-2, Alpha-3, and numeric country codes.
3. **Data Scientist Salaries**: Salary data for data scientists across different countries.
4. **Levels FYI Salary Data**: Salaries for different levels of employees across companies.

## Key Features

- **Data Cleaning**: 
  - Standardizing country names to ensure consistency between datasets.
  - Handling missing country codes by mapping them to standard ISO codes.
  - Merging data from multiple sources.

- **Descriptive Statistics**:
  - Generating summary statistics for numerical columns, such as the Cost of Living Index.

- **Visualization**:
  - Creating histograms and KDE plots to visualize the distribution of the Cost of Living Index.
  
## Project Structure

```plaintext
├── cost_of_living.csv            # Cost of Living dataset
├── country_codes.xlsx            # ISO Country Codes dataset
├── ds_salaries.csv               # Data Scientist Salaries dataset
├── Levels_Fyi_Salary_Data.csv    # Levels FYI Salary dataset
├── scripts/                      # Python scripts for data cleaning and analysis
│   └── data_cleaning.py          # Script for cleaning and merging data
├── analysis.ipynb                # Jupyter notebook for data analysis
└── README.md                     # Project documentation
