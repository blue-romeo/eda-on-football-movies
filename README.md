# eda-on-football-movies
Project Overview
This repository contains the code and analysis for an Exploratory Data Analysis (EDA) project on football movies. The goal of this project is to gain insights into the trends, patterns, and characteristics of football-themed movies.

## Data
Dataset: /kaggle/input/rotten-tomatoes-best-soccer-movies/critic_reviews.csv/critic_reviews.csv
Description:
Content
In the movies dataset each record represents a movie available on Rotten Tomatoes, with the URL used for the scraping, movie tile, description, genres, duration, director, actors, users' ratings, and critics' ratings.
In the critics dataset each record represents a critic review published on Rotten Tomatoes, with the URL used for the scraping, critic name, review publication, date, score, and content.

## EDA Steps
### imports and reading data
importing and reading the data in the notebook.

### Understanding the data
This involves finding out the dimensions of the data and cleaning.
### Feature Understanding
We do a deep dive into each feature to not only to understand them but also draw insights.

### Merging dataframes
We do this in order to find out the top 10 most reviewed  movies and the top 5 best ranked movies.




## Insights and Findings:

There are 16 columns and 2412 rows of data. Through data cleaning and feature engineering the columns of data were reduced to 12 and 1677 rows.
There were no duplicated rows. There are 555 top movie critics in the data a rank of the top 15 most active was made and visualized using bar graphs.

A rank of the top 10 most reviewed movies and the top 5 best ranked movies were made.

Tools and Libraries
Python: The primary programming language used for the analysis.
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib: For creating visualizations.
