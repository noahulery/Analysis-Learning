# FantasyFootball
A place to store all my FF data collection and analysis.

hopefully in the future this will contain the algorithm to collect player stats and project future stats

This will pull stats from tables on www.pro-football-reference.com. As written it pulls the 2019 passing rushing and reciveing stats. The url list and dataframes that are created and merged can be altered to use this code to scrape other pages on the website.

I will use this to pull weekly data from 2019 and use the weekly data from earlier weeks (ex weeks 1-12) to project the stats of later weeks. the projected stats of later weeks will be used in a multivariable regressor to estimate a player's point output for a given week. This will be used to optimize DFS lineups
