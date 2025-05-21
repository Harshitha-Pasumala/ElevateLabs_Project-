# ElevateLabs_Project-
This project focuses on detecting fake news using Natural Language Processing (NLP) and machine learning. Using a publicly available dataset from Kaggle that contains labeled fake and real news articles, the system preprocesses the text data by cleaning, normalizing, and vectorizing it using TF-IDF. A Passive Aggressive Classifier is then trained to classify news articles with an accuracy of approximately 93%. The project includes a simple web application built with Flask, where users can input a news article and receive a real-time prediction on its authenticity. Future extensions include integrating deep learning models like LSTM and BERT, detecting satire and clickbait, and developing a browser extension to flag suspicious news content directly on web pages. This project demonstrates a practical approach to addressing the problem of misinformation using NLP and machine learning.
How It Works
Preprocessing:
Lowercasing
Removing punctuation and stopwords
Combining headline and text for full context
Vectorization:
TF-IDF used to convert text to numerical vectors
Model:
Passive Aggressive Classifier: Excellent for sparse and high-dimensional data like text
| Metric           | Value                              |
| ---------------- | ---------------------------------- |
| Accuracy         | \~93%                              |
| Confusion Matrix | Balanced false positives/negatives |
