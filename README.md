# Data Analytics Training Portfolio

Coursework and guided projects from my data analytics training (2022–2025): SQL, Python/pandas, Excel, Tableau and business-oriented analysis.

![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Type](https://img.shields.io/badge/type-learning%20portfolio-lightgrey)

This repository documents **how I built my analytics foundation**. It is a learning record, not a set of original research projects. My applied, end-to-end projects are:

- [SatNOGS Observation Success Prediction](https://github.com/ShadiShadab/satnogs-observation-success-prediction): ML on real satellite ground-station data
- [E-commerce Returns Prediction](https://github.com/ShadiShadab/ecommerce-returns-prediction): ASOS returns modelling, team project

---

## Contents

### CuriousIQ Diploma in Data Analysis: business case projects

Case studies on fictional company databases, answering briefs from a business stakeholder.

| Project | Business question | Tools | Files |
|---|---|---|---|
| AdventureWorks sales analysis | Product associations, geographic focus, slow-moving products, best-customer rewards | SQL, Excel, PowerPoint | [`CuriousIQ 1st Data Analysis Project/`](CuriousIQ%201st%20Data%20Analysis%20Project/) |
| WorldWideImporters demand-forecasting inputs | Which data and variables should feed a sales-forecasting model? | SQL, Python (pandas, seaborn), statistics | [`CuriousIQ 2nd Data Analysis Project/`](CuriousIQ%202nd%20Data%20Analysis%20Project/) |

### IBM Data Analyst Professional Certificate: coursework

| Project | Content | Files |
|---|---|---|
| Capstone: 2019 Stack Overflow Developer Survey | Data collection, wrangling, EDA, dashboard and findings presentation | [`IBM_Capstone_Project.pdf`](IBM_Projects/IBM_Capstone_Project.pdf) |
| House sales in King County, USA | House-price regression (linear, polynomial, ridge) | [`IBM_Projects/`](IBM_Projects/) |
| Databases and SQL for Data Science | SQL queries against public datasets from Python | [`IBM_Projects/`](IBM_Projects/) |
| Python Project for Data Science | Tesla and GameStop stock and revenue data extraction and visualisation | [`IBM_Projects/`](IBM_Projects/) |
| Interactive dashboard (peer-graded) | Plotly Dash app | [`5_Peer_Graded_Assignment_Questions.py`](IBM_Projects/5_Peer_Graded_Assignment_Questions.py) |

### pandas fundamentals (5-part series)

Series, DataFrames, functions, importing and exploring data. Notebooks with their practice datasets are in [`Pandas/`](Pandas/).

### Guided projects (based on public tutorials and datasets)

| Project | Skills practised | Files |
|---|---|---|
| COVID-19 deaths and vaccinations | SQL joins, CTEs, window functions, Tableau dashboard | [`Covid_19_DataAnalysis/`](Covid_19_DataAnalysis/) |
| COVID-19 data visualisation | pandas, Plotly | [`Covid_19_DataAnalysis/`](Covid_19_DataAnalysis/) |
| Nashville housing data cleaning | SQL data cleaning (standardising, splitting, de-duplicating) | [`SQL/`](SQL/) |
| 2019 monthly sales analysis | Combining files, cleaning, answering business questions with pandas | [`Python/Sales_Data/`](Python/Sales_Data/) |
| Movie industry correlation | Correlation analysis, seaborn | [`Python/`](Python/) |
| Product price tracker | Python requests and BeautifulSoup for web data collection | [`Amazon Web Scrapping project.ipynb`](Amazon%20Web%20Scrapping%20project.ipynb) |

### Early experiments

| Notebook | Notes |
|---|---|
| [`Python/ASOS_modeling_analysis.ipynb`](Python/ASOS_modeling_analysis.ipynb) | First Random Forest experiment on ASOS returns data (Colab). It was developed further in [ecommerce-returns-prediction](https://github.com/ShadiShadab/ecommerce-returns-prediction). |

![COVID-19 Tableau dashboard](Covid_19_DataAnalysis/Covid-19_Tableau.png)

---

## Running the notebooks

Most notebooks need only `pandas`, `numpy`, `matplotlib`, `seaborn` and `jupyter`. The COVID visualisation uses `plotly`, and the price tracker uses `requests` and `beautifulsoup4`. Datasets are included next to each notebook, except where a notebook reads directly from a public URL.

```bash
pip install pandas numpy matplotlib seaborn plotly requests beautifulsoup4 jupyter
jupyter notebook
```

Most SQL files use Microsoft SQL Server (T-SQL) syntax.

---

Author: [Shadi Shadabshoar](https://www.linkedin.com/in/shadi-shadabshoar/)
