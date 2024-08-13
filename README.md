# News_classification

Project Overview

This project focuses on building a machine learning model to classify news articles as either "Fact" or "Fake." We leverage a Support Vector Machine (SVM) classifier to achieve an accuracy of 99%. The dataset used includes a balanced collection of real and fake news, preprocessed for optimal performance.

Table of Contents

Project Overview
Dataset
Installation
Model Training
Evaluation
Results
Usage
Contributing
License
Dataset

The dataset includes labeled news articles where each article is categorized as either "Fact" or "Fake." The data was taken from kaggle https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data after data was preprocessed by removing noise, tokenizing the text, and applying TF-IDF vectorization.

The model is trained using a Support Vector Machine (SVM) classifier, known for its effectiveness in high-dimensional spaces. Key steps in the process include:

Data Preprocessing:
Tokenization
Removal of stopwords
Lemmatization
TF-IDF vectorization
Model Building:
A linear SVM model is trained on the preprocessed dataset.
Hyperparameter tuning is done using GridSearchCV to find the optimal parameters.
Cross-Validation:
The model is evaluated using k-fold cross-validation to ensure robustness.
Evaluation

The SVM model is evaluated on a separate test set to measure its accuracy. The model achieves an impressive 99% accuracy on the test data, indicating its effectiveness in distinguishing between fact and fake news.

Results

The final SVM model demonstrates high accuracy and precision in classifying news articles. The confusion matrix and classification report provide detailed insights into the model's performance, showing strong results across both classes.


