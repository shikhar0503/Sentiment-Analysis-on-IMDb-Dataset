# Sentiment-Analysis-on-IMDb-Dataset
<img src="1_UkI9za9zTR-HL8uM15Wmzw.png" alt="Figure 1" >

## Introduction
In this notebook, we'll implement a recurrent neural network that performs sentiment analysis. Using an RNN, rather than a feedfoward network is more accurate since we can include information about the sequence of words. 

## Dataset
Data Used to train the model is downloaded from Kaggle.<br>
The labeled data set consists of 50,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the 25,000 review test set.

## Conclusion
The RNN gave results as:-
* Accuracy score = 86.56%
* Recall = 0.85 
* Precision = 11.92
