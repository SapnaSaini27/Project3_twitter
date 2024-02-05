# Project3_twitter

Project Title: Sentiment Analysis on Kaggle Dataset

1. Introduction
Twitter Sentiment Analysis is a data analytics project that involves analyzing a 
dataset of tweets to determine the sentiment expressed in each tweet—whether it 
is positive, negative, or neutral. The project aims to gain insights into public 
opinions, trends, and sentiments shared on Twitter, utilizing data analytics 
techniques.
Dataset can be accessed on Kaggle using this link "https://www.kaggle.com/datasets/kazanova/sentiment140"

3. Data Cleaning
    Null Values:
    I have removed all null values present in the dataset, Fotunately there was not any null value present.

    Duplicate Values:
     I have removed duplicate files using drop_duplicates function.

    Column Naming:
     I have given column name to the columns of the dataset because names are not given already to the columns.
     Column name is an important aspect of the anlysis, without it how we can proceed further for analysis. So I give them name accordingly.

3. Exploratory Data Analysis (EDA)
   From EDA I can conclude that mostly text(tweets) are written in month of June and least in April, as we have only 3 months data (April, May, June)
   And second conclusion is that mostly tweets are written in 50-60 text-lengths. A few tweets are written in 150 or above text-length.

4. Text Preprocessing
Punctuation Removal:
   I have removed Punctuation for viewing the data more cleanly.
Stopword Removal:
 I have removed stopwords because they are not contributing in sentiment analysis.
Special Character Removal:
 After all this some special characters are still remain, so i remove all of this except A-Za-z






