# Quora Sincere/Insincere Questions Classification

## Overview
This project aims to classify questions posted on Quora into "sincere" or "insincere" categories, enhancing the quality of content and interactions on the platform. Utilizing various machine learning models and natural language processing techniques, this repository contains all the necessary code and documentation for setting up, training, and evaluating the classifiers.

## Problem Statement
Identify and classify questions from Quora into sincere or insincere categories, based on their likelihood to be genuine inquiries or problematic content that may violate Quora's "Be Nice, Be Respectful" policy.

## Dataset
The dataset used is the [Quora Insincere Questions Classification dataset from Kaggle](https://www.kaggle.com/c/quora-insincere-questions-classification).

## Features
- `qid`: Unique question identifier
- `question_text`: Text of the question
- `target`: Label (0 for sincere, 1 for insincere)

## Models Used
- Logistic Regression
- Naïve Bayes
- Convolutional Neural Network (CNN)
- BERT (Bidirectional Encoder Representations from Transformers)

## File Descriptions
- `train.csv`: Training data containing the features and target labels.
- `test.csv`: Test dataset for model evaluation.
- `models.py`: Contains the implementation of the machine learning models.
- `preprocess.py`: Script for data cleaning and preparation.
- `train.py`: Script for model training.
- `evaluate.py`: Evaluation of models using accuracy, precision, recall, and F1 score.

## Authors
- **Nainil Rajendra Maladkar** - *Data Preprocessing, Model Implementation* - maladkar.n@northeastern.edu
- **Simran Nagpurkar** - *Feature Engineering, Streamlit Application* - nagpurkar.s@northeastern.edu

## Acknowledgments
- Prof. Junwei Huang for guidance and NLP insights.
- Insights from [Medium](https://medium.com/@amitbalharakr93/quora-insincere-question-classification-2f19a973273b) and [Towards Data Science](https://towardsdatascience.com/quora-insincere-questions-classification-d5a655370c47) blogs.
- Kaggle for providing the dataset.

