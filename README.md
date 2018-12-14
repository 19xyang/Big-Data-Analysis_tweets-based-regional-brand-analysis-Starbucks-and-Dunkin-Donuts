# Big-Data-Analysis_tweets-based-regional-brand-analysis-Starbucks-and-Dunkin-Donuts
Columbia University EECS6893 Big Data Final Project -xy2378 fw2322 gy2266
*1.Directory data collection contains source code for crawling tweets from internet, we have two filters: the location and the key words which refer to the brand names. We collect tweet data for 48 states in USA except Hawaii and Alaska.
*2.Directory sentiment_analysis contains a ipython notebook. This part is implemented in databricks, connected with AWS. Using pyspark to train an sentiment classifier and do sentiment prediction for tweets we scrawled.
*3.Directory visualization contains one java script file and three html files. We draw three popularity map to demonstrate the popularity of each brand in different states in United States. We also draw a final map which shows the more welcomed brand in each state.

# Read Me
* 1.File tweet_crawl contains source code for crawling tweets from internet, this part is from https://github.com/Jefferson-Henrique/GetOldTweets-python
* 2.Directory data_cleaning_tf_idf contains two python files. 
tweet_cleaning.py is used for cleaning raw twitter data and make them standardized and easy for future use.
tfidf_count.py is used for calculating tf-idf in different files. It would import tweet_cleaning.py for tweet data. In order to suit for twitter data, this part is modified from http://stevenloria.com/finding-important-words-in-a-document-using-tf-idf/
* 3.Directory sentiment_analysis contains a ipython notebook. This part is implemented in databricks, connected with AWS. Using pyspark to train an sentiment classifier and do sentiment prediction for tweets we scrawled.
* 4.Directory visualization_code contains several ipython notebooks. These python codes do visualization on tweets.

