# Python Analysis Exercises

| Project | Description |
|---|---|
| [Sales_Data/](Sales_Data/) | 2019 monthly sales analysis (separate README) |
| [Correlation in Python.ipynb](Correlation%20in%20Python.ipynb) | Movie industry correlation analysis |
| [ASOS_modeling_analysis.ipynb](ASOS_modeling_analysis.ipynb) | Early ASOS product-returns experiment |

## Movie industry correlation analysis

**Type:** guided project on a public dataset · data: [movies.csv](movies.csv) (about 7,600 films)

Which factors relate most to a film's gross revenue? The notebook checks missing data (budget is missing for 28% of films), drops incomplete rows, fixes types, extracts the release year, and builds correlation matrices for numeric features and for category-encoded features.

**Result:** budget (r ≈ 0.74) and number of votes (r ≈ 0.61) correlate most strongly with gross revenue.

**Skills:** data cleaning, type conversion, correlation analysis, seaborn heatmaps and scatter plots.

## ASOS product-returns experiment

An early Google Colab experiment, made while preparing for the team project [ecommerce-returns-prediction](https://github.com/ShadiShadab/ecommerce-returns-prediction). It analyses return rates by shipping country, product type and brand, and tries a first classification model. The maintained analysis and final models are in that repository.

## Running

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```
