# NBA Games Results Prediction

Note: all data for this project are generated and/or modified from https://basketball-reference.com, I have also uploaded on this site.<br>
Source data were uploaded to my personal website, they are also available on this site. <br>
This prediction is produced by Jiabao Zheng with thanks to the inspiration by https://lanqiao.cn <br>
The data cleaning notebook can be found in the data cleaning folder.

In this project, we use Python and Logistic Regression to predict NBA game results in 2019-2020 season based on team's statistic from the previous season. 
![title](nba_profile.jpg)

The HTML version is available at https://student.cs.uwaterloo.ca/~j243zhen/project/nba_pred/nba_game_results_prediction.html. More information are available on this site

## Summary
We used some statistics from basketball-reference.com to calculate the Elo score of each NBA team and used these basic statistics to evaluate 
the past games of each team, and compared the teams according to the rating method "Elo Score". The current team's performance and the characteristics
of these different teams are finally used to determine which team can have the advantage in a game.  Unlike some other predictions, in our prediction 
results, we did not determine the results of each game by only saying the winner. Instead, we calculated the probability of our results. One improvement 
for this project would be the amount of data we use to evaluate the performance of the team is too small (only the 2018-2019 season's data). 
If you want a more accurate and systematic judgment, you should get more statistics of each NBA team from previous years for prediction. 

