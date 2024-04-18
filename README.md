# Sentiment Analysis of Twitter Data for Stock Market Prediction using Large Language Model BERT.

## Overview
This project explores the effectiveness of leveraging large language models, specifically BERT, for sentiment analysis on financial tweets to predict intraday movements in the stock market. 
It delves into the inherent sentiment of financial tweets and investigates the practicality of deploying a trading bot guided by insights derived from the trained language model.

## Methodology
1. Preprocessing Data: Removing emojis, hyperlinks tags from tweets.
2. Prepare the Bert NLP model tokenizer to encode tweets
3. Define the Bert NLP Classifier
4. Finetuning BERT
5. Predictions for new data
6. Get all of the stock files to process
7. Random Forest Classifier

## Dataset
1. Stock Data - Gathered Stock news from Multiple twitter Handles regarding Economic news dividing into two parts : Negative(-1) and positive(1). Negative count: 2,106. Positive count: 3,685.
   [Tweet Sentiment Data](https://www.kaggle.com/datasets/yash612/stockmarket-sentiment-dataset)
3. Nasdaq 100 Tweets - All tweets mentioning any NASDAQ 100 Twitter Symbol. From 2016 March to June Made with, Measured Time: 79 days. Total Tweets: About a million.
   [NASDAQ 100 Tweets](https://data.world/kike/nasdaq-100-tweets)

## Results
BOT accurately predicts winning stock 80.19% of the time

![ BOT vs Market ](https://github.com/effaf/stockmarket-LLM/blob/main/resultPlot.png)




## How to Use/Replicate
1. Upload the Jupyter Notebook to Google Colab
2. Upload stock_data.csv in runtime
3. Create a new folder `companyData`
4. In the `companyData` directory, upload the compressed files for each company from `kike-nasdaq-100-tweets` dataset.
5. Run the code blocks sequentially

You can reach out to me at shlok.kothari@rutgers.edu for any questions or concerns!
