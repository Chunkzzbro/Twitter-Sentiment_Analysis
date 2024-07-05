# Twitter-Sentiment_Analysis

This repository contains code for a robust sentiment analysis model to classify Twitter tweets as positive, negative, or neutral. The project includes two approaches: one using a pre-trained RoBERTa model and another using Logistic Regression trained on the Sentiment140 dataset.


## Link to the pretrained Roberta model for Tweets: https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment
Short Description : This is a roBERTa-base model trained on ~58M tweets and finetuned for sentiment analysis with the TweetEval benchmark. This model is suitable for English (for a similar multilingual model, see XLM-T).

Reference Paper: TweetEval (Findings of EMNLP 2020).
Git Repo: Tweeteval official repository.
Labels: 0 -> Negative; 1 -> Neutral; 2 -> Positive

# Sentiment140 dataset: https://www.kaggle.com/datasets/kazanova/sentiment140

This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .

It contains the following 6 fields:

1. target: the polarity of the tweet (0 = negative, 4 = positive)

2. ids: The id of the tweet ( 2087)

3. date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

4. flag: The query (lyx). If there is no query, then this value is NO_QUERY.

5. user: the user that tweeted (robotickilldozr)

6. text: the text of the tweet (Lyx is cool)

Tried extracting the tweets from twitter using Tweepy , an open-source python package that provides a way for developers to communicate with the Twitter API but didnt have enough permission to do so. I assume you would need to Basic Access as compared to the Free Access provided by Twitter.


