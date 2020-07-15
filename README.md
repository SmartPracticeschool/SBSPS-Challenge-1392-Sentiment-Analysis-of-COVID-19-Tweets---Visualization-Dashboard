# SBSPS-Challenge-1392-Sentiment-Analysis-of-COVID-19-Tweets---Visualization-Dashboard

Sentiment analysis for covid-19 tweets.

Covid-19 analysis notebooks:-
1) covid-analaysis-nltk-vlader.ipynb:- Covid-19 tweets analysis by frst fetching covid-19 related tweets from twitter api by using python tweepy package and saving all the data in csv format.
data like:
username,location,tweets,user-id,hashtags etc.
Data cleaning and final analysis is done by classifying sentence into positive, negative and neutral sentiments.

## Lets move one step further and classify these tweets according to emotions like sad,anger,analytical,fear, etc.

2)Covid-analysis-IBM-tone.ipynb:- In this we will classify according to above emotions for this we will use IBM tone analysis api 
send the data by breaking csv into 2500 rows and get the tone anlalysis in return in the form of list and merge it with our csv .
Since IBM tone analysis only provide free api calls upto 2500. We will use multiple free id for that
 
3)bert_model_sentimental_classification.ipynb:- Now we got classified sentiment thanks with the help of IBM tone analyzer now we can built model.
For building our model we will go by bert-model pretrained ready made base model for text classification made by google which has high accuracy.It can also train at small dataset which is ideal for our situation since we face limited free calls from IBM tone analyzer so we have medium size dataset to train.
we built our model using torch and export bin model for our model deployment.

## Now comes our model deployement which we made by fast-api microframe-work 
we will take tweet text as input and our model will predict our emotions.
we made with the help of microframework fast api which deploys our model very fast and easy to use 

## Flask framework for our model data visualization
Flask framework to deploy our visualization Dashboard.

## Video Links .
https://drive.google.com/drive/folders/1aeDGC_a-PGgZHNvYDajp--dcgTgJALQW?usp=sharing
for our video 

## ppt and document:
idea ppt,
IBM Hack Report 2020.pdf

