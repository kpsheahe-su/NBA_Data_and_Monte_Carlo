# NBA_Data_and_Monte_Carlo

This repository contains multiple datasets that can be divided into 3 main groups: Individual Player Play-by-Play Game Level Shot Data, Team Game Level Data, and Individual Player Season Long Data. 

The first dataset of event data comes from Vladislav Shufinskiy work of gathering shot data, play-by-play data and url links. So the first dataset is the culmination of all that data through joins using Tableau. If you would like to see the original data sets please use the kaggle link below: https://www.kaggle.com/datasets/brains14482/nba-playbyplay-and-shotdetails-data-19962021?select=nbastats.csv 
To see the final joined data please use this kaggle link to my upload (It's quite large 1.3 GB and over 2 million rows of numeric and text data):
https://www.kaggle.com/datasets/kevinsheahen/nba-player-shot-location-and-video-url

The second dataset is game level data (MonteCarlo.7z) that I sourced from Nathan Lauga on kaggle, the link is below: https://www.kaggle.com/datasets/nathanlauga/nba-games?select=games.csv I took this dataset and transformed it to add rolling averages and standard deviations heading into each game of the last 10,5, and 3 games for each metric. The metrics were Points, Field-Goal, Field-Goal 3, Free-Throw, Assists and Rebounds all categorized as For or Against the team. This expansion enabled the use of a Monte Carlo simulation to the predict the metrics headed into each game. 

The third dataset is Player Season Long data (Player_Season_Stats2.csv) which includes Basic performance stats for a player in a given season. This includes regular season and playoffs. The data was manually scraped from NBA.com as they prevent web-scraping through 404 errors. 

The other files include NBA Logos (30), Player Profile Pictures (+1000), a user guide that details more information, and the Python files needed to create the datasets. The tools used in this work were Python, Tableau, and Excel. Special Mention to Sudeep Tandon and Murhaf Abdal-qader who were great teammates during the project and helped in all the steps mentioned. The final tableau tool can be found at this link: https://public.tableau.com/app/profile/sudeep.tandon/viz/NBADashboardV8/LandingPage?publish=yes and is named Bucket Getter. 


If you have any questions please feel free to email me Kevin.Sheahen@ucdconnect.ie or via Whatsapp +1-201-888-9299

<img width="716" alt="Bucket Getter Main" src="https://github.com/kpsheahe-su/NBA_Data_and_Monte_Carlo/assets/35640823/c5f1b413-d9e5-447e-9d1d-2172163fce6c">
![Uploading Bucket Getter Player.PNG…]()
![Uploading Bucket Getter Team.PNG…]()


