# moneyball
Mo money mo problems

Put together an all-time best roster of cheap players who had great on base percentages

## Objectives
- Understand how to use public data for analysis
- Understand how to relate many datasets and perform analysis on the related data
- Understand how to publish your own data analysis as a notebook
- Able to Join / Merge many external datasets
- Able to perform statistical analysis to solve a problem

## Files included
A Jupyter notebook named moneyball.ipynb showing your analysis.
A requirements.txt file: 'pip install -r requirements.txt' in your command line to run files in this repo


## Description
In the movie / book Moneyball - data analysis is employed to discover that teams that had a roster containing players with a high on base percentage (OBP) did very well in the regular season. Using this knowledge the General Manager was able to create a very successful team on a shoestring budget with players that had a high OBP.

* First get the most recent complete baseball statistics dataset from Sean Lahman's website. Unzip it into a data/ directory inside your repository.

* Create a Jupyter Notebook that joins together many of the different tables so you are able to find each player's OBP and their salary.

* Put together the starting 9 player roster for a single season.
    * You need to find the players with the highest OBP and the lowest salary in any specific year. Make sure you are removing outliers (an OBP of 1.0 is not an indicator of a perfect player, more like they possibly only played 4 or 5 games and had good luck, alternatively an OBP of 0 is pretty bad). Your 9 player roster will need to include:
      * (1st, 2nd, 3rd) Baseman
      * (Left, Center, Right) Fielders
      * Short Stop
      * Pitcher
      * Catcher
      * A player that historically played multiple positions can not account for 2 places on your roster.
