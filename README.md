# Twitter-Stock-Correlation-Analyzer
Analyzer for determining the effect of a CEO's twitter account on the stock of his/her respective company. 

This analyzer displays various graphics depicting the correlation between an individual's twitter activity and a stock.

This script specifically focuses on the effect of Elon Musk's Twitter activity on the Tesla stock. However, it can easily be adapted to another CEO/stock pair.

## Data

The stock data was obtained using Bloomberg Terminal. There is a csv file (must be unzipped) in the data folder that contains Tesla's stock data from the last 10 years.

The Twitter data was obtained using Twitter's Premium Developer API. I have provided a script which writes the data from the Twitter API to a csv file. You need to provide your own credentials in the twitter_keys.yaml file. 

## Run

Run all the cells of the jupyter notebook. This will result in many graphs. Some key graphs are presented below.

### Graphs
The following graphs indicate the effect of Elon Musk's Tweets on the stock price. The X-axis represents the tweets during each week of a year. The Y-axis indicates the change in the average price movement of the stock (per minute) from the 30 minutes before a tweet compared to the 30 minutes after a tweet.

This graph considers all of Elon Musk's tweets:
![](./Images/graph%202.png)
This graph groups the tweets based on type:
![](./Images/graph%203.png)
This graph only uses tweets that meet a certain like/retweet threshold (i.e. 100 likes and 30 retweets minimum)
![](./Images/graph%204.png)

This graph shows how Elon Musk tweets more and more each year:
![](./Images/graph%201.png)
