<img src="https://github.com/axiom2018/Kaggle-Social-Media-Sentiments/blob/main/sentiment_analysis%20_background.png"/>

## Description
<p align="left">
  Found the dataset on Kaggle. Due to my love for any social media related task I gave it a good shot. This multiclassification dataset, 
  found <a href="https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset">here</a>, has an abnormally 
  HIGH level of classes to predict by default. Specifically 279 as I've seen by using value_counts(). I used a few techniques to
  get it to only Positive, Negative and Neutral, with good results as well. As with my other projects, this one is heavily commented.

  Also this was my <b><i><u>first</u></i></b> time utilizing a HuggingFace model after reading up about them. Definitely was fun and 
  rewarding.

  Project sections
  1) Exploratory Data Analysis
     - Sentiment column/feature
     - Dropping columns
     - Platforms
     - Country
     - Text
     - Year
     - Revisiting the "Sentiment" column for same issue
    
  2) Adjusting "Sentiment" column
     - Identifying positive, negative, and neutral words (using SentimentIntensityAnalyzer from nltks Vader)
     - Applying identified words to dataframe
     - Sentiment column to numerical
    
  3) Tokenization
  4) Dataset
  5) Splitting data & DataLoaders
  6) Model creation and training
     - Training function
     - Evaluation function
     - Epoch training
    
  7) Model evaluation
  8) Predictions

This was pretty fun to do because of HuggingFace. Hope any visitors to this page found it useful!
</p>

