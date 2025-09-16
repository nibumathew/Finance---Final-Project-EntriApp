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

5.Derived metrics

6.Aggregation examples

7.Visualizations

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
# 5.Derived metrics

Creates Profit Margin % as (Profit / Sales) * 100 (and handles divide-by-zero / NaNs)

--------------------------------------------------------------------------------------------------
# 6. Aggregation examples

Aggregates Sales by Year & Segment

Groups Profit Margin % by Product

Computes country_wise_sales and country_profit aggregations (Sales & Profit by Country)

--------------------------------------------------------------------------------------------------
# 7. Visualizations

Profit Margin by Product — pie chart (shows relative profit contribution per product)

Units Sold by Country & Segment — grouped bar plot (helps find which country/segment
combination sells the most units)

Profit Margin % by Country — boxplot (shows distribution and spread across countries)

Sales vs Profit — scatterplot (check linear relationship; outliers)

Profit by Country — horizontal bar chart (rank countries by profit)

Total Sales Trend — line chart over time

Total Profit Trend — line chart over time

Distribution of Profit Margins — histogram with mean

Correlation Heatmap — heatmap of correlations between numeric columns (Units Sold, Prices,
Sales, COGS, Profit, Profit Margin %)

----------------------------------------------------------------------------------------------------
# Key Findings - Visuals

<img width="485" height="528" alt="image" src="https://github.com/user-attachments/assets/44e7ed2d-7536-4435-975b-30fe5e0cb6d6" />

<img width="840" height="548" alt="image" src="https://github.com/user-attachments/assets/0e7faf9f-8797-4a16-b91d-e6513f6b7d27" />

<img width="977" height="545" alt="image" src="https://github.com/user-attachments/assets/3160f266-0251-4ae2-9ebe-fcc64373df37" />




