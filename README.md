# Gold in Different Economic Conditions

A data analysis project examining how gold behaves under different macroeconomic conditions, with a focus on inflation, GDP growth, and comparisons with silver and copper.

---

## Overview

Gold is often described as a hedge against inflation and economic uncertainty, but its actual behavior can vary across different market environments. This project investigates how gold performs under changing macroeconomic conditions by combining annual GDP, inflation, and historical metal price data into a unified time-series dataset.

Using **Python** and **SQL**, I built a workflow for data collection, cleaning, validation, integration, feature engineering, and analysis. I then applied **exploratory data analysis (EDA)**, **descriptive statistics**, **subgroup comparisons**, and **regression modeling** to evaluate how gold behaves across different economic regimes.

This project was completed as part of a data analysis course and demonstrates practical skills in **data wrangling, time-series analysis, statistical reasoning, and data storytelling**.

---

## Research Question

How does gold perform across different economic conditions, especially during periods of:

- high vs. low inflation
- high vs. low GDP growth
- changing relationships with other metals such as silver and copper

---

## Objectives

- Build a clean, analysis-ready dataset from macroeconomic and commodity price sources
- Examine how gold returns vary across inflation and growth environments
- Compare gold’s behavior with silver and copper
- Identify the variables most strongly associated with gold returns

---

## Tools and Skills

### Tools
- Python
- SQL
- Jupyter Notebook
- API-based data collection

### Python Libraries
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn

### Methods
- Data cleaning and validation
- Feature engineering
- Exploratory data analysis (EDA)
- Descriptive statistics
- Correlation analysis
- Subgroup comparisons
- Regression analysis
- Time-series analysis

---

## Dataset

This project combines annual data for:

- Real GDP
- Inflation
- Gold prices
- Silver prices
- Copper prices

The datasets were collected, cleaned, aligned by year, and merged into a single analytical table for downstream analysis.

---

## Feature Engineering

To better capture macroeconomic and market relationships, I created several derived variables, including:

- GDP growth
- Inflation change
- Gold return / percentage change
- Silver return
- Copper return
- Gold-inflation gap
- Gold-GDP gap

These features were used to compare gold’s performance against broader economic conditions and against other metals.

---

## Workflow

### 1. Data Collection
- Pulled macroeconomic and commodity data from API and historical sources
- Imported and organized data into analysis-ready tables

### 2. Data Cleaning and Preparation
- Standardized variable types and date formats
- Checked for duplicates and missing values
- Harmonized time frequency across datasets
- Merged data into a single annual time-series dataset

### 3. Exploratory Data Analysis
- Visualized long-run trends in GDP, inflation, gold, silver, and copper
- Examined summary statistics and correlations
- Compared gold performance under high vs. low inflation and GDP growth conditions

### 4. Statistical Analysis
- Conducted subgroup comparisons across macroeconomic regimes
- Used regression modeling to test relationships between gold returns and macroeconomic/market variables
- Compared gold’s behavior with silver and copper

---

## Key Findings

- Gold performed best in **high-inflation, low-growth environments**
- Gold tracked **silver** more closely than **copper**
- Inflation and silver returns were more strongly associated with gold returns than broader growth indicators
- The findings support gold’s role as a relatively defensive asset during inflationary and weaker-growth periods

---

## Why This Project Matters

This project moves beyond the general claim that “gold is a hedge” by testing how gold behaves across specific economic conditions. It helps answer:

- when gold is most likely to outperform
- whether gold behaves more like a defensive asset or a commodity
- how gold compares with other metals under different macroeconomic regimes

It also demonstrates an end-to-end data analysis workflow, from raw data collection to analytical conclusions.

---

## Deliverables

- Cleaned and integrated macroeconomic dataset
- Python notebook for analysis
- SQL queries for data preparation and analysis
- Data visualizations
- Final presentation deck
