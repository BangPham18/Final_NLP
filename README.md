# Final NLP Project

This repository contains the final notebook for an NLP (Natural Language Processing) project, implemented using Python and common machine learning libraries.

## Project Overview

This project focuses on text classification using natural language processing techniques. It walks through a full pipeline including data preparation, feature engineering, model training, and evaluation.

### Data Preprocessing

The following preprocessing steps are applied to the input text data:

- Removal of special characters and punctuation
- Lowercasing all text
- Tokenization (splitting sentences into words)
- Stopword removal (filtering out common words like “and”, “the”, etc.)
- Stemming / Lemmatization (reducing words to their root form)
- Label encoding of target classes
- Data splitting (training/test sets)
![image](https://github.com/user-attachments/assets/43ec0b4a-617f-4c39-b15a-4ba0f1e43117)
![image](https://github.com/user-attachments/assets/5733784f-71d7-449b-9f37-e098298aaebb)

### Feature Extraction

- **TF-IDF (Term Frequency–Inverse Document Frequency)** is used to convert text into numerical feature vectors suitable for training machine learning models.

### Model Used

- XGBoost
- Naive Bayes
- SVM
- LSTM
