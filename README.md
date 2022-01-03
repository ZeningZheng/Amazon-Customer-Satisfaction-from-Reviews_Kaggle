# Amazon-Customer-Satisfaction-from-Reviews_Kaggle
This is a group project for the course Big Data Analytics that I worked on with two other students during my masters.
https://www.kaggle.com/c/bda2021amazon/leaderboard

#### data
The Data come from [this website](http://jmcauley.ucsd.edu/data/amazon/), which is a repository with Amazon customer review data on different categories such as Baby, Beauty or Musical instruments. The data used in this notebook will be used to predict baby product satisfaction, and thus will generalize towards reviews oriented at this subject specifically.

#### Candidate machine learning methods
+ Features: TF-IDF for single words and bigrams, NRC (sentiment score)
+ Models: logistic regression, ridge and lasso regression
