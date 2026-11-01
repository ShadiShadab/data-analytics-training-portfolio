# COVID-19 Deaths, Infections and Vaccinations — SQL, Tableau and Python

**Type:** guided portfolio project based on public tutorials and public data · **Date:** 2022

## SQL exploration and Tableau dashboard

[Covid_Project_Portfolio.sql](Covid_Project_Portfolio.sql) · data: [covid-deaths.xlsx](covid-deaths.xlsx), [covid-vaccination.xlsx](covid-vaccination.xlsx) (Our World in Data extract)

SQL Server queries exploring:
- likelihood of dying after infection over time (with Greece as the example country),
- infection rate relative to population, highest infection and death counts by country and continent,
- global daily and total figures,
- rolling vaccination totals using a join, a CTE, a temporary table and a view prepared for visualisation.

The results were visualised in a Tableau dashboard:

![COVID-19 Tableau dashboard](Covid-19_Tableau.png)

## Python visualisation

[COVID_19 Data Visualization Using Python.ipynb](COVID_19%20Data%20Visualization%20Using%20Python.ipynb) · data read directly from the public [datasets/covid-19](https://github.com/datasets/covid-19) repository

Plotly charts of global spread and deaths, maximum daily infection rate per country (first derivative of confirmed cases), and the effect of Italy's national lockdown on the infection rate and active cases.

## Skills practised

SQL joins, CTEs, window functions, temporary tables and views · Tableau dashboards · Plotly choropleth and line charts · deriving rates from cumulative data

## Running

```bash
pip install pandas plotly jupyter
jupyter notebook
```
The SQL script uses Microsoft SQL Server (T-SQL) syntax, with the two Excel files imported as tables.
