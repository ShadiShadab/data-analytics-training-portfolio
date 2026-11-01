# 2019 Electronics Store Sales Analysis — pandas

**Type:** guided project on a public practice dataset · **Date:** 2022

[Sales Analysi_Data cleaning and data exploration.ipynb](Sales%20Analysi_Data%20cleaning%20and%20data%20exploration.ipynb) · data: 12 monthly CSV files (`Sales_January_2019.csv` … `Sales_December_2019.csv`)

## Business questions

1. Which month had the best sales, and how much was earned?
2. Which city sold the most?
3. When should advertisements be shown to maximise purchases?
4. Which products are most often sold together?
5. Which product sold the most, and why?

## What I did

- **Merged** the 12 monthly files into one dataset.
- **Cleaned** it: dropped empty rows, removed repeated header rows, converted quantity and price to numbers.
- **Added columns:** month, city (with state), sales value, order hour and minute.
- **Analysed** sales by month and city, orders by hour of day, product pairs bought in the same order (`itertools.combinations` + `Counter`), and quantity ordered against average price.

## Findings

- The most common product pairs were iPhone with Lightning cable, and Google Phone with USB-C cable.
- A twin-axis chart of quantity ordered against average price shows that low-priced items sell in the highest quantities.
- Month, city and hour-of-day charts in the notebook show where and when sales peak.

## Skills practised

Combining files · data cleaning and type conversion · feature creation with `apply` · `groupby` aggregation · basket analysis · matplotlib

## Running

Run the notebook from the `Python/` folder (it reads `./Sales_Data/`). It saves a combined `all_data.csv`; one cell reads that file from a local Windows path, so change the path to `all_data.csv` before running.
