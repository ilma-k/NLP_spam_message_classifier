# NLP_spam_message_classifier

This project focuses on building a machine-learning model that automatically classifies SMS messages as spam or ham. The dataset contains real SMS messages collected for spam-detection research.

The main steps in project are:

### Data Cleaning & Exploration
Checking for missing values and analyzing dataset imbalance (the data is heavily skewed toward ham messages, about 87% ham and 13% spam).

### Text Preprocessing
Tokenization, stopword removal, lowercasing, POS tagging, lemmatization and converting text into numerical form using NLP techniques such as Bag-of-Words or TF-IDF.

### Model Training
Training a classification models using SVM and Logistic Regression algorithms to distinguish spam from ham messages.

### Evaluation
Assessing the model using accuracy, precision, recall, F1-score, and a confusion matrix to understand performance, especially on the minority spam class.
