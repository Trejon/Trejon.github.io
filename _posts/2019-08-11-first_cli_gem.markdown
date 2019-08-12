---
layout: post
title:      "First CLI Gem"
date:       2019-08-12 00:31:46 +0000
permalink:  first_cli_gem
---


My first CLI gem came together slowly but was eventually transformed into a functional program. I chose to focus my first project on something else I knew I was interested in personally, hoping it could translate into a deeper learning of a new skill. Scrapping had been a difficult concept for me to begin with so I was excited for the opportunity to work more in depth with it. First, I scrapped ESPN for data and information on the top 50 players in the league. My goal in the project was to have a command line interface that had players listed numerically for me to select from. Next, after going back and forth on various methods to display my data, I realized it made the most sense to create each player from the site as an object using the name in the instantiation. This allowed for the player extracted from the website to have attributes, such as position, team, points per game and others, to be displayed in their own section.

Finally, after long delegation and confusion, I realized the best way for me to display the data from all the players was to create individual arrays for each piece of information I was scrapping. I was unable to directly iterate over the information with an index until I named each to different arrays. But then was able to iterate over each piece of the player's data while pushing them into a new instance of a player. With each new instance of a player being listed with an index, I was then able to select a player and return a full page of this player's data. Overall, I feel like the project pulled together smoothly with being able to showcase NBA stats for the top stars in the league. 
