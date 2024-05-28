# Investigate a Dataset - TMDB 5000 Movie Dataset

## Table of Contents
1. Introduction
2. Data Wrangling
3. Exploratory Data Analysis
4. Conclusions

## Introduction

### Dataset Description
This dataset contains data on several thousand movies, including plot, cast, crew, budget, and revenues. It aims to predict the success of a movie before its release. The dataset consists of two related tables: `tmdb_5000_movies` and `tmdb_5000_credits`.

### Questions for Analysis
1. Which factors contribute to higher ratings and revenues?
2. Which release months get the highest ratings and revenues?

## Data Wrangling
- Loaded and merged datasets.
- Handled missing data and optimized data types.

## Exploratory Data Analysis
- Investigated relationships between budget, revenue, ratings, and vote counts.
- Analyzed the impact of release month on ratings and revenues.

## Conclusions
1. Most movie ratings lie between 5 and 7.
2. Weak positive relation between vote count and average rating.
3. Strong relation between budget and revenue.
4. Movies released in May, June, and November generate the highest revenue.

### Limitations
- Missing data in several columns.
- Correlation does not imply causation.

### Additional Research
- Analyze the impact of different genres on revenue and ratings.
- Investigate how movie popularity affects ratings.
