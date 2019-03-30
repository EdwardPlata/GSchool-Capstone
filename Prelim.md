
### Preliminary Proposal 1

Purpose: Create a news feed platform where I can stream headlining news + content and perform sentiment analysis to say wheather a certain event is positive or negative, then add a metric to state the significance of an event.
- Most Events will be financial related
- Mainly focused on US Treasury Market,
    - S&P, DJI,Russle 2000, F.A.N.G, and other major financial indexes 
    - As well as stream headlining news sources
    - Even twitter with their API
- This will be a way to ease those who depend on financial news to focus more time on investment strategies

1. I will have a dashboard where all this data will be presented
    - Including charts on how often a certain topic has been mentioned the during the week, including present
    - Weather a topic is looked favoritly or not
    - And how prices of indexed have been moving along the same timespan
    
2. I will be attempting to solve how quick newsources affect and how severe the effect may be.
    - To help investorse guage decisions in a more concise version
    - In an all in one packet
  
3. Presented with an interactive dashboard powered by dash and plotly. Running on AWS
    - Will create machine learning models to predict validity of news sources 
    - Sentiment Analysis on all news sources
    - Contantly updating Machine learning model
    - If possible, a neural network on a EC2 p4 instance

4. Data sources will be WSJ, Bloomberg News, FIanncial Times, Google News, Reuters,New York Times, and twitter (mainly to measure popularity on the subject matter)

5. Steps concist of creating a pipeline to gather and store data, and training / implementing a model

### Tools for the job
- news-api
- twitter-api & tweepy
- nltk/Spacy and textblob
- sklearn - tf-idf, vectorize, encoders, etc
- autotldr - summarizing news articles
- beautifulsoup4 - gather whole article, which will be fed to summarizer
- numpy, pandas, seaborn
- Plotly and Dash - for Dashboard capabilities
