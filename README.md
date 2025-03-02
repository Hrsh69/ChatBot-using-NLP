# ChatBot-using-NLP

This project is a simple intent-based chatbot built in Python. The chatbot uses natural language processing techniques with NLTK for text processing, scikit-learn's TF-IDF vectorization and Logistic Regression for intent classification, and SQLite for logging conversations.

# Feature
Predefined intents with multiple example phrases and responses
Text preprocessing that removes punctuation, tokenizes, and lemmatizes input sentences
TF-IDF vectorization to convert text into numerical features
Logistic Regression classifier with a configurable confidence threshold to decide on responses
Fallback mechanism when the classifier's confidence is too low
SQLite database integration to log every conversation (including timestamps, user messages, and bot responses)
Debug output for viewing probability distributions during predictions

# Requirements
Python 3.x
nltk
scikit-learn
numpy
sqlite3 (included with Python)


