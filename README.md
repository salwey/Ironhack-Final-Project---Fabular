# Ironhack-Final-Project---Fabular
Final Project for the Ironhack Bootcamp. Spiritus Games were kind enough to share their player log data with me, from this I wrangled the data into more useable formats resulting in several tables. Then performed an analyses in Tableau on how to increase player satisification. 


**-- Overview of fabular.ipynb --**
Ultimately the output of running this is creating several .csv files which we load into tableau.

**Load in the data**
After some initial exploration of a sample player log, we first load in the player log files. As inside the logs there is no player id, but we do have separate files for each player, so we also bring in the filenames to use as a player id.

**Seperate Events**
As some events are related and we have no event ID, this step effectively adds in this event id. This takes a few minutes to process.

**Exploring sample data**
Here I did an initial exploration of a sample log file.

**Extracting battle info**
Taking a closer look into the battle events and stats we have available.

**Thoughts on nice to have target tables**
At this point, I wanted to set a goal for what tables would be nice to have to work from. Listed the tables and columns that would make sense to work towards.

**Working toward player battles table**
The initial table I'm working toward creating is the player battle table, other tables will be derived at least in part from this table. It is creating a row for each battle that has taken place with some stats related to each battle.

**Player Attempt Table**
As fabular is a roguelike title, it makes sense to also have a summary for each attempt. Each row is a player's run. The first attempt is the tutorial.

**Player Table**
Gives an overview of each player - how far have they progressed through the game and various player based stats.

**Activity Table**
Here we setup a few for daily active users (DAU) and also weekly active users (WAU) with the following cohorts: New, Winback and Continuing players.

**Machine Learning**
In this step we are using a neural network technique to see if it is possible to predict a successful boss kill.

**Exploring / Metrics**
Now we have some tables, this is a small exploration in to what kinds of information we can see from this.

**Steam**
Connecting to the Steam API we are pulling some comparative data for a selection of similar games.

