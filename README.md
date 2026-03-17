# Fake Review Detection using Machine Learning

This project focuses on detecting whether a product review is real or fake using supervised machine learning and natural language processing (NLP) techniques.

## Problem Statement

Fake reviews mislead customers and reduce trust in online platforms. This project aims to automatically identify fake (AI-generated) reviews and distinguish them from genuine user reviews.

## Dataset

This project uses a combination of real and synthetic (AI-generated) reviews:

* OG (Original Reviews): Real customer reviews
* CG (Computer Generated Reviews): Fake reviews generated using a T5 model

A sample dataset (`test.csv`) is included in this repository for reference and testing purposes.

Note: The full dataset used for training is not included due to size constraints.

## Project Workflow

1. Data Cleaning (lowercasing, removing punctuation, stopwords)
2. Text preprocessing using stemming
3. Feature extraction using TF-IDF
4. Train-test split
5. Model training and evaluation

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Naive Bayes
* K-Nearest Neighbors
* XGBoost (Best Performing Model)

## Results

* Accuracy: ~90%
* Precision: ~90%
* Recall: ~90%
* F1 Score: ~90%

XGBoost achieved the best performance with a strong balance between precision and recall.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* NLTK

## Key Highlight

This project combines real-world reviews with AI-generated fake reviews using a T5 model to simulate deceptive behavior and improve detection performance.

## Author

Yalla Divya Reddy
