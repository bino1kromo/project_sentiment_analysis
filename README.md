# Sentiment Analysis on Tweets and EPerpusdikbud App Reviews 

## Overview
This project focuses on performing sentiment analysis on two datasets: tweets and app reviews from the EPerpusdikbud application. The objective is to classify the sentiments expressed in these texts as either positive, negative, or neutral using machine learning techniques. The project employs Logistic Regression and Naive Bayes algorithms to build predictive models that can effectively identify the sentiment of a given piece of text.

## Objectives
- To analyze sentiments expressed in user-generated content, such as tweets and app reviews.
- To compare the performance of two popular classification algorithms: Logistic Regression and Naive Bayes.
- To provide insights into the user perception of the EPerpusdikbud app, helping in product improvement and customer engagement strategies.

## Datasets
1. Tweets Dataset: This is the sentiment140 dataset. This dataset contains 1.6 billion tweet data points extracted using twitter api. The tweets have been annotated (0 = negative, 2 = neutral, 4 = positive) and can be used for sentiment detection. There are 6 sections namely Target, Ids, Date, Flag, User, and Text.
2. EPerpusdikbud App Reviews: Review data was obtained using Google Play Scraper, which collects reviews from users of the EPerpusdikbud app. The data consists of the content of the review and the score given by the user. After processing, this dataset contains 412 reviews that have been cleaned and processed.

## Tools & Technologies
Programming Language: Python
Libraries: pandas, numpy, nltk, scikit-learn, matplotlib, seaborn, wordcloud

## Project Workflow
1. Data Collection: Scrape or import data from Twitter and Google Play Store.
2. Data Cleaning & Preprocessing: Prepare data for analysis by performing text cleaning, tokenization, and feature extraction.
3. Exploratory Data Analysis (EDA): Understand data patterns, word frequencies, and sentiment distributions.
4. Model Building: Train and evaluate models using Logistic Regression and Naive Bayes classifiers.
5. Model Evaluation: Compare the performance of the models using accuracy and other evaluation metrics.
6. Insights & Recommendations: Derive actionable insights based on the analysis and propose improvements.

created by : meysi supmawati
