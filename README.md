# Ind_Project_European-Soccer-Top-Points-Contributors--Kaggle
    
## Screenshot
![screenshot](https://github.com/dmarks84/Ind_Project_European-Soccer-Top-Points-Contributors--Kaggle/blob/main/soccer_screenshot.png?raw=true)

## Summary
I worked on the European Soccer Dataset.  The data was read in from a SQL database (SQLite).  There were several table for players, matches, teams, etc. and these were read into separate dataframes in Pandas.  The data was wrangled and reoganized so that various identifications and summations/averages could be calcualted.  All this was done in order to determine who helps earn the most points for their team.  I look at two sample means for each player-- their team's average points per game when they started and when they didn't start.  I used a paired t-test to determine the signficance of the differnece between these two values.  I performed this individually for Lionel Messi, setting up a hypothesis test related to his contributions signficance to his team's average points haul, and then I performed this for a large list of players in Europe that played a substantial number of games.

## Results
Through the hypothesis testing and statistical analysis done individually on Lionel Messi, I found there was not evidence to suggest that Lionel Messi create a significant contribution to FC Barcelona's average points per game when he starts games compared to when he does not start games. This does not suggest that he is not the most valuable player in the world-- it likely simply suggests that Barcelona is a great team even without him.  Leon Osman appeared to have the most significant contribution to his team.  When he started a match, his team (Everton), took home 1.722 points on average in the seasons before 2017 where he played.  When he does not start in the same period, they take home only 1.185 points on average.

## Skills (Developed & Applied)
Programming, Python, Statistics, Numpy, Pandas, Dataframes, Data Wrangling, Data Reporting, Statistical Analysis, P-Values, Hypothesis Testing
