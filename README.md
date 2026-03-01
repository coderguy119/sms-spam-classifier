# sms-spam-classifier

This project builds a machine learning model to classify SMS messages as spam or not spam using Python and Naive Bayes. 
It demonstrates the workflow of supervised learning and natural language processing (NLP).

## Features
- Text preprocessing (lowercasing, stopword removal)
- Converts text to numerical features using CountVectorizer with n-grams (1-2 words)
- Multinomial Naive Bayes classifier
- Accuracy evaluation on real SMS spam dataset
- Function to test custom messages

## Libraries Used
- pandas
- scikit-learn

## Accuracy Achieved
- ~0.97 (on test set of real SMS dataset)
- Note: Accuracy may vary slightly depending on train/test split.
