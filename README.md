# Python_SentimentAnalysis_SVM
An interactive Streamlit application for performing sentiment analysis on tweets related to fuel (BBM) quality on the X platform (Twitter), using a full NLP pipeline and Support Vector Machine (SVM) classification. This is 2025 Project

## Key Features
1. Complete Text Preprocessing Pipeline
* Case folding
* Text normalization (slang-to-formal mapping)
* Stopword removal
* Stemming using Sastrawi

2. Lexicon-Based Sentiment Scoring
* A positive lexicon (positif.csv)
* A negative lexicon (negatif.csv)
* Each word is weighted, and overall sentiment is categorized as Positive, Negative, or Neutral.

3. Exploratory Data Analysis (EDA)
* Sentiment-distributed dataset
* Sentiment counts
* Wordclouds for positive and negative sentiments

4. TF-IDF & Feature Selection
* TF-IDF Vectorizer (uni-gram & bi-gram)
* Chi-Square (SelectKBest)

5. Support Vector Machine (SVM) Model Training
* Scenario 1 — 500 Best Features
* Scenario 2 — Best Performance
* Classification report
* Confusion matrix (heatmap)

6. In-App Sentiment Prediction
* Preprocessing
* TF-IDF transformation
* Feature selection
* SVM classification
* Output: Positive / Negative / Neutral
