# Gold in Different Economic Conditions

## Overview
This project analyzes how **gold behaves under different macroeconomic conditions**, with a particular focus on **inflation** and **GDP growth**. Using **Python** and **SQL**, I built a workflow to collect, clean, validate, and merge macroeconomic and historical metal price data into an analysis-ready time-series dataset. :contentReference[oaicite:0]{index=0}

The project compares gold with **silver** and **copper** to better understand whether gold behaves more like a defensive asset during economic uncertainty. The analysis includes **feature engineering, exploratory data analysis (EDA), subgroup comparisons, and regression modeling**.

---

## Research Question
How does gold perform across different economic conditions, especially during periods of:

- **high vs. low inflation**
- **high vs. low GDP growth**
- changing relationships with other metals such as **silver** and **copper**

---

## Objectives
- Build a clean, integrated dataset from macroeconomic and commodity price sources
- Examine how gold returns change under different inflation and growth environments
- Compare gold’s behavior with silver and copper
- Identify which macroeconomic and market variables are most strongly associated with gold returns

---

## Tools and Methods
### Tools
- **Python**
  - pandas
  - NumPy
  - matplotlib
- **SQL**
- API-based data collection

### Methods
- Data cleaning and validation
- Time-series integration
- Feature engineering
- Exploratory data analysis (EDA)
- Descriptive statistics
- Correlation analysis
- Subgroup comparisons
- Regression modeling

---

## Dataset
The analysis combines:

- **Real GDP**
- **Inflation**
- **Gold prices**
- **Silver prices**
- **Copper prices**

These data were cleaned, aligned, and merged into an annual time-series dataset for analysis. :contentReference[oaicite:3]{index=3}

---

## Feature Engineering
Key engineered variables include:

- GDP growth
- Inflation change
- Gold return / percentage change
- Silver return
- Copper return
- Gold-inflation gap
- Gold-GDP gap

These features were created to better evaluate how gold behaves relative to broader macroeconomic conditions and other metals. :contentReference[oaicite:4]{index=4}

---

## Analysis
The project included:

1. **Data preparation**
   - Pulled and cleaned macroeconomic and metal price data
   - Validated missing values, duplicates, and variable formats
   - Merged all datasets into a unified analytical table

2. **Exploratory data analysis**
   - Visualized long-run trends in gold, inflation, GDP growth, and metal prices
   - Examined correlations between gold and key macroeconomic variables
   - Compared gold performance across inflation and growth regimes

3. **Comparative analysis**
   - Evaluated whether gold tracked silver or copper more closely
   - Compared gold returns under high- vs. low-inflation environments
   - Compared gold returns under high- vs. low-growth environments

4. **Regression modeling**
   - Tested how inflation, GDP growth, and other metal returns relate to gold returns
   - Evaluated which predictors were most consistently associated with gold performance :contentReference[oaicite:5]{index=5}

---

## Key Findings
- Gold performed best during **high-inflation, low-growth environments**. :contentReference[oaicite:6]{index=6}
- Gold tracked **silver** more closely than **copper**, suggesting stronger alignment with silver market dynamics. :contentReference[oaicite:7]{index=7}
- Inflation and silver returns emerged as stronger indicators of gold returns than broader economic growth measures in the combined analysis. :contentReference[oaicite:8]{index=8}
- The results support the idea that gold can serve as a relatively defensive asset during periods of inflationary pressure and weaker macroeconomic conditions. :contentReference[oaicite:9]{index=9}

---

## Why This Project Matters
Gold is often discussed as a hedge against inflation or uncertainty, but this project takes a more data-driven approach by testing that claim across multiple economic conditions. The findings help clarify:

- when gold is most likely to outperform
- how gold behaves relative to other metals
- which indicators may be most useful for understanding gold’s market behavior

This project also demonstrates practical skills in **data engineering, time-series analysis, statistical reasoning, and data storytelling**.

---

## Repository Structure
```text
.
├── data/                  # raw and cleaned datasets
├── notebooks/             # analysis notebooks
├── sql/                   # SQL queries used for data preparation/analysis
├── figures/               # exported charts and visuals
├── slides/                # presentation materials
└── README.md
