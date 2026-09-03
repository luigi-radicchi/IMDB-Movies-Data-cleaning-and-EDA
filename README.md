# IMDB Data Cleaning & Exploratory Data Analysis

This project focuses on cleaning and analyzing an intentionally corrupted IMDB dataset.

The goal was to identify and resolve data quality issues such as invalid numeric values, inconsistent date formats, encoding problems and missing values before performing an exploratory data analysis using Pandas and Seaborn.

## Dataset
The dataset contains information about 100 highly rated movies, including:

- Title
- Release Date
- Director
- Country
- Duration
- Income
- Votes
- Score
- Content Rating

## Data Cleaning

The dataset contained several intentionally introduced issues:

- Invalid numeric values
- Inconsistent date formats
- Country naming inconsistencies
- Character encoding errors
- Missing values
- Incorrect income records
 
The following techniques were applied:
 
- String cleaning with 
- Datatype conversion
- Date standardization
- Category normalization
- Manual validation of corrupted income values

Many validations have been done after data cleaning, below two examples with sns.boxplot for the votes and sns.histplot for the income.

<p align="center">
<img src="images/03_Votes_boxplot" width="900">

<p align="center">
<img src="images/10_income_distribution_adjusted.png" width="900">

## Exploratory Data Analysis (EDA)

Examples of the insights found:

### Top countries by movie
<p align="center">
<img src="images/11_top_countries_by_movie.png" width="900">

### Top directors by average score
<p align="center">
<img src="images/15_top_directors_by_avg_score.png" width="900">

### Correlation between votes and score
<p align="center">
<img src="images/17_corr_votes_score.png width="900">

### Distribution of income per genre
<p align="center">
<img src="images/21_distribution_income_per_genre.png" width="900">

### Correlation matrix bewtween numerical entries
<p align="center">
<img src="images/16_corr_matrix.png" width="900">
