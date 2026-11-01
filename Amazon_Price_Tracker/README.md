# Product Price Tracker — Python Web Data Collection

**Type:** guided project based on a public tutorial · **Date:** August 2022

[Amazon Web Scrapping project.ipynb](Amazon%20Web%20Scrapping%20project.ipynb)

A small Python script that reads a product page, extracts its title and price, and appends them with the date to a CSV file. It is designed to run once a day to build a price history, with an optional email alert when the price drops below a target.

## What it does

1. Requests the product page with `requests` (with browser-like headers) and parses it with BeautifulSoup.
2. Cleans the title and price strings.
3. Writes a header row once, then appends `Title, Price, Date` rows with `csv`.
4. `check_price()` wraps the steps; a `while True` loop with `time.sleep(86400)` runs it daily.
5. An optional `send_mail()` function sends an alert through SMTP. The credentials are placeholders and must be supplied by the user, never committed.

## Notes

- Retailer page structure changes often and many sites limit automated access; check the site's terms of use before running this. This notebook is a learning exercise, not a maintained tool.
- Some cells read the CSV from a local Windows path; change it to `Amazon.scrapping.csv` before running.

## Skills practised

HTTP requests · HTML parsing with BeautifulSoup · string cleaning · writing CSV files · scheduling a task in a loop · reading the result with pandas
