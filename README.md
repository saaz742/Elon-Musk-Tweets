# Elon-Musk-Tweets

Get tweets from Twitter API or prepare a dataset and analyze it.

- [First version without comparison for MIR](https://github.com/saaz742/elon-musk-tweets/blob/main/elon_musk_tweets.ipynb)
- [Second version with comparison for NLP](https://github.com/saaz742/elon-musk-tweets/blob/main/elon_musk_tweets_v2.ipynb)
    
## Introduction

First, I get tweets from Twitter API and save them in a CSV file, but Twitter API is not free, so it is better to use a prepared dataset.

Here I use the Kaggle dataset to get tweets and analysis them. ("elonmusk.csv" include 12205 tweet with other data about each tweet - "musk-tweets-2010-to-2018.csv" include 6094 tweets)

## Table of contents
- Load the data
    - kaggle dataset / crawling Twitter API
    - Read CSV
- Preprocess the data
  - Tokenize the data
  - Normalize the data
  - Lemmatize the data
  - Stem the data
  - Stopwords
  - Rejoin the tokens
- Cloudwords 
    - Most important words and visualize
- Spacy 
    - Names type
- Sklearn CountVectorizer 
    - Matrix of token counts
- Negative and positive tweets, percantage and visualize
