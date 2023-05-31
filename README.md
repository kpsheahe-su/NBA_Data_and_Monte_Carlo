# NBA_Data_and_Monte_Carlo


This repository contains 2 final dataset: an individual player event data of NBA games of the 2021-2022 season, and game level data for every game from 2003 through the 2021 season. 

The first dataset of event data comes from Vladislav Shufinskiy work of gathering shot data, play-by-play data and url links. So the first data is the culmination of all that data through joins using Tableau. If you would like to see the original data sets please use the kaggle link below: https://www.kaggle.com/datasets/brains14482/nba-playbyplay-and-shotdetails-data-19962021?select=nbastats.csv 


The second dataset is game level data that I sourced from Nathan Lauga on kaggle, the link is below: https://www.kaggle.com/datasets/nathanlauga/nba-games?select=games.csv I took this dataset and transformed it to add rolling averages and standard deviations heading into each game of the last 10,5, and 3 games for each metric. The metrics were Points, Field-Goal, Field-Goal 3, Free-Throw, Assists and Rebounds all categorized as For or Against the team. This expansion enabled the use of a Monte Carlo simulation to the predict the metrics headed into each game. 

The tools used in this work were Python, Tableau, and Excel. 

If you have any questions please feel free to email me Kevin.Sheahen@ucdconnect.ie or via Whatsapp +1-201-888-9299

