# Analysis of Tweets to Gauge Customer Sentiment Towards Airlines
## Contents
The goal of this project was to conduct sentiment analysis on a dataset of tweets centered around customers’ experiences with various American airlines to gauge public sentiment surrounding these airlines. This repository contains the original dataset of US airline tweets, derived from scraping tweets posted in February 2015 about consumer experiences with American airlines. It also contains the code importing necessary packages and the data to begin analysis, the actual process of sentiment analysis through utilizing a transformers API, and the code created to create data visualizations from the dataset. 

## SRC 
### Installing/Building Code
To analyze the data, we imported the pandas and numpy packages. The data file was also read in. For the actual sentiment analysis, we utilized a sentiment analysis pipeline from a transformer, a natural language architecture that can be used to conduct various kinds of analysis on text and audio data. 
### Usage 
This code yields a list of sentiment scores that correspond to a tweet in the dataset. These scores were further grouped based on airline to gauge overall consumer sentiment per airline.

## References 
“Getting Started with Sentiment Analysis Using Python.” Huggingface.co, huggingface.co/blog/sentiment-analysis-python#2-how-to-use-pre-trained-sentiment-analysis-models-with-python.

Kulshrestha, Ria. “Transformers.” Medium, 22 Nov. 2020, towardsdatascience.com/transformers-89034557de14.

Ledsom, Alex. “Airline Ratings World’s Best Airline 2023.” Forbes, 5 June 2023, www.forbes.com/sites/alexledsom/2023/06/05/airline-ratings-worlds-best-airline-2023-awards-air-new-zealand-wins/?sh=2c656e5b3fdd.

Selvaraj, Natassha. “A Beginner’s Guide to Sentiment Analysis with Python.” Medium, 12 Sept. 2020, towardsdatascience.com/a-beginners-guide-to-sentiment-analysis-in-python-95e354ea84f6.



