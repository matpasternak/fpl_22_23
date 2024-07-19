# Fantasy Premier League  2022/2023 season analysis
Data analysis of 2022/2023 season in Fantasy Premier League which is a game based on  a real events in the Premier League. 

## About the game:
Fantasy Premier League (FPL) is a game played by 10m+ people globally and is a game which is base on a real action in Premier League. Your goal is to build most point team. Each manager of a team are selecting 15 players from all of the teams in Premier League and scores points. Each FPL manager is given a starting budget of £100 million and must pick a total of 15 players: 2 goalkeepers, 5 defenders, 5 midfielders and 3 forwards. You are limited to a maximum of three players from each Premier League team. Players in your team score points based on real-life performances with the main contributors to points totals being goals, assists (attacking side) and cleansheets(cs) (defensive side). Players can also lost their points for cards or own goal. 

More detailed points score table:

| Action      | Points |
| ----------- | ----------- |
| For playing up to 60 minutes | 1 |
| For playing 60 minutes or more (excluding stoppage time) |2|
| For each goal scored by a goalkeeper or defender | 6 |
| For each goal scored by a midfielder | 5 |
| For each goal scored by a forward | 4 |
| For each goal assist | 3 |
| For a clean sheet by a goalkeeper or defender | 4 |
| For a clean sheet by a midfielder | 1 |
| For every 3 shot saves by a goalkeeper | 1 |
| For each penalty save | 5 |
| For each penalty miss | -2 |
| Bonus points for the best players in a match | 1-3 |
| For every 2 goals conceded by a goalkeeper or defender | -1 |
| For each yellow card | -1 |
| For each red card | -3 |
| For each own goal | -2 |


## Project description
The goal of this project is to analysis diffrent statistics and find impact of these on points and patterns. With this conclusions search for undervalued players. Because in my opinion finding these kind of players before everyone else is a key to get to top ranks which is having more points than opponents.
This project aims to use statistical analysis to identify the best strategies for selecting a high-performing FPL team.

#### Objective

1.  Identify key factors correlating with high FPL points.
2.  Evaluate player performance across teams and positions.
3.  Provide recommendations for optimal squad selection.


##  Table Of Contents
The project is splitted by two Jupyter Notebooks.

1.  Data preparation
2.  Data analysis
	1. Introduction. Correlation analysis.
	2. Team and position analysis.
	3. Comparision relevant criteria.
	4. Selecting most optimal squads.

## Sources
1. Data used for this project is from Anand Vaastav [FPL Historical Dataset](https://github.com/vaastav/Fantasy-Premier-League)
2. Small library  [adjustText](https://github.com/Phlya/adjustText)  used for this project to automatic label placement for  `matplotlib` .




