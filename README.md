# Tweet Based Regional Brand Analysis — Starbucks vs Dunkin Donuts
Columbia University EECS6893 Big Data Final Project -- Xi Yang (xy2378), Fan Wu(fw2322), Geqi Yan(gy2366)
Xi Yang is the owener of this repository. Fan Wu and Geqi Yan mainly worked on the sentiment prediction part. Xi Yang mainly contributed to the data visualization part. All other works such as tweet collecting, further analysis, and report writing are done in group.

For detail, please see the final report.

## Directory
```
Tweet Based Brand Analysis — Starbucks vs Dunkin Donuts
|
+--sentiment analysis
|   +--tweet+cleaning.ipynb
|   +--sentiment+analysis+starbucks.ipynb
|   +--sentiment+analysis+dunkin.py
+--data collection
|   +--got
|         +--...some sample module...
|   +--data+collecting+starbucks.ipynb
|   +--data+collecting+dunkin.ipynb
+--visualization_code
|   +--map_all.html
|   +--map_dunkin.html
|   +--map_starbucks.html
|   +--uStates.js
|   +--word cloud.ipynb
```
* 1.Directory data collection contains source code for crawling tweets from internet, we have two filters: the location and the key words which refer to the brand names. We collect tweet data for 48 states in USA except Hawaii and Alaska. The file tweet+cleaning.ipynb is used to standardize the tweets.
* 2.Directory sentiment_analysis contains two ipynb notebooks for sentiment analysis. In this part, we first use PySpark to train a sentiment classifier and then do sentiment prediction for tweets we collected.
* 3.Directory visualization contains one java script file and three html files as well as two ipynb files. We draw three popularity maps to demonstrate the popularity of each brand in different states in United States and a final map which shows the more welcomed brand in each state. Also, we draw a pie chart to compare the overall sentiment analysis ratio of these two brands. Finally, we draw word clouds of these two brands.
