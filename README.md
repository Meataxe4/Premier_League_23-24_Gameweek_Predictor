# Premier League 23/24 Gameweek Predictor
The code uses a Poisson regression model to predict the results in each game in a given matchweek/gameweek. It then provides the probability of each possible outcome.

xG from indiviual games from the 22/23 season has been used as the training data and used in the poisson model.

The relegated teams have been removed and replaced with promoted teams from the Championship from 22/23 season, again there has been some assumptions over the xG used for the newly promoted teams.

The code creates two Poisson regression models, one for the home team and one for the away team. The Poisson regression models are used to predict the number of goals scored by each team in that matchweek.

The predicted goals are then used to generate random scores for each match taking into consideration the formula for expected goals.

Finally a probability of a Home Win, Draw and Away Win is provided in the final output.
