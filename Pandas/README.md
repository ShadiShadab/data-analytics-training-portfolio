# pandas for Data Analysis — 5-Part Practice Series

**Type:** self-study practice notebooks following a pandas course · **Date:** 2022

Five notebooks working through pandas from the basics to text data, each with its practice dataset in this folder.

| Part | Notebook | Topics | Dataset |
|---|---|---|---|
| 1 | [Series](Pandas%20Data%20Analysis%20part%201_Series.ipynb) | Creating Series, reading a CSV into a Series, basic operations | S&P 500 prices |
| 2 | [DataFrame](Pandas%20for%20Data%20Analysis%20Part%202_DataFrame.ipynb) | Creating DataFrames, indexing, selecting, reading CSV with an index column | Employee records |
| 3 | [DataFrames with functions](Pandas%20for%20Data%20Analysis%20Part%203_DATAFRAMES%20WITH%20FUNCTIONS.ipynb) | Applying functions, filtering, concatenation, multi-indexing, merging | Employee records |
| 4 | [Import and explore a dataset](Pandas%20for%20Data%20Analysis%20Part%204_IMPORT%20AND%20EXPLORE%20DATASET.ipynb) | Reading Excel, `groupby`, multi-indexed DataFrames, date and time handling | Sales data (Excel) |
| 5 | [Data exploration](Pandas%20for%20Data%20Analysis_DATA%20EXPLORATION_Part%205.ipynb) | Text data: case operations, filtering positive and negative ratings, removing punctuation and stopwords, word clouds | Amazon Echo customer reviews |

## Skills practised

pandas Series and DataFrames · filtering, grouping, merging · multi-indexing · dates and times · basic text cleaning

## Running

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook
```
Part 5 also uses `nltk` and `wordcloud`.
