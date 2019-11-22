# EECS731Project4
Major League 

NFL, MLB, NBA and Soccer scores
1. Set up a data science project structure in a new git repository in your GitHub account
2. Pick one of the game data sets depending your sports preference
https://github.com/fivethirtyeight/nfl-elo-game 
https://github.com/fivethirtyeight/data/tree/master/mlb-elo 
https://github.com/fivethirtyeight/data/tree/master/nba-carmelo 
https://github.com/fivethirtyeight/data/tree/master/soccer-spi 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more regression models to determine the scores for each team using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

# Data Source and description

https://projects.fivethirtyeight.com/nba-model/nba_elo.csv
nba_elo.csv contains game-by-game Elo ratings and forecasts back to 1946.

# Two main parts of this project

Data exploration and Regression

# Part 1: Data exploration

We first clean the data set by removing all the null data.
We calculate the correlation between any two factors.
Then we calculate total number of games played by each team and find the winner of each game.

# Part 2: Regression

We add three additional factors for regression. They are the winner indicator, difference between post match ratings of the two teams,
and product of probabilities.

We come up with two different models. one is the random forest and the other is linear regression. We found that the linear regression model can substantially enhance the performance.

