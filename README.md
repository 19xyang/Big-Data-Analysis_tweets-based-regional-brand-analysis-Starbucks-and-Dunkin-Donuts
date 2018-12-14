# Tweet Based Regional Brand Analysis — Starbucks vs Dunkin Donuts
Columbia University EECS6893 Big Data Final Project -- Xi Yang (xy2378), Fan Wu(fw2322), Geqi Yan(gy2366)


## Directory
```
Tweet Based Brand Analysis — Starbucks vs Dunkin Donuts
|
+--sentiment analysis
|   +--sentiment+analysis+starbucks.ipynb
|   +--sentiment+analysis+starbucks.py
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
```
* 1.Directory data collection contains source code for crawling tweets from internet, we have two filters: the location and the key words which refer to the brand names. We collect tweet data for 48 states in USA except Hawaii and Alaska.
* 2.Directory sentiment_analysis contains a ipython notebook. This part is implemented in databricks, connected with AWS. Using pyspark to train an sentiment classifier and do sentiment prediction for tweets we scrawled.
* 3.Directory visualization contains one java script file and three html files. We draw three popularity map to demonstrate the popularity of each brand in different states in United States. We also draw a final map which shows the more welcomed brand in each state.
