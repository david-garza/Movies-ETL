# Movies ETL

## Purpose

This exercise demonstrates my ability perform ETL operations on various types of data then load it into a SQL database.

## Process

### Data
The data source is a web scrappings from Wikipedia and CSV files from [Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/)

#### Wiki
Wiki data was parsed, columns removed / merged, and duplicate rows deleted.

#### Kaggle 
Kaggle movie data required some parsing. The kaggle ratings data was pivoted to show count for each rating per movie ID.

### Merge
All three transformed data sets were merged on IMBd ID. Duplicated rows were dropped.

### Load
Data was loaded to a SQL database.
