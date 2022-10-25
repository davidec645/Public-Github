# Sports_Analysis
## Overview
These scripts are part of an ongoing project to refine my data science skills, apply new techniques, and participate in open source coding.

The goal of this project is to predict the outcome of college football games, as well as to see if its possible to have more accurate models than the line setters at a sportsbook.

All relevant function can be called from the master script, which will create the data sets from collegefootballdata.com's public API, do some feature creation and finally compare two different models based on that feature creation. The first model is a sequential neural network, the specification of which can be viewed in the Sports_NN script.  The second model is a basic OLS linear regression. Notably, the linear regression performs just as well, and often better depending on the test/train split, then the Neural Network. Further evidence, if its needed at all, that Deep Learning is not always the best tool for the job and that the simplier models should always be applied first.

## To Do
1. Add more features 
   -Percentage of starters present
   -clustering teams and refining current features to compare how teams have competed against similar teams instead of all aggregated historical          performance
2. Format and Upload Bayesian Model for public Github
