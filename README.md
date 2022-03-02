# Overview

eSports has been a growing industry with revenues expected to reach $1,084 million, representing a year-on-growth of 14.5%. The combined esports market together with games streaming is expected to be worth $2.1 billion in 2021 and more than $3.5 billion by 2025.\
Just like any other sport, there are several elements within the game that contribute to the outcome of the game and wether the team wins or lose. This analysis focuses on using machine learning to create a model on data collected from Riot Game's developer api to predict the outcome of a match. \



# Data Understanding

The data used for this project was obtained from the Riot API using their developer platform, I have also uploaded the same dataset on kaggle and can be found using [this](https://www.kaggle.com/pratimanjoshi/euw-challanger-gamestats) link. It includes data from challenger level competitive matches with 13 features per player and one target variable which indicates whether the match resulted in a win or loss for the player.

<b>Glossary of Features:</b>
- Kills: Total number of kills the player have gotten during the span of a game.
- Deaths: Total times the player died in the game.
- Assists: Contributing to a kill by providing damage or utility.
- KillParticipation: This statistic is calculated for a player by taking their kills plus assists and dividing that by their team's total kills.
- Kda: This statistic refers to the players Kills, Deaths and Assists ratio.
- goldPerMinute: This statistic holds the value of the gold that the player earned every minute in the game. 
- totalMinionsKilled: This is the value of the total creeps the player killed by the end of the game.
- gold: This statistic refers to the value of the total gold the player had by the end of the game.
- totalDamageDealt: This is the value of the total damage the player dealt during the 
- visionScore: This statistic indicates how much vision a player has influenced in the game, this also includes the vision they provided and denied.
- visionScorePerMinute: This statistic provides the vision score of the player with respect to time.
- skillshotsDodged: This is a fairly new metric present within the 'challange' metric in the riot match api. This provides the number of skillshots dodged by the player.
- skillshotsHit: Similar to skillshotsdoged, skillshotshit is a metric to show how many skillshots a player hit.
- win: The final metric which tells the result of the player's game.

# Methods
