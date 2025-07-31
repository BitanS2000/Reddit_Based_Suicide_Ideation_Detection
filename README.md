# Reddit_Based_Suicide_Ideation_Detection
## Project Overview
This project develops a machine learning model to automatically identify varying levels of suicide risk from Reddit posts. Leveraging natural language processing (NLP) techniques, including text embeddings and emotion/sentiment features, the model classifies posts into multiple risk categories with a focus on early detection.

## Key Features
Multi-class classification: Detects multiple levels of suicide ideation risk from social media text.

Feature engineering: Combines advanced text embeddings with emotional and sentiment signals for richer context.

Imbalance handling: Employs SMOTE oversampling to address class imbalance in the dataset.

Modeling: Uses XGBoost classifier optimized through hyperparameter tuning for robust performance.

Results: The optimized model achieves strong accuracy and balanced precision/recall across all classes, particularly excelling in detecting high-risk posts which are essential for suicide prevention efforts.

## Repository Contents
Data processing: Scripts for feature extraction and dataset preparation.

Model training: Code for XGBoost training with hyperparameter tuning and SMOTE oversampling.

Visualization: Confusion matrix and feature importance plots.
