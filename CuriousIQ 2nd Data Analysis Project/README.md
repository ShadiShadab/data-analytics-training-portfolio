# WorldWideImporters Demand-Forecasting Inputs — CuriousIQ Advanced Data Analysis Project

**Course:** CuriousIQ Diploma in Data Analysis · **Date:** June 2022 · **Type:** individual business case project

## Business brief

A Data Science Manager wanted to build a **sales demand-forecasting model** but did not know which data in the WorldWideImporters database would be useful ([brief](CuriousIQ_Advanced%20Data%20Analysis%20Project.pdf)). The task: identify useful tables, analyse them statistically, visualise the findings and, ideally, build an initial regression model.

## What I did

1. **Explored the database in SQL** (SQL Server): orders, order lines, invoices, customer transactions, customers and categories, cities, states and countries. Built aggregate views such as sales per day, per customer, per month and year, per stock item, per customer category, and per city/state ([Final_Project_Shadi.sql](Final_Project_Shadi.sql)).
2. **Exported a combined dataset** of 225,797 rows and 11 columns (customer, category, stock item, state, city, population, total sales, line profit, year, month, transaction date) ([Sales prediction.csv](Sales%20prediction.csv)).
3. **Analysed it in Python** ([Final_Project_Shadi1.ipynb](Final_Project_Shadi1.ipynb)): missing-value check, sales and profit by state and year, customer categories, a correlation matrix across all features, monthly sales and profit trends by year, and monthly resampling of profit.

## Observations from the notebook

- No missing values in the extracted dataset.
- Colorado and Nebraska had the highest yearly line profit (2014–2015).
- Total sales and line profit were moderately correlated (r ≈ 0.47); no single variable was strongly correlated with sales.
- 2016 contains only part of a year, which shows up as a drop in yearly profit and should be handled before any forecasting.

The notebook stops at exploratory analysis; the optional regression model was not built.

## Skills practised

SQL across many related tables · feature identification for a model · pandas, seaborn and Plotly · correlation analysis · time-series resampling

## Files

| File | Content |
|---|---|
| `CuriousIQ_Advanced Data Analysis Project.pdf` | Course brief |
| `Final_Project_Shadi.sql` | SQL extraction and aggregation |
| `Sales prediction.csv` | Extracted dataset |
| `Final_Project_Shadi1.ipynb` | Python analysis |
