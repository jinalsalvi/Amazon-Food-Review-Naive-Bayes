# Amazom Food Review Naive Bayes
## Introduction   
 This python notebook for Amazon food reviews polarity prediction based on the given review data by applying Naive Bayes algorithm which is based on Bayes probability model. To build generalized prediction model first step should be necessary cleaning of data as a part of data preprocessing.    
        
 We will perform following data preprocessing.    
        
 - Removing Stop-words   
 - Remove any punctuations or limited set of special characters like   or . or # etc.   
 - Snowball Stemming the word    
 - Convert the word to lowercase   
         
 Once we the data is cleaned to be processed we'll use below Feature generation techniques to convert text to numeric vector.   
 1. Bag Of Words (BoW)   
 2. Term Frequency - inverse document frequency (tf-idf)   
        
 Using Naive Bayes algorithm we will build model to predict review polarity for each technique.    
     
 __Objective: Given a review determine whether a review is positive or negative  by appling Naive Bayes algorithm and deciding the best Feature generation technique with most important features for positive & negative class. We will generate ROC curve for each model to check the sensibility of model.__   
        
 __Note: As word2vec generate vector with negative valuel we can not use it for Naive Bays algorithm as it accepts positive values only as a imput vector.__   
    
### Download notebook and data from Kaggle
#### https://www.kaggle.com/jinalsalvi/review-prediction-by-naive-bayes
