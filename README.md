# NLP-Pipeline
The notebook goes through the Natural Language Processing (NLP) pipeline, using the [IMDB reviews dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). 

## Preprocessing
The following steps have been followed during the preprocessing stage;

 1. Removal of punctuation marks
 2. Converting to lower case
 3. Tokenization
 4. Removal of stop words
 5. Lemmatization

**Feature Extraction:** 
The data has been transformed into a matrix to be modelled thereafter. The bag of words (count vectorizer) method was used where the occurence of words within a document is represented. 

## Modelling
A number of classification algorithms were applied to the text which is given below, along with the accuracy scores. 
|Algorithm |Accuracy  |
|-|--|
| Gaussian Naive Bayes |0.79464
Multinomial Naive Bayes|0.83048
|Logistic Regression |0.86208 
Support Vector Machine|0.86088

Based on the above results, it can be concluded that the Logistic Regression model is the best fit for the data. 
