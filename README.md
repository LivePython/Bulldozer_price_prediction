# Bulldozer_price_prediction
This is a Kaggle competition project done during my Data science and Machine Learning class

In this notebook, we are going to go through an example machine learning project with the goal of predicting the sale price of bulldozers

Problem Definition
How well can we predict the future sale price of a bulldozer, given its chracteristics and previous examples of how much similar bulldozers have been sold for?

Data
The three data set available are:

1. Train.csv is the training set, which contains data through the end of 2011.
2. Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012.
3. Test.csv is the test set.

Note: The data we are using were already downloaded from Kaggle Bluebook for Bulldozers competition. The source of the data is: https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices. For more on evaluation of this project check: https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation

Note: The goal for most regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a machine learning model which minimises the RMSLE.

Features
Kaggle provides a data dictionary of details of all the features of the dataset. You can view this data dictionary on Google sheets: https://docs.google.com/spreadsheets/d/1DtmBZsmHnKbAJbSWvOfN4Yyk-GijvJhM4oepIpEfx_g/edit#gid=2070077111

**In conclusion**: From the analysis conducted we observed that the year the machine was made greatly affects the sales of the machine. Other factors also contributed, but the production year (YearMade) has more impact on the sale. From this analysis, I can state clearly to the clients that more emphasy be given to advertisement to propective buyers about newly produce machines. This aweness will bring the machine to the buyers and exponentially increase their sales to maximize profits. 

