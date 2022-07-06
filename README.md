# Bulldozer-price-prediction

In this project, we are going to predict the price of bulldozers with the help of Scikit-Learn's **RandomForestRegressor()** machine learning model.

## 1. Problem definition
How efficiently can we predict the sales price of the bulldozers, given its characteristics and previous examples

## 2. Data
The data is downloaded from the Kaggle bluebook for bulldozers: The data for this competition is split into three parts:

The datasets are:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
The key fields are in train.csv are:

* SalesID: the uniue identifier of the sale
* MachineID: the unique identifier of a machine. A machine can be sold multiple times
* saleprice: what the machine sold for at auction (only provided in train.csv)
* saledate: the date of the sale 
