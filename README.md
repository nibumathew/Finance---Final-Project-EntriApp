# Final Project — Finance Data Visualization
Short description :

A step-by-step exploratory data analysis and visualization notebook for a finance dataset
( Financials.csv ). This repository contains a Jupyter Notebook ( Final Project Finance -
Visualization.ipynb ) that loads the dataset, cleans and prepares the data, computes derived metrics
(for example Profit Margin %), and generates a set of visualizations to help answer business questions about
sales, profit and product / country performance.

--------------------------------------------------------------------------------------------------------------

# Table of contents

1.Project Overview

2.Dataset

3.Data Loading and Initial Overview

4.Data Pre-processing

Visualizations produced

Key observations (from the notebook)

Suggested improvements / next steps

Recommended repository structure

Requirements

License & credits

-----------------------------------------------------------------------------------------------------

# 1. Project overview

This project demonstrates exploratory data analysis (EDA) and visualization techniques applied to a financial
dataset. The notebook is intended to be readable by data analysts and product/finance stakeholders. 

It focuses on:

Data loading and an initial overview

Cleaning and type conversion for numeric/currency columns

Creating derived metrics (e.g. Profit Margin %)

Aggregations (sales / profit by year, segment, product, country)

Multiple visualizations (time series, bar charts, boxplots, scatterplots, pie charts, histograms,
heatmap)

---------------------------------------------------------------------------------------------------------

# 2. Dataset

Financial.csv (Uncleaned Dataset)

Financial_cleaned.csv (Cleaned Dataset)

Final Project Finance - Visualization.ipynb

-------------------------------------------------------------------------------------------------------
# 3.Data Loading and Initial Overview

Imports: pandas , numpy , matplotlib.pyplot , seaborn

Reads Financials.csv into df_financials

Displays .shape , .head() , .info() and basic checks

------------------------------------------------------------------------------------------------------
# 4.Data Pre-processing

Cleans numeric/currency columns by removing spaces, $ signs and commas

Converts columns to numeric using pd.to_numeric(..., errors='coerce')

Fills missing values for Discounts , Profit and Profit Margin % (with 0 in the notebook)

Converts Date to datetime and (where present) uses Year for aggregation

---------------------------------------------------------------------------------------------------

