# SBSPS-Challenge-1392-Sentiment-Analysis-of-COVID-19-Tweets---Visualization-Dashboard

The corona-virus disease is major challenge to the healthcare systems around the world. Many AI companies around the world are working towards finding AI-based solutions. Opinion of people matters a lot to analyze how the propagation of information impacts the lives in a large-scale network like Twitter. One such solution is to understand the COVID-19 tweets by performing sentimental analysis and representing data in the statistical dashboard web application.

## Data Analysis:-
COVID-19 tweets analysis is done by frst fetching coronavirus related tweets from twitter api by using python tweepy package and saving all the data in csv format.
Data parameters like: username,location,tweets,user-id,hashtags etc. Data cleaning and final analysis is done by classifying sentence into positive, negative and neutral sentiments.

### Lets move one step further and classify these tweets according to emotions like sad, anger, analytical, fear, etc.

By using IBM tone analyser we had classified tweets according to given above emotions and used IBM tone analysis api. 
- Send the data, by breaking input data into 2500 rows and get the tone analysis in return in the form of list and merge it with output data file .

## Sentiment Analysis Model:-
For building our model we had used bert pretrained model for text classification which is made by google and having high accuracy. It can also train a small dataset which is ideal. for our situation since we face limited free calls from IBM tone analyzer so we have medium size dataset to train. We had built our model by using torch and export bin model for our model deployment.

## Data Visualization:-
In this dashboard the tweet data results will be displayed in form of statistical bar graphs. We will use matplotlib, seaborn and ploty for displaying proper results.

## Application Deployment:-
We had developed our dashboard by using HTML/CSS and javascript in frontend and flask framework in backend. With the help of microframework fast api we had deployed our sentiment analysis model and used heroku cloud for web application deployment. 

## Video link and user interface output :-
 Google Drive Link:- https://drive.google.com/drive/folders/1YRfeTsEPhGH2ERaXut-gH_12qFB4DG63
 
 
 Youtube Link:- https://youtu.be/mbbF3Orywjc

## Documentation
PPT File:- idea.pptx 
Report:- IBM Hack Report 2020.pdf
Team Name:- SLAY_CODERS

