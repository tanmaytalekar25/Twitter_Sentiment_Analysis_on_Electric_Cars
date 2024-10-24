# Twitter_Sentiment_Analysis_on_Electric_Cars

## Objective:

Build a model to analyze tweet sentiments.

Check if sentiment correlates with Tesla stock price movements.

## Data:

Collected 43983 tweets with the keyword "Electric cars" and likes > 10 using the Twitter API from 1st Jan 2018 to 31st Dec 2020.

Cleaned the data using the NLTK package by removing duplicates, URLs, special characters, and applying lemmatization and tokenization.

## Methodology:

Word2Vec: Converted words into vectors using word embeddings, trained on a large corpus of text.

K-Means Clustering: Grouped words into three clusters (positive, negative, neutral) based on sentiment.

Sentiment Distribution: Positive (55%), Neutral (40%), and Negative (5%).

## Tesla Stock Analysis:

Stock movement direction determined using Moving Averages (5, 10, 15-day).

Combined sentiment with stock trends, resulting in a 51% accuracy in predicting true stock movements (compared to 37% using Moving Averages alone).

## Conclusion: 

Incorporating tweet sentiments increased prediction accuracy by 14%, indicating that sentiments have an influence on stock movements.
