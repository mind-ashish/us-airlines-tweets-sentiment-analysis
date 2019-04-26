# us-airlines-tweets-sentiment-analysis
Given Twitter US Airline Sentiment Dataset, which contains data for over 14000 tweets,
the challenge is to predict the sentiment of the tweet i.e. positive, negative or neutral.

This projects analyses the tweet sentiment of a tweep, &amp; predicts whether a tweet tagging the us-airlines twitter handles , 
is positive , negative or neutral

First the data is pre-processed using nltk.
Then i saved the pre-processed data in a file, so that one can easily use this directly into colab, aws etc.

I used countvectorizer to generate features for data, which uses one-hot encoding 
Then i applied various classifiers and ML models like Neural networks, for prediction.

Predictions from different models are saved in result files.



