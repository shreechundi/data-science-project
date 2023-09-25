# Analysis of Tweets to Gauge Customer Sentiment Towards Airlines
## Contents
The goal of this project was to conduct sentiment analysis on a dataset of tweets centered around customers’ experiences with various American airlines to gauge public sentiment surrounding these airlines. This repository contains the original dataset of US airline tweets, derived from scraping tweets posted in February 2015 about consumer experiences with American airlines. It also contains the code importing necessary packages and the data to begin analysis, the actual process of sentiment analysis through utilizing a transformers API, and the code created to create data visualizations from the dataset. 

## SRC 
### Installing/Building Code
To analyze the data, we imported the pandas and numpy packages. The data file was also read in. For the actual sentiment analysis, we utilized a sentiment analysis pipeline from a transformer, a natural language architecture that can be used to conduct various kinds of analysis on text and audio data. 
### Usage 
This code yields a list of sentiment scores that correspond to a tweet in the dataset. These scores were further grouped based on airline to gauge overall consumer sentiment per airline. 


