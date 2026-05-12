# Investigate a Dataset: TMDb Movie Analysis

> Udacity Data Analyst Nanodegree — Project 1

## Overview

This project investigates the TMDb (The Movie Database) dataset containing information about **10,878 movies**, including user ratings, revenue, budget, genres, and more. The analysis explores trends in the movie industry through three research questions.

## Research Questions

1. How is adjusted profit distributed across the movies with complete financial data?
2. Do higher adjusted budgets tend to relate to higher adjusted profits?
3. How do popularity, vote count, and vote average relate to adjusted profit?

## Key Findings

- Adjusted profit varied widely across movies, with a few major blockbuster films pulling the average profit much higher than the median profit.
- About 72% of movies in the cleaned profit dataset had a positive adjusted profit.
- Higher adjusted budgets were generally associated with higher adjusted profits, but a higher budget did not guarantee profitability.
- Movies in the very high budget group had the highest median adjusted profit and the highest profitable rate.
- Popularity and vote count had stronger positive relationships with adjusted profit than vote average.
- The strongest variables associated with higher adjusted profit were adjusted budget, popularity, and vote count.

## Files

| File | Description |
|------|-------------|
| `Investigate_a_Dataset_TMDb.ipynb` | Jupyter Notebook with full analysis |
| `Investigate_a_Dataset_TMDb.html` | HTML export for easy viewing |
| `tmdb-movies.csv` | TMDb dataset (10,878 movies) |

## Tech Stack

- Python 3, NumPy, pandas, Matplotlib, Seaborn

## Limitations

- Many budget and revenue values were listed as zero, likely meaning missing data, so those rows were removed from profit analysis. This reduced the dataset from 10,866 to 3,854 movies and may create bias.
- The profit calculation is only an estimate because the dataset does not include marketing, distribution, streaming, licensing, or international revenue details.
- TMDb popularity scores may reflect activity on the TMDb platform, not overall audience popularity across all countries or time periods.
- The analysis is exploratory, so the findings show patterns and correlations, not proven cause-and-effect relationships.
