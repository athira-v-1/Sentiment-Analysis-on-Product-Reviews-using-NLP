# Sentiment Analysis on Product Reviews using NLP

## Description

This project performs Sentiment Analysis on product reviews using Natural Language Processing (NLP) and Machine Learning techniques.  
The goal of the project is to build a model that can predict whether a review is positive, negative or neutral.

The dataset contains cleaned product reviews along with sentiment labels.  
Text preprocessing, TF-IDF vectorization, and multiple machine learning models are used to train and evaluate the sentiment classifier.

## Dataset

The dataset contains the following columns:

- sentiments → sentiment label (positive / negative / neutral)
- review → cleaned review text
- cleaned_review_length → length of review
- review_score → rating score

Only the review and sentiments columns are used for training the model.


## Features

- Text preprocessing using regex
- WordCloud visualization
- TF-IDF vectorization
- Train-test split
- Multiple model training
- Model accuracy comparison
- Best model selection
- Prediction on new reviews

## Models Used

The following machine learning models were used:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest


## Results

Accuracy of models:

- Logistic Regression → 82.95%
- SVM → 87.43%
- Random Forest → 84.91%

SVM achieved the highest accuracy and was selected as the final model.


## Conclusion

The project successfully demonstrates how NLP and machine learning can be used for sentiment analysis.  
The trained model is able to classify product reviews into positive, negative, and neutral categories with good accuracy.

