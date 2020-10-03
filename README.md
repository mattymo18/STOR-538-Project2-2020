STOR 538 Project 2
==================

Data
----
Data is found in the Source-Data directory. 

1. Game.Results.csv was taken from kaggle at: https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv
This dataset contains scores for every game from 2000-2019. It also contains pregame gambling lines for each game, as well as information about the weather at each game. 

2. nfl_teams.csv was taken from kaggle at:
https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv
This dataset contains information about each team in the NFL. 

3. nfl_stadiums.csv was taken from kaggle at:
https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv
This dataset contains information about each stadium. 

4. Defensive-Stats folder was taken from https://www.pro-football-reference.com
Contains aggregate data for all teams from 2000-the first three games of 2020. 

5. Offensive-Stats folder was taken from https://www.pro-football-reference.com
Contains aggregate data for all teams from 2000-the first three games of 2020. 

## Important Note about Offensive and Defensive Stats:
Defensive stats are from multiple point of views. For example the columns tunrovers, fumbles, and interceptions represent how many turnovers and fumbles that team caused the opposing offense. On the other hand, columns under the passing or rushing header are what that team allowed the opposing offense during the 16 games. 

# Glossary:
Rk -- Rank
This is a count of the rows from top to bottom.
It is recalculated following the sorting of a column.
G -- Games played
### Points
PF -- Points Scored by team
### Tot Yds & TO
Ply -- Offensive Plays: Pass Attempts + Rush Attempts + Times Sacked
Y/P -- Yards per Offensive Play
(Rush + Pass Yards)/( Pass Attempts + Rush Attempts + Times Sacked)
TO -- Takeaways
FL -- Fumbles Lost by Team
1stD -- First Downs
### Passing
Cmp -- Passes completed
Att -- Passes attempted
Yds -- Yards Gained by Passing
For teams, sack yardage is deducted from this total
TD -- Passing Touchdowns
Int -- Interceptions thrown
NY/A -- Net Yards gained per pass attempt
(Passing Yards - Sack Yards) / (Passes Attempted + Times Sacked)
Minimum 14 attempts per schedule game to qualify as leader.
Minimum 1500 pass attempts to qualify as career leader.
1stD -- First Downs by Passing
### Rushing
Att -- Rushing Attempts (sacks not included in NFL)
Yds -- Rushing Yards Gained (sack yardage is not included by NFL)
TD -- Rushing Touchdowns
Y/A -- Rushing Yards per Attempt
Minimum 6.25 rushes per game scheduled to qualify as leader.
Minimum 750 rushes to qualify as career leader.
1stD -- First Downs by Rushing
### Penalties
Pen -- Penalties committed by team and accepted
Yds -- Penalties in yards committed by team
1stPy -- First Downs by Penalty
Sc% -- Percentage of drives ending in an offensive score
TO% -- Percentage of drives ending in an offensive turnover
### Expected Points
EXP -- Expected points