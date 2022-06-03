# Predictiing-the-price-of-Bitcoin-and-DogeCoin-using-Random-Forrest-Regression

In this project, i aim to study the impact and forecast bitcoin (BTC) price fluctuation for Bitcoin related tweets from 2019- 2022 and for SpaceX and Tesla Founder Elon Musk’s tweets for the same time frame using sentiment analysis. The bitcoin data i obtained was on a day to day basis, where features were chosen based on the effect any particular feature has on price metrics. I did a lot of data preprocessing considering the noisy dataset of both the tweets as well as the bitcoin data The sentimental analysis I are using is VADER

Guide to run the code

Datasets

The datasets for the code can be downloaded from (https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets) for bitcoin tweets and https://www.kaggle.com/datasets/ayhmrba/elon-musk-tweets-2010-2021 for Elon Musk tweets (only downloaded 2019,2020,2021,2022.csv). And bitcoin historic data can be downloaded from https://finance.yahoo.com/quote/BTC-USD/history/ with time period as Time Period:Dec 31, 2018 - Apr 19, 2022. But downloading many datasets would be tedious, in order to make the process fast. We have included 2 csv files 1. bitcoin_tweets_2021_prices_final.csv 2. elon_bit_doge_final.csv. These 2 small csv files are the result of our rigorous data cleaning and pre-processing and sentiment analysis. After the data was cleaned they were merged with bitcoin historic price data. But the process for cleaning and pre-processing is available in the code file

This way the code can be run from bitcoin_tweets_2021_prices_final = pd.read_csv('bitcoin_tweets_2021_prices_final.csv’), from where the feature selection and model training starts.

In order to import libraries pip install -r requirements.txt can be used
