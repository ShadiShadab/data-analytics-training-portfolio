# Nashville Housing Data Cleaning — SQL

**Type:** guided portfolio project based on a public tutorial and dataset · **Date:** 2022

[Cleaning Data.sql](Cleaning%20Data.sql) · data: [Nashville Housing Data for Data Cleaning.xlsx](Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx)

Cleaning a real-estate sales dataset in SQL Server so it is ready for analysis:

1. **Standardise dates:** convert the sale date to a `DATE` type.
2. **Fill missing property addresses:** self-join on `ParcelID` and `ISNULL` to copy the address from another record of the same parcel.
3. **Split addresses** into street, city and state using `SUBSTRING`/`CHARINDEX` and `PARSENAME`.
4. **Normalise values:** change `Y`/`N` to `Yes`/`No` in "Sold as Vacant" with `CASE`.
5. **Remove duplicates** with `ROW_NUMBER()` in a CTE.
6. **Drop unused columns.**

## Skills practised

SQL data cleaning · self-joins · string functions · `CASE` · window functions and CTEs
