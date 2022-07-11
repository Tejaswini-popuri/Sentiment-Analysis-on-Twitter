# Sentiment-Analysis-on-Twitter
Sentiment Analysis on Twitter using tweepy module
  To be able to use the Twitter APIs, you’ll need to register as a Twitter app developer and obtain keys and access tokens. You’ll need to replace/fill-in the keys and   tokens in config.cfg with your keys and tokens
1. Download the two files tweetering.py and config.cfg from Camino and place them in the same
directory
2. Sign in on https://apps.twitter.com/ using your Twitter account
3. Click on “create new app”
4. Click on your app name
5. Click on “Keys and Access Tokens”
6. In this page, you’ll find a consumer_key, consumer_secret, access_token, and access_token_secret
7. Copy your keys and tokens into config.cfg

First we need to clean up the tweet file content. For each word that is not a
“stop word” (and, the, a, is, as, …), a value +1 is assigned for positive sentiment or a value -1 for
negative sentiment. 
A list of “positive” words, negative words and stop words are included. For the words that is not in
positive/negative/stop words, counted as ‘others’.
• Used the word ‘Trump’ to collect the tweets and performed sentiment analysis
• Used the keyword 'Pfizer' to perform the same analysis again.

Objective:
• What’s the ratio of positive/negative/stop word/others compare to the whole word count?
• What’s the sum of all positive/negative observed? Do you think that the general
sentiment is negative or positive? Weakly or strongly?
