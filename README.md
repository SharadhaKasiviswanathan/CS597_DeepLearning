# CS597_DeepLearning


# NBA Data Analysis with Deep Learning

## Overview

This project aims to analyze NBA player statistics using deep learning techniques. The data used in this project includes various performance metrics of NBA players such as points scored, assists, rebounds, field goal percentages, and more. The project applies data cleaning, aggregation, and statistical analysis techniques to derive meaningful insights from the dataset.

## Project Structure

This repository consists of a Jupyter notebook which follows a structured pipeline:

1. **Data Cleaning**: Preprocessing of raw NBA player statistics data.
2. **Data Aggregation**: Summing up various metrics like points, assists, rebounds, and others, grouping by player.
3. **Statistical Analysis**: Applying calculations such as average per game statistics for players.
4. **Visualization**: Generating relevant plots and charts to visualize trends and player performances.

### Notebook Details

1. **Data Import and Cleaning**:
   - The raw data is loaded and cleaned using pandas.
   - Players' statistics such as points, assists, field goals, and more are extracted from the dataset.
   
2. **Data Aggregation**:
   - The data is grouped by players, and metrics like total points scored, assists, turnovers, and field goals are summed up.
   - Additional columns are created to represent average statistics per game for players, which are derived from the aggregated stats.

3. **Statistical Analysis**:
   - The number of games played by each player is calculated.
   - Average statistics per game are computed and included in the dataset.
   
4. **Visualization**:
   - Visual representations (graphs and charts) are created to analyze player performances, compare stats, and detect trends.
   
5. **Final Output**:
   - The cleaned and aggregated dataset is saved for further analysis or use in machine learning models.

## Prerequisites

Before running this notebook, ensure that you have the following libraries installed:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For plotting visualizations.
- `numpy`: For numerical operations.
- `seaborn`: For enhanced data visualization (optional).

To install the required libraries, run the following:

```bash
pip install pandas matplotlib numpy seaborn
```

## How to Run

1. Clone this repository or download the notebook file.
2. Make sure you have the necessary dependencies installed.
3. Run the notebook in a Jupyter environment or Google Colab.
4. The notebook will guide you through loading the data, cleaning it, and generating the visualizations.

## Data

The dataset used in this project is a collection of NBA player statistics. The data contains several columns and several other relevant basketball statistics.

## Key Features

### Data Cleaning
The dataset goes through several cleaning steps to ensure its quality:

- **Missing Values Handling**: Missing or erroneous values are handled appropriately.
- **Outlier Detection**: Outliers in the dataset are identified and handled.

### Data Aggregation
- **Per Game Stats**: The stats for each player are aggregated to provide per-game statistics.
- **Game Count**: The number of games each player participated in is also calculated.

### Statistical Insights
- Players’ performances are analyzed based on aggregated statistics like total points scored, average points per game, field goal percentage, and more.

### Visualizations
- Graphs and charts are generated to visualize player performances, compare stats, and detect trends.

## Example Output

The notebook produces several outputs, including:

- Aggregated player statistics with per-game averages.
- Various plots such as:
  - Points per game vs. assists.
  - Field goal percentage comparisons.
  - Distribution of rebounds, turnovers, and other metrics.

## Conclusion

This project provides a detailed statistical analysis of NBA player data, offering insights into performance trends across the league. It can be further extended with machine learning models to predict player performance, or other predictive tasks.

# Player Stats Abbreviations

### Full Form of Player Statistics Abbreviations:

- **PTS**: **Points** – Total points scored by the player in a game.
- **AST**: **Assists** – Total assists made by the player.
- **TRB**: **Total Rebounds** – The sum of both offensive and defensive rebounds.
- **FG%**: **Field Goal Percentage** – The percentage of field goals made by the player, calculated as (Field Goals Made / Field Goals Attempted) * 100.
- **3P**: **Three-Point Field Goals Made** – The total number of three-point shots made by the player.
- **3PA**: **Three-Point Attempts** – The total number of three-point shots attempted by the player.
- **TOV**: **Turnovers** – The total number of times the player loses possession of the ball to the opponent.
- **STL**: **Steals** – The total number of times the player steals the ball from the opponent.
- **BLK**: **Blocks** – The total number of shots the player blocks.
- **Tm**: **Team** – The team the player is currently playing for.
- **Opp**: **Opponent** – The opponent team the player is facing.
- **MP**: **Minutes Played** – The total number of minutes the player has played in the game.
- **FG**: **Field Goals Made** – The total number of field goals made by the player.
- **FGA**: **Field Goals Attempted** – The total number of field goals the player has attempted.
- **3P%**: **Three-Point Percentage** – The percentage of successful three-point shots made by the player, calculated as (3P / 3PA) * 100.
- **FT**: **Free Throws Made** – The total number of free throws made by the player.
- **FTA**: **Free Throws Attempted** – The total number of free throws attempted by the player.
- **FT%**: **Free Throw Percentage** – The percentage of successful free throws made by the player, calculated as (FT / FTA) * 100.
- **ORB**: **Offensive Rebounds** – The total number of rebounds grabbed on the offensive end.
- **DRB**: **Defensive Rebounds** – The total number of rebounds grabbed on the defensive end.
- **PF**: **Personal Fouls** – The total number of personal fouls committed by the player.
- **GmSc**: **Game Score** – A comprehensive statistic that provides an overall score based on a player's performance in a game.
