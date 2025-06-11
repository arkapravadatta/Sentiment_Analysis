Sentiment Analysis on ABC News Headlines
📌 Overview
This project performs sentiment analysis on the ABC News "Million Headlines" dataset from Kaggle, comparing different NLP approaches:

Lexicon-based (VADER)

Traditional ML (TF-IDF + Multinomial Naive Bayes)

Transformer-based (DistilBERT)

The goal is to classify news headlines into positive, negative, or neutral sentiments and evaluate model performance.

📂 Dataset
Source: ABC News Million Headlines (Kaggle)

Size: ~1 million headlines (2003–2020)

Preprocessing: Lowercasing, punctuation removal, stopword filtering

🛠️ Approach
Exploratory Data Analysis (EDA)

Sentiment distribution

Most frequent terms

Baseline (Lexicon-Based)

VADER sentiment scoring

Traditional ML Model

TF-IDF vectorization + Multinomial Naive Bayes

LLM-Based Sentiment Analysis

Fine-tuned DistilBERT (distilbert-base-uncased-finetuned-sst-2-english)

Evaluation Metrics

Accuracy, Precision, Recall, F1-Score
