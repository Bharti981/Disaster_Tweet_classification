# Disaster_Tweet_classification
Built using Natural Language Processing (NLP), this project leverages various ML algorithms and a Flask-based web application for easy accessibility and deployment.
The nuanced and context-dependent nature of tweets, where terms like “fire” or “flood” may be used metaphorically, adds complexity to the task.
Features
Comprehensive NLP Pipeline: Data cleaning, tokenization, vectorization with TF-IDF, and GloVe word embeddings.

Diverse Model Ensemble: Evaluates multiple models, including Naive Bayes, Logistic Regression, Random Forest, and more. Gaussian Naive Bayes serves as the final model for classification.

Sentiment Analysis Integration: Uses VADER and TextBlob to extract sentiment features from tweet text, enhancing prediction accuracy.

User-Friendly Web Interface: Allows users to input tweet text and receive real-time predictions.

Developed a web application: Developed a web application using Flask

Project Structure
Data Preprocessing: Handles text cleaning, tokenization, stopword removal, stemming, and vectorization with TF-IDF.

Feature Engineering: Adds sentiment scores from VADER and TextBlob, as well as tweet structure features (hashtags, mentions, URLs).

Model Training: Trains, evaluates, and selects from multiple ML algorithms to ensure robust performance.

Web Deployment: A user-friendly Flask web app that predicts disaster tweets in real-time
