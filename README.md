# Fake News Detection System 

![NLP](https://img.shields.io/badge/NLP-Text%20Classification-blueviolet)
![Sklearn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-99.5%25-green)

## Overview
This project is a comprehensive **Natural Language Processing (NLP)** study aimed at classifying news articles as "Real" or "Fake" with high precision. It serves as a benchmark analysis comparing multiple text preprocessing techniques (Stemming vs. Lemmatization) and machine learning classifiers to determine the optimal pipeline for misinformation detection.

## Key Features
- **Rigorous Preprocessing**:
  - Comparison of **Porter Stemmer**, **Snowball Stemmer**, and **WordNet Lemmatizer**.
  - Stopword removal and noise cleaning (regex).
- **Vectorization Strategies**:
  - **Bag-of-Words (CountVectorizer)** for frequency analysis.
  - **TF-IDF (Term Frequency-Inverse Document Frequency)** for context-aware weighting.
- **Model Benchmarking**: Evaluates and compares:
  - Logistic Regression
  - Linear Support Vector Machines (SVM)
  - Decision Tree Classifiers
- **Visual Analytics**: Word Clouds and class distribution histograms to analyze vocabulary differences between real and fake news.

## Tech Stack
- **Language**: Python
- **NLP Libraries**: NLTK (Punkt, WordNet, Stopwords, POS Tagging)
- **ML Framework**: Scikit-Learn
- **Visualization**: WordCloud, Matplotlib

## Workflow
1. **EDA**: Analysis of dataset balance (~23k Fake vs ~21k True) and frequent terms.
2. **Text Normalization**: Tokenization followed by Lemmatization (using POS tags) to reduce words to their dictionary roots.
3. **Feature Engineering**: Converting text to numerical vectors using TF-IDF.
4. **Training & Evaluation**: 
   - Split data into training and testing sets.
   - Fit models and generate Classification Reports.

## Results
The system achieved near-perfect classification on the test set:

| Model | Accuracy |
| :--- | :--- |
| **Decision Tree** | **99.50%** |
| **Linear SVM** | **99.49%** |
| **Logistic Regression** | *High* |

## 👤 Author
**Deepanshu Sain** *Roll No: 2023UCD2138* *Netaji Subhas University of Technology*
