# How-the-War-Changed-Ukrainian-Football-Data-Analysis
Data analysis project exploring how the 2022 war affected Ukrainian football clubs. I analyzed changes in foreign players, squad age, and market value to explain the decline in European performance using Python, Pandas, and visualizations.


## Project Overview

This project explores how the full-scale war in Ukraine affected Ukrainian football clubs and their performance in European competitions.

The analysis focuses on changes in squad composition, including the number of foreign players, average squad age, and market value. The goal is to understand whether these factors can help explain the decline in European performance after 2022.


## Business Questions / Hypotheses

This analysis is based on testing the following hypotheses:

1. **Talent Drain**
   Has the number of foreign players in Ukrainian clubs significantly decreased after 2022?

2. **Loss of Experience**
   Have Ukrainian teams become younger, indicating a loss of experienced players?


## Dataset

The analysis is based on football data containing information about players, clubs, appearances, market values, lineups, and club performance.

The project uses the following CSV files:

- `appearances.csv`
- `competitions.csv`
- `player_valuations.csv`
- `players.csv`
- `game_lineups.csv`
- `club_games.csv`

These files were used to analyze squad composition, player characteristics, market value changes, and club performance over time.


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook


## Data Cleaning

Before the analysis, the dataset was preprocessed to ensure data quality:

- Removed columns with more than 50% missing values
- Handled missing values in key columns
- Converted data types where necessary
- Standardized and cleaned textual data
- Filtered relevant data for Ukrainian clubs

These steps ensured that the analysis is based on consistent and reliable data.
