# Data Analysis for Predicting Attacks in Smart Systems Using AI Techniques

## Project Overview
This project investigates the application of artificial intelligence and machine learning techniques to predict and detect cyber attacks in smart systems. The study focuses on analyzing system-level data to identify abnormal behavior and improve early attack detection in smart and connected environments.

## Problem Statement
Smart systems and smart city infrastructures are increasingly vulnerable to cyber attacks such as DDoS attacks. Traditional security mechanisms often fail to detect complex and evolving attack patterns. This project aims to enhance predictive security capabilities using data-driven AI models.

## Dataset Description
- Number of instances: 82,333
- Number of features: 45
- Target: Attack / Normal behavior
- Data characteristics:
  - Mixed numerical and categorical features
  - Presence of missing values and outliers
  - Class imbalance

## Data Preprocessing
The following preprocessing steps were applied:
- Handling missing values
- Outlier treatment
- Feature normalization and standardization
- Categorical encoding
- Class imbalance handling

## Methodology
The project evaluates both traditional machine learning and deep learning models.

### Machine Learning Models
- Logistic Regression
- Decision Tree
- Hyperparameter tuning using GridSearchCV

### Deep Learning Models
- SimpleRNN
- LSTM
- GRU
- CNN
- Training optimization using:
  - EarlyStopping
  - ReduceLROnPlateau

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Key Results
- Decision Tree achieved the best performance after optimization:
  - Accuracy: 0.9236
  - F1-score: 0.929
- Deep learning models showed noticeable improvement after applying training optimization techniques.
- SimpleRNN demonstrated the most consistent performance improvement among DL models.

## Tools & Technologies
- Python
- Scikit-learn
- TensorFlow / Keras
- Pandas & NumPy
- AI-based cybersecurity analytics

## Project Status
This repository documents the research methodology and results. Code reconstruction based on the published methodology is planned for future updates.

## Authors
Reem Mushari Albalawi, Shrouq Khalaf Alaazi, Thuraya Saeed Alshahrani, Tahani Mohammed Alanazi, Wejdan Alomrani
