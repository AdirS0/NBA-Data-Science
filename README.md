# NBA-Data-Science

This repository contains a project made by Adir Solomon, Hai Elimelech and Aviv Amrusi in a data science class at Holon Institute of Technology, analyzing NBA players stats by using pandas and machine learning in Python.</br>

# Main Purpose
The NBA has a lot of interesting statistics but there is a statistic that combines them all, under the name PER.</br>
We used it to estimate the success of the players in their season.</br>

Our process for each research question:</br>
Defining a research question -> Web Crawling -> Data Cleaning -> Visualization -> Machine Learning.

1. Can we predict if a player is 'Efficient' according to his stats?
2. Can we predict a player’s seasonal salary?
3. Can we predict a player's average points per game?

# Web Crawling
We got our data from:</br>
https://www.basketball-reference.com/leagues/NBA_2021_totals.html</br>
https://www.basketball-reference.com/contracts/players.html</br>
</br>
Manipulated the data with Beautiful Soup library.

# Data Cleaning
Removed missing data.</br>
Filled missing values.</br>
Handled outliers.</br>

# Visualisation
We visualized our data and then analyzed it to try and learn more about it.</br>
We used seaborn and matplotlib visual libraries.

# Machine Learning
Used sklearn with linear regression and logistic regression algorithms to try to:</br>
Predict if a player is 'Efficient' according to his stats.</br>
Predict a player’s seasonal salary.</br>
Predict a player's average points per game.</br>
