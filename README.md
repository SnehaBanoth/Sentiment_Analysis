# Sentiment Analysis
Title: Data Pipeline for Sentiment Analysis on Weather Tweets using Twitter API and OpenWeather API

The data pipeline consists of the following steps;
1. Data Ingestion: Streaming-in tweets related to weather using Twitter API and fetch the actual
weather data for several cities using the OpenWeathermap API.

2. Data Processing: To bring the text (tweet) to input shape, that could be fed into the ML model
i) Cleaning the data (remove stopwords, #hashtags, replace smileys with text, etc) 
ii) Tokenization
iii) Vectorization

3. Machine Learning model: A batch dataset containing 1.6 million labelled tweets is used to train the machine learning model. It is a binary classification problem, since the tweets are labelled as either positive or negative.

4. Predictions: The trained model is used to predict the sentiment of preprocessed stream of tweets 

5. Data Visualization: The predictions of sentiment of tweets by the machine learning model and
actual weather are visualized on Kibana
