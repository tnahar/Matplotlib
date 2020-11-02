A three part project on creating charts to visualize a wrestler's wins and losses over the course of four years. 

Winning Wrestlers Entertainment¶
In this activity you will be taking four seperate csvs that were scraped down from a wrestling database, merging them together, and then creating charts to visualize a wrestler's wins and losses over the course of four years.

Part 1 - Macho Merging
You will likely need to perform three different merges over the course of this activity, changing the names of your columns as you go along.

Bring each CSV into a separate data frame
Merge the first two datasets (2013 and 2014) on "Wrestler" so that no data is lost (should be 182 rows)
Rename our _x columns to "2013 Wins", "2013 Losses", and "2013 Draws"
Rename our _y columns to "2014 Wins", "2014 Losses", and "2014 Draws"
Merge our newly combined dataframe with the 2015 dataframe
Rename "wins", "losses", and "draws" to "2015 Wins", "2015 Losses", and "2015 Draws"
Merge our newly combined dataframe with the 2016 dataframe
Rename "wins", "losses", and "draws" to "2016 Wins", "2016 Losses", and "2016 Draws"
Part 2 - Time to Calculate!
When your tables have been merged together into one data frame, calculate the total number of wins, losses, and draws a wrestler has had over the course of their career. Also create a new column that will hold the total matches a wrestler has been in over the course of their career.

You will need to convert all NaN values to a number so that you can perform these calculations We are only interested in those wrestlers who have been with the WWE from 2013 to 2016. You will need to come up with some way of filtering out rows that do not meet these conditions.

Also set the 'Wrestler' column as your key for easier referencing later on.

Replace all NaN values with 0

Create a new column called "Total Wins" and add up each wrestler's wins per year to fillinthe values

Create a new column called "Total Losses" and add up each wrestler's losses per year to fill inthe values

Create a new column called "Total Draws" and add up each wrestler's draws per year to fill inthevalues

Create a new column called "Total Matches" and add up the total wins,losses,anddraws

Create a new dataframe for those wrestlers who have wrestled at least 100 matches,have at least one win in 2013,# and have at least one win in 2016

Part 3 - Charting Careers
Store an individual wrestler's wins over time in a variable Store that same wrestler's losses over time in a variable as well Create a line chart that will plot this wrestler's wins and losses from 2013 to 2016

Collect the user's input to search through our data frame
Create a series that looks for a wrestler by name and then traces their wins from 2013 to 2016
Create a series that looks for a wrestler by name and then traces their losses from 2013 to 2016
Create a list of the years that we will use as our x axis
Plot our line that will be used to track a wrestler's wins over the years
Plot our line that will be used to track a wrestler's losses over the years
Place a legend on the chart in what matplotlib believes to be the "best" location
image.png