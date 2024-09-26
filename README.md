# Fake News Detection Project

## Overview
This project aims to detect fake news using machine learning techniques. It leverages a dataset of news items labeled as either "Fake" or "Real". The primary goal is to create a robust classifier capable of distinguishing between fake and real news articles based on their content.

##  Why Fake News Detection?
With the rapid spread of information through digital channels, distinguishing between real and fake news is critical. Misinformation can have a profound effect on public opinion and societal decisions. This project seeks to contribute to the battle against misinformation by developing a machine learning model to automate fake news detection.

## Dataset
Source: The dataset contains thousands of news items labeled as "Fake" or "Real".
Fields:
Text: Full news article text.
Label: Categorical label indicating whether the article is "Fake" or "Real".
This dataset is ideal for supervised learning tasks, providing a strong foundation for training machine learning models.

# Approach
The project follows these main steps:

Data Loading and Exploration:
Load and examine the dataset to understand its structure and contents.

Data Preprocessing:
Use TfidfVectorizer to convert the text into feature vectors by removing stop words and limiting the vocabulary to relevant words.

Model Building:
Train a Passive Aggressive Classifier to detect fake news. The model is known for its efficiency in binary classification tasks.

Model Evaluation:
Calculate accuracy using test data, and construct a confusion matrix to further evaluate performance.

Libraries Used
pandas: For data manipulation and analysis.

scikit-learn: For model training, evaluation, and preprocessing (e.g., TfidfVectorizer, train_test_split, PassiveAggressiveClassifier).
matplotlib: For visualizing evaluation metrics (e.g., confusion matrix).
# Results
Accuracy: The Passive Aggressive Classifier achieved an accuracy of 99.55%, indicating a highly effective model.

Confusion Matrix: This matrix shows how well the model is able to distinguish between fake and real news articles.
