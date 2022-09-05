## WeRateDogs
In this project Tweepy will be used to query Twitter's API for data included in the WeRateDogs Twitter archive. This statistics will include the number of retweets and favorites. We create a Twitter application before executing our API querying code after which we construct an API object that collects Twitter data. We then write each tweet's JSON data to a tweet json.txt file after querying each tweet ID, with each tweet's JSON data on its own line. We then read this file line by line to generate a pandas DataFrame, then we inspect and clean.

**WeRateDogs** is a Twitter account that scores people's pets and includes a funny comment about the dog. The denominator of these scores is generally invariably ten. But what about the denominators? It is almost usually larger than ten. 11/10, 12/10, 13/10, etc.

Simple put, we will gather, assess, and clean data Twitter Data then act on it through analysis, visualization and/or modeling.
