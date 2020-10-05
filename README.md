STOR 538 Project 2
==================

Project Details
---------------

### Objective
The Variables you will be predicting are Spread, Total Points, and Result. <br />
Spread = Winning team's score - Losing team's score <br />
Total points = Winning team's score + Losing team's score <br />
Result = Who won the game



### Methodology
Data is available here: https://github.com/mattymo18/STOR-538-Project2 <br />
You are asked to use this data to build models that predict the 3 variables above. These models will be used to predict NFL games in weeks 8-10. That schedule can be found here: https://www.espn.com/nfl/schedule <br />

### Grading 
You will be graded on accuracy of your models predicting these three variables. Dr. Mario will release results after each week's games ranking your projects vs your classmates. 


Data
----
Data is found in the Source-Data directory. 

1. Game.Results.csv was taken from kaggle at: https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv <br />
This dataset contains scores for every game from 2000-2019. It also contains pregame gambling lines for each game, as well as information about the weather at each game. 

2. nfl_teams.csv was taken from kaggle at:
https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv <br />
This dataset contains information about each team in the NFL. 

3. nfl_stadiums.csv was taken from kaggle at:
https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=nfl_teams.csv <br />
This dataset contains information about each stadium. 

4. Defensive-Stats folder was taken from https://www.pro-football-reference.com <br />
Contains aggregate data for all teams from 2000-the first three games of 2020. 

5. Offensive-Stats folder was taken from https://www.pro-football-reference.com <br />
Contains aggregate data for all teams from 2000-the first three games of 2020. 

#### Important Note about Offensive and Defensive Stats:
Defensive stats are from multiple points of view. For example the columns turnovers, fumbles, and interceptions represent how many turnovers and fumbles that team caused the opposing offense. On the other hand, columns under the passing or rushing header are what that team allowed the opposing offense during the 16 games.

Glossary
--------
Rk -- Rank
This is a count of the rows from top to bottom.
It is recalculated following the sorting of a column.<br />
G -- Games played
#### Points
PF -- Points Scored by team (on defensive datasets this represents points allowed)<br />
#### Tot Yds & TO
Ply -- Offensive Plays: Pass Attempts + Rush Attempts + Times Sacked<br />
Y/P -- Yards per Offensive Play<br />
(Rush + Pass Yards)/( Pass Attempts + Rush Attempts + Times Sacked)<br />
TO -- Takeaways<br />
FL -- Fumbles Lost by Team<br />
1stD -- First Downs<br />
#### Passing
Cmp -- Passes completed<br />
Att -- Passes attempted<br />
Yds -- Yards Gained by Passing<br />
For teams, sack yardage is deducted from this total<br />
TD -- Passing Touchdowns<br />
Int -- Interceptions thrown<br />
NY/A -- Net Yards gained per pass attempt
(Passing Yards - Sack Yards) / (Passes Attempted + Times Sacked)
Minimum 14 attempts per schedule game to qualify as leader.
Minimum 1500 pass attempts to qualify as career leader.<br />
1stD -- First Downs by Passing<br />
#### Rushing
Att -- Rushing Attempts (sacks not included in NFL)<br />
Yds -- Rushing Yards Gained (sack yardage is not included by NFL)<br />
TD -- Rushing Touchdowns<br />
Y/A -- Rushing Yards per Attempt
Minimum 6.25 rushes per game scheduled to qualify as leader.
Minimum 750 rushes to qualify as career leader.<br />
1stD -- First Downs by Rushing
#### Penalties
Pen -- Penalties committed by team and accepted<br />
Yds -- Penalties in yards committed by team<br />
1stPy -- First Downs by Penalty<br />
#### Percentages
Sc% -- Percentage of drives ending in an offensive score<br />
TO% -- Percentage of drives ending in an offensive turnover<br />
#### Expected Points
EXP -- Expected points
