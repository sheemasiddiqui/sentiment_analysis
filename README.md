# Sentiment Analysis

### Summary
This project involves analyzing a dataset of customer product reviews using natural language processing (NLP) techniques and machine learning algorithms. 
The dataset consists of reviews of a particular product, and the project aims to determine the sentiment of the reviews and classify them as positive or negative.

### Exploratory Data Analysis (EDA)
The project starts by importing the necessary libraries and loading the dataset into a pandas dataframe.
It then performs exploratory data analysis (EDA) to gain insights into the data, such as the number of rows and columns, 
the number of missing values, and the distribution of the score column. The EDA includes creating various visualizations, such as histograms and word clouds, 
to represent the data.

### Using Natural Language Processing (NLP) Techniques to find Tone of product reviews
Next, the project applies data cleaning techniques to the text column by removing special characters and converting all text to lowercase. 
It then uses the TextBlob library to perform sentiment analysis on the reviews, which involves calculating the polarity and subjectivity of each review.
The project also creates a target column for the reviews based on their score and applies a specific threshold to classify them as positive or negative.

### Classification, Prediction, and Evaluation of Model chosen
Finally, the project uses the TF-IDF vectorization technique to convert the cleaned review text into numerical features and trains a logistic regression
model to predict the sentiment of the reviews. The project evaluates the performance of the model by creating a confusion matrix and an ROC curve. 
Overall, this project successfully assesses the sentiment of the reviews and classifies them as positive or negative with high accuracy using NLP 
and machine learning techniques.
