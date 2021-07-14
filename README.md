# Disaster Tweets Analysis (First NLP Project)
In this project I participated in [a kaggle competition](https://www.kaggle.com/c/nlp-getting-started) that analyzes tweets and attempts to correctly identify tweets that signals real disasters from miscellaneous tweets. The project was executed in a colab notebook.  

The project implemented three classifier algorithms (XGBoost, Logistics regression and Multinomial Naive Bayes classifiers) and two texts transformers (CountVectorizer and TFIDF Vectorizer) to find techniques that generate a higher predictive accuracy.

The Tasks were broken down into four steps:  
1. Exploratory Data Analysis
2. Data Cleaning
3. Modelling and
4. Prediction

From the three algorithms used for prediction, Multinomial Naive Bayes classifier combined with count vectorizer performed better than XGBoost and Logistic regression classifiers combined with TFIDF Vectorizer, with an `f1` score of `0.6627`, `0.3736` and `0.5938` respectively. Thus, predictions on the test dataset was done using the **MNB Classifier** and achieved a public score of `0.79803` on the [leaderboard](https://www.kaggle.com/c/nlp-getting-started/leaderboard)