<h1 align="center" style="border-bottom: none">
    <a href="https://prometheus.io" target="_blank"><img alt="Prometheus" src="./.assets/heading-image.svg"></a><br>Predicting Football Betting Odds
</h1>

> A `R` project designed to explore the factors that influence football betting odds and attempting to construct a model with predictive capabilities for these odds.

- [Dataset](https://github.com/adithya-r-01/football-linear-regression/tree/main?tab=readme-ov-file#dataset)
- [Running The Analysis](https://github.com/adithya-r-01/football-linear-regression/tree/main?tab=readme-ov-file#running-the-analysis)
- [Report](https://github.com/adithya-r-01/football-linear-regression/tree/main?tab=readme-ov-file#report)

## Dataset

The dataset used for this project is the European Soccer Database, sourced from [Kaggle](https://www.kaggle.com/datasets/hugomathien/soccer/code). This dataset includes information about over 25,000 matches, attributes for teams and players, and betting odds. The focus of this analysis is to leverage both team-level attributes and player-level characteristics to predict the `home_team_win_probability`, derived from pre-match attributes.

The dataset was aggregated from three separate data sources:
- http://football-data.mx-api.enetscores.com/  : scores, lineup, team formation and events
- http://www.football-data.co.uk/ : betting odds. Click here to understand the column naming system for betting odds:
- http://sofifa.com/ : players and teams attributes from EA Sports FIFA games. FIFA series and all FIFA assets property of EA Sports.

For the full citation of the dataset:

```
Mathein, H. (October,2016). European Soccer Database, 2.0. Retrieved Nov. 10, 2024 from https://www.kaggle.com/datasets/hugomathien/soccer/data.
```

## Running The Analysis

The bulk of the analysis is available in the `analysis.Rmd` file. The analysis includes all the neccessary data cleaning, model selection, and results completely annotated. Simply run each code block in succession withing the `analysis.Rmd` file for the full report to be generated.

Before generating the report use the [Kaggle](https://www.kaggle.com/datasets/hugomathien/soccer/code) link and put the attached `.sqlite` file in the same directory as the `.Rmd` file.

## Report

For a static version of the report consult the `analysis.html` file which has all figures rendered and code blocks executed.

