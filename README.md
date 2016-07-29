Moneyball

In the movie / book Moneyball - data analysis is employed to discover that teams that had a roster containing players with a high on base percentage (OBP) did very well in the regular season. Using this knowledge the General Manager was able to create a very successful team on a shoestring budget with players that had a high OBP.

I pulled most recent complete baseball statistics dataset from Sean Lahman's website. Unzip it into a data/ directory in the repository.

Created a Jupyter Notebook called moneyball.ipynb that joins together many of the different tables in able to find each player's OBP and their salary.

Put together the starting 9 player roster for a single season.

Found the players with the highest OBP and the lowest salary in any specific year, removing outliers (an OBP of 1.0 is not an indicator of a perfect player, more like they possibly only played 4 or 5 games and had good luck, alternatively an OBP of 0 is pretty bad). Roster includes:

(1st, 2nd, 3rd) Baseman
(Left, Center, Right) Fielders
Short Stop
Pitcher
Catcher
