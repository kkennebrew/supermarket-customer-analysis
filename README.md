# Supermarket Customer Behaviour — Preliminary Data Analysis

A comprehensive exploratory data analysis (EDA) of a supermarket customer dataset, investigating shopping behaviour, customer satisfaction, and demographic patterns across store locations.

## Overview

This preliminary analysis prepares a real-world supermarket dataset for downstream modelling. It covers data familiarisation, multi-stage cleaning, outlier handling, and visual EDA across customer demographics, satisfaction scores, basket composition, and queue wait times.

## Key findings

- Satisfaction scores cluster toward the middle — very high and very low ratings are rare, suggesting a consistent but unremarkable customer experience
- Queue wait time shows a moderate negative correlation with satisfaction; it is the strongest numeric predictor in the dataset
- Customers on a "top-up" shopping mission spend significantly less time in store than those on a "full shop" mission
- Store location is associated with meaningful differences in average household income and self-checkout adoption rates

## Tools and technologies

| Tool | Purpose |
|---|---|
| Python | Full analysis pipeline |
| pandas | Data cleaning, type coercion, feature extraction |
| difflib | Fuzzy string matching for city and category standardisation |
| Matplotlib / Seaborn | EDA visualisations |
| Jupyter Notebook | Analysis environment |

## Files

| File | Description |
|---|---|
| `Preliminary_Analysis.ipynb` | Full analysis notebook |
| `SupermarketEvaluation.csv` | Raw dataset |
| `Preliminary Data Analysis Report.pdf` | Written report with full methodology |

## Running the notebook

```bash
pip install pandas matplotlib seaborn
jupyter notebook Preliminary_Analysis.ipynb
```

---
*Data Mining module — Coursework 1, 2025–26.*
