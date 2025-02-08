# Twitter Sentiment Analysis for Public Health

## Project Overview
This project focuses on sentiment analysis of Twitter posts related to public health. The primary objective is to classify tweets into three categories: **Positive, Negative, and Neutral**. The initial dataset encountered issues with **NaN values**, leading to inconsistencies in model training. To resolve this, a **synthetically generated** dataset was used, ensuring a balanced distribution of classes.

## Features of the Project

### Data Preprocessing
- Text cleaning (removal of links, punctuation, and special characters)
- Lowercasing and tokenization
- Removing stopwords and unnecessary whitespace

### Sentiment Labeling
- **Positive (1)**
- **Negative (0)**
- **Neutral (2)**

### Machine Learning Models Used
- Logistic Regression
- Random Forest
- Naive Bayes

## Dataset
The initial dataset had missing values (**NaNs**), affecting the model's learning capability. To overcome this issue, a **synthetic dataset** was generated to simulate real-world Twitter data while maintaining a balanced class distribution.
