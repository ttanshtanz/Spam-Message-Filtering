# Spam Message Filtering using Naive Bayes Classifier

## Overview
This repository contains code for building a spam message filter using the Multinomial Naive Bayes classifier. The project involves natural language processing (NLP) techniques, including text preprocessing, TF-IDF vectorization, and the application of the machine learning model.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- NLTK
- WordCloud
- Scikit-learn (Sklearn)

## Dataset
The dataset used for this project is sourced from the 'spam.csv' file, containing labeled spam and ham (non-spam) messages.

## Workflow

### Data Cleaning and Exploration
- Removal of unnecessary columns and renaming.
- Exploratory Data Analysis (EDA) to understand message lengths, distribution, and visualization.

### Text Processing
- Removal of punctuation and stopwords.
- Tokenization and lemmatization of words.
- Word Cloud visualization for both spam and ham messages.

### Vectorization
- Bag-of-Words (BoW) vectorization using CountVectorizer.
- TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.

### Machine Learning Model
- Train-test split of the TF-IDF transformed data.
- Implementation of Multinomial Naive Bayes classifier.
- Evaluation of the model using classification reports on training and testing sets.

## Results
- The model demonstrates high precision, recall, and F1-scores for 'ham' (non-spam) messages in both training and testing sets.
- While the model performs well on 'ham' messages, there is room for improvement in accurately classifying 'spam' messages.
