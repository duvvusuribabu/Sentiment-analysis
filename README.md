# Sentiment-analysis on recent government intiative
We used SNScrape to get the most trending hashtags from social media platforms like tiwtter.
snscrape is a python module and it is a scraper for social networking services (SNS). It scrapes things like user profiles, hashtags, or searches and returns the discovered items.
We collected the data and converted into CSV file for further preprocessing and modeling.
We are going to use bag of words, tranformers, BERT to perform sentiment analysis on the gathered data for that we have to import all the required libraries.
Generaly public data is more noisy for that we have to perform data cleaning process where we can remove all the unwanted data using regular expression, stop words, word-tokenization.
Using tranfromers we made a y-label called target where it contains whether the review is positive or not.
Using word cloud we visualize the data that we have and plot a histogram for number of positive reviews and neagtive reviews.
We got unbaised data so we perform random over sampling and text augmentation to handle the unbalanced data.
We use various classification techniques like multinomial naive bayes and logistic regression.
We also did sentiment analysis using BERT(Bidirectional Encoder Representations from Transformers) model.
The main difference between transformers and BERT model is BERT is only an encoder, while the original transformer is composed of an encoder and decoder.

