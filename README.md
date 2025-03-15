The basic strategy is going to be 
1. Data preparation, binding teams, box scores, and tourney scores into one data frame
2. Include the winning and losing team's ELO scores in our main data set
3. Build an average of the team's recent performance using the box scores
4. Run a logistic regression with the data from 2 and 3
5. get a table with the teams, elo scores, and recent performance data
6. Write a loop that will do a prediction for each team in the tournament against every other team in the tournament using the data from part 5.
