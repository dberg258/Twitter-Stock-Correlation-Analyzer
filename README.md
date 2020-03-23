# Twitter-Stock-Correlation-Analyzer
Analyzer for determining the effect of a CEO's twitter account on the stock of his/her respective company. 

This analyzer displays various graphics depicting the correlation between an individual's twitter activity and a stock.

This script specifically focuses on the effect of Elon Musk's Twitter activity on the Tesla stock. However, it can easily be adapted to another CEO/stock pair.

## Data

The stock data was obtained using Bloomberg Terminal. There is a csv file in the data folder that contains Tesla's stock data from the last 10 years.

The Twitter data was obtained using Twitter's Premium Developer API. I have provided a script which writes the data from the Twitter API to a csv file. You need to provide your own credentials in the twitter_keys.yaml file. 

