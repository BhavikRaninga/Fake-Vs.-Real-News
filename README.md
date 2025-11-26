# Fake News Detection
## Overview
This project uses machine learning to classify news articles as real or fake. It leverages TF-IDF vectorization and Logistic Regression to achieve high accuracy on the Fake vs. Real News dataset.

## Dataset
Source: Kaggle Fake and Real News Dataset

## Steps
Data loading and exploration

Text preprocessing (cleaning, lowercasing, removing stopwords)

Stratified K-Fold Cross-Validation (5 folds)

Model training and evaluation

## Results
Average Accuracy: 98.9%

Precision, Recall, F1-score: ~99% for both fake and real news

## How to Run
Install requirements: pip install -r requirements.txt

Open the notebook in Google Colab:
https://colab.research.google.com/drive/1ZIPbtt85WUh3-ZjMFE20t6syFKpPKsxe#scrollTo=GQbFJI7HVqlp

## About
This project demonstrates the application of NLP and machine learning techniques to identify fake news, a crucial task in today’s digital world.
