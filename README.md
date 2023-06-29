# Data Science Project

This project focuses on analyzing and classifying reviews using natural language processing (NLP) techniques. The main steps of the project include data cleaning, exploratory data analysis (EDA), sentiment analysis, feature extraction, and classification.

## Table of Contents
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">About The Project</a>
    </li>
    <li>
      <a href="#data-loading">Loading the Data</a>
    </li>
    <li>
      <a href="#data-cleaning">Data Cleaning</a>
    </li>  
    <li>
      <a href="#exploratory-data-analysis">Exploratory Data Analysis</a>
    </li>
    <li>  
      <a href="#sentiment-analysis">Sentiment Analysis</a>
    </li>
    <li>  
      <a href="#feature-extraction">Feature Extraction</a>
    </li>
    <li>
      <a href="#classification">Classification</a>
    </li>
    <li>
      <a href="#performance-evaluation">Performance Evaluation</a>
    </li>
    <li>  
      <a href="#conclusion">Conclusion</a>
    </li>
  </ol>
</details>

## Introduction 
In this project, we analyze a dataset of reviews using NLP techniques. The goal is to classify reviews based on their sentiment using machine learning algorithms. The steps involved in the project include data loading, cleaning, EDA, sentiment analysis, feature extraction, and classification.

## Data Loading 
The dataset is loaded from a CSV file. The file is uploaded and then read into a Pandas DataFrame.

## Data Cleaning 
The data cleaning process involves removing any missing values from the dataset and applying text-cleaning techniques to prepare the reviews for analysis.

## Exploratory Data Analysis (EDA) 
EDA is performed to gain insights into the dataset. This includes analyzing the dimensions of the dataset, examining the distribution of scores, visualizing the distribution of the score column, and calculating the number of words per review.

## Sentiment Analysis 
Sentiment analysis is performed using the TextBlob library. The polarity and subjectivity of each review are calculated and added as new columns to the DataFrame.

## Feature Extraction 
TF-IDF (Term Frequency-Inverse Document Frequency) is used to extract features from the cleaned review text. The TF-IDF vectors are computed for further analysis and classification.

## Classification 
A logistic regression model is trained on the TF-IDF vectors to classify the reviews into positive or negative sentiments. The model is evaluated using performance metrics such as accuracy, precision, recall, and F1-score.

## Performance Evaluation 
The performance of the classification model is evaluated using a confusion matrix, ROC curve, and various metrics including accuracy, precision, recall, and F1-score.

## Conclusion 
In this project, I successfully analyzed and classified reviews using NLP techniques. The classification model achieved good performance on sentiment classification, as evidenced by the evaluation metrics. The project demonstrates the application of NLP, data cleaning, EDA, feature extraction, and classification techniques in the domain of sentiment analysis.
