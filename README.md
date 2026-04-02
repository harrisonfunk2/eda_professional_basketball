# Exploratory Data Analysis of NBA Shot Charts

This project explores NBA shot-chart data using Python, with a focus on shot location patterns, visualization, and dimensionality reduction. The work was completed as part of a Statistical Data Science course assignment and demonstrates data wrangling, exploratory data analysis, and unsupervised learning on real basketball data.

## Project Overview

The goal of this project was to analyze professional basketball shot data and better understand how players generate offense across different areas of the court. Using NBA shot-chart data, I cleaned and organized team, player, and shot-level datasets, then created visualizations to study shooting behavior and spatial shot patterns.

The project begins with exploratory analysis of Stephen Curry’s shot attempts, including scatter plots, hexbin plots, and kernel density contour plots. It then expands to a league-wide analysis by transforming player shot charts into binned and smoothed court representations. Finally, I applied non-negative matrix factorization (NMF) to identify common shooting archetypes and compare how well different players’ shot patterns can be reconstructed from those learned components.

## Methods Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- JSON parsing
- exploratory data analysis
- kernel density estimation
- non-negative matrix factorization (NMF)

## Key Tasks

- Parsed raw NBA JSON files into structured pandas DataFrames
- Cleaned team, player, and shot-level data
- Isolated and analyzed Stephen Curry shot attempts
- Created shot-location visualizations on a basketball court layout
- Binned and smoothed shot data into 2D spatial shot surfaces
- Vectorized shot charts for hundreds of players
- Applied NMF to learn interpretable shooting-pattern archetypes
- Compared reconstruction error across players to evaluate model fit

## Main Takeaways

- Shot data can be effectively visualized as spatial patterns rather than only traditional summary statistics.
- Stephen Curry’s shot distribution highlights strong perimeter activity and selective interior finishing.
- Vectorized shot surfaces provide a useful way to represent player tendencies numerically.
- NMF can uncover interpretable basis patterns that summarize common NBA shooting styles.
- Reconstruction error helps show which players are well described by shared archetypes and which players have more unique shot profiles.

## Files

- `assignment2.ipynb` — main notebook containing the full analysis
- `assignment2.pdf` — exported version of the completed assignment
