# Text-classification-with-Python

Project Overview

The objective of this project is to create a classification model that classifies tweets with different sentiments using machine learning algorithms. The dataset can be found a: 

http://bit.ly/VaccinationsDS.

Prerequisites

**1. Data Exploration**

Basic understanding of dataset size and characteristics through .shape and .sample() methods.

Explore and balance the dataset by sampling equal tweets from each sentiment category (neutral, negative, positive).

**2. Data Preparation**

Ensure data types are appropriate and check for missing values using .dtypes and .isnull().sum().

Implement text cleaning through removal of URLs, hashtags, and stopwords, followed by lemmatization.

**3. Text Processing**

Use the text_cleaning function to remove unnecessary elements from the tweets.

Apply feature engineering techniques to extract additional features like word count, noun, verb, and adjective counts, polarity, and subjectivity.

**4.Feature Construction**

Create features using word-level and character-level n-gram TF-IDF vectors.

Convert categorical values (neutral, positive, negative) to numerical labels (0, 1, 2).

Combine TF-IDF matrices and metadata features into a single feature matrix for modeling.

**5. Data Modeling**

Split data into training and testing sets using train_test_split.

Use various classifiers including Logistic Regression, Decision Tree, SVM, KNN, Naive Bayes, and ensemble classifiers like Random Forest, AdaBoost, and Gradient Boosting.

Install and apply XGBoost

**6. Model Evaluation**

Evaluate models using accuracy scores, confusion matrix, and classification reports.

Choose the most reliable models based on balanced dataset performance.

This covers the full flow of data preprocessing, feature engineering, modeling, and evaluation required to build a sentiment classification model
