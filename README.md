# Fake News Detection Using Machine Learning and NLP

## Overview

Fake news has become a major problem due to the rapid growth of digital media and social networking platforms. This project develops a Machine Learning and Natural Language Processing based system to classify news articles as Fake or Real.

## Objectives

- Detect whether a given news article is fake or real.
- Apply NLP techniques for text preprocessing.
- Convert textual data into numerical features using TF-IDF.
- Compare different Machine Learning algorithms.
- Evaluate model performance using different evaluation techniques.
- Analyze possible overfitting using K-Fold Cross-Validation.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Natural Language Processing
- TF-IDF
- Google Colab

## Machine Learning Models

The following models are implemented and compared:

1. Logistic Regression
2. Random Forest
3. XGBoost

## Methodology

The project follows these steps:

1. Collect fake and real news datasets.
2. Select required records from both datasets.
3. Merge the datasets.
4. Shuffle the combined dataset.
5. Combine title and article text.
6. Clean and preprocess the text.
7. Extract features using TF-IDF.
8. Split the data into training and testing sets.
9. Train Logistic Regression, Random Forest, and XGBoost models.
10. Evaluate model performance.
11. Generate confusion matrix and accuracy comparison graphs.
12. Perform K-Fold Cross-Validation.
13. Test the trained model on new news articles.

## Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- K-Fold Cross-Validation

## Prediction

The trained model accepts a news article as input and predicts:

**Fake News** or **Real News**

## Project Structure

```text
fake_news_detection/
│
├── Fake_News_Detection.ipynb
├── README.md
└── requirements.txt
