

## Project Overview

This project analyzes U.S. petroleum import data using the U.S. Energy Information Administration (EIA) API. The goal is to understand how import patterns evolve over time, which countries dominate supply, and how stable or volatile these imports are.

The analysis follows a full data analytics pipeline, including data extraction from an API, data cleaning, SQL-based exploration, visualization, and regression modeling.

## Objectives

The project is structured around three key questions:

1. Which countries and products dominate U.S. oil imports?
2. How has dependency on top suppliers changed over time?
3. Are oil imports becoming more volatile?

## Tools and Technologies

- Python (pandas, numpy)
- SQL (DuckDB)
- Data Visualization (matplotlib, seaborn)
- Statistical Modeling (scikit-learn, statsmodels)
- API Integration (EIA API)

## Data Source

The data is retrieved from the U.S. Energy Information Administration (EIA) API, providing monthly petroleum import data by product and country.

## Key Features

- End-to-end data pipeline (API → cleaning → analysis)
- SQL-based exploratory data analysis
- Time-series visualization
- Regression modeling and interpretation
- Volatility and dependency analysis

## Limitations

Some observations in the dataset contain incomplete country information (labeled as "Unknown"), which may slightly distort country-level comparisons. This limitation is acknowledged and considered in the interpretation of results.
