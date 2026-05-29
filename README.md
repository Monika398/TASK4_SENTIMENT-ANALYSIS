# TASK4_SENTIMENT-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS PRIVATE LIMITED

*NAME*: MONIKA ROUT

*INTERN ID*: CITS376

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION OF TASK2*:

# Sentiment Analysis Using NLP

## Overview

This project focuses on performing Sentiment Analysis on textual data using Natural Language Processing (NLP) techniques in Python. The main objective of the project is to classify text reviews into Positive and Negative sentiments based on their content. Sentiment analysis is one of the most important applications of NLP and is widely used in social media monitoring, customer feedback analysis, product reviews, and opinion mining.

The project was implemented using Python in Google Colab/Jupyter Notebook environment. Various libraries such as Pandas, NLTK, Scikit-learn, and TextBlob were used for data processing, feature extraction, machine learning, and sentiment prediction.

## Tools and Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NLTK
* Scikit-learn
* TextBlob

## Project Workflow

### 1. Data Collection

A sample dataset containing positive and negative text reviews was created manually. The dataset included various customer opinions and feedback related to products and services.

### 2. Data Preprocessing

Text preprocessing is an important step in NLP. The textual reviews were converted into numerical form using the CountVectorizer method from Scikit-learn. This process converts words into vectors so that machine learning algorithms can understand and process textual information.

### 3. Train-Test Split

The dataset was divided into training and testing datasets using the train_test_split() function. The training dataset was used to train the model, while the testing dataset was used to evaluate model performance.

### 4. Model Training

The Multinomial Naive Bayes algorithm was used for sentiment classification. Naive Bayes is a popular machine learning algorithm commonly used in text classification tasks because of its simplicity and efficiency.

### 5. Prediction and Evaluation

The trained model predicted the sentiments of unseen reviews. Model performance was evaluated using accuracy score and classification report metrics such as precision, recall, and F1-score.

### 6. TextBlob Sentiment Analysis

In addition to machine learning classification, TextBlob library was used to calculate sentiment polarity scores. The polarity value determines whether a sentence has a positive, negative, or neutral sentiment.

## Results

The sentiment analysis system successfully classified textual reviews into positive and negative categories. The project demonstrated how NLP techniques and machine learning algorithms can be used together for text classification tasks. The model achieved working predictions and generated sentiment outputs based on textual input.

## Conclusion

This project successfully implemented Sentiment Analysis using NLP techniques and machine learning. It provided practical experience in text preprocessing, feature extraction, sentiment classification, and model evaluation. The project also demonstrated the use of TextBlob for polarity-based sentiment detection. Overall, the project helped in understanding the basics of Natural Language Processing and sentiment analysis using Python.


