# Seasonal Agriculture Performance Analysis

## VOIS AICTE Batch1 2026-2027 — Major Project

### Overview
This project analyzes seasonal agricultural performance using a dataset of 4,000 farm records across three Indian cropping seasons — Kharif, Rabi, and Zaid — spanning 8 states and 8 crop types. It investigates how environmental conditions, farming inputs, and economic outcomes vary by season, using data cleaning, exploratory data analysis, statistical hypothesis testing, and visualization to uncover meaningful seasonal patterns.

### Objective
To analyze agricultural data from different seasons and identify meaningful patterns, trends, relationships, and differences in agricultural performance, and to provide evidence-based recommendations for seasonal agricultural planning.

### Dataset
- 4,000 farm records
- 28 columns covering environmental conditions (rainfall, temperature, humidity, soil), farming inputs (fertilizer, pesticide, irrigation method, seed quality), and outcomes (yield, production, cost, revenue, profit, water efficiency)

### Key Analyses
- Data cleaning: missing value imputation, duplicate removal, outlier detection
- Univariate, bivariate, and multivariate analysis
- Correlation analysis between environmental factors and yield/profit
- Statistical testing: ANOVA (seasonal yield/profit differences), Chi-square (irrigation method vs. season)
- Crop-season and state-season pattern discovery via heatmaps

### Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (statistical testing)
- Jupyter Notebook (Google Colab)

### Key Findings
- Yield and profit differ statistically significantly across seasons
- Irrigation method choice is significantly associated with season
- Specific crop-season and state-season combinations consistently outperform others

### Files
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook
- `seasonal_agriculture_performance_dataset.csv` — dataset
- `output/` — generated charts

### Author
Abhishek Verma
