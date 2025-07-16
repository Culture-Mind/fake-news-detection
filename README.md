# Fake News Detection

This project demonstrates a pipeline for detecting fake news using machine learning. It combines real news articles fetched from the NewsAPI with a labeled fake news dataset, processes the data, and trains a classifier to distinguish between real and fake news.

## Features

- Fetches recent real news articles from multiple sources using NewsAPI.
- Combines real news with a labeled fake news dataset.
- Preprocesses and vectorizes news text using `CountVectorizer`.
- Trains a `PassiveAggressiveClassifier` to classify news as REAL or FAKE.
- Evaluates model performance with accuracy and confusion matrix.
- Supports evaluation on a separate test dataset.

## Requirements

- Python 3.8+
- pandas
- scikit-learn
- matplotlib
- python-dotenv
- newsapi-python

Install dependencies:
```sh
pip install pandas scikit-learn matplotlib python-dotenv newsapi-python
