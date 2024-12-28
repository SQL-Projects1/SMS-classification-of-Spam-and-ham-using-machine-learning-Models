# SMS-classification-of-Spam-and-ham-using-machine-learning-Models
Project Goal:

The project aims to build a machine learning model to classify SMS messages as either "ham" (legitimate) or "spam" (unsolicited). It uses a Linear Support Vector Classifier (LinearSVC) model for this purpose.

Steps:

Data Loading and Preparation:

Loads the SMS dataset from a CSV file (spam.csv).
Cleans the data by removing unnecessary columns.
Splits the data into training and testing sets.
Feature Extraction:

Uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert text messages into numerical representations. This step is crucial for machine learning models to understand the text data.
Model Training:

Trains a LinearSVC model using the training data. This involves feeding the model the TF-IDF representation of the messages and their corresponding labels (ham or spam).
Model Evaluation:

Evaluates the model's performance on the testing data using metrics such as accuracy and a classification report (including precision, recall, and F1-score).
Testing and Prediction:

Defines a function predict_spam to predict the class of new SMS messages.
Demonstrates the model's usage by predicting the class of various sample messages.
Libraries Used:

pandas
scikit-learn (for model selection, feature extraction, model training, and evaluation)
