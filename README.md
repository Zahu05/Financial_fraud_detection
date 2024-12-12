# Financial_fraud_detection

This project implements a financial fraud detection system using machine learning techniques. It uses a Random Forest Classifier to predict fraudulent transactions based on various features such as transaction type, amount, and account balances.

Features
Fraud Prediction: Classifies transactions as fraudulent or non-fraudulent.
Web Application Interface: A simple Flask web app that allows users to input transaction details and receive a fraud prediction.
Model and Scaler: The model is trained using financial transaction data, and the scaler ensures that the input features are properly normalized before prediction.

Technologies Used
Python: Programming language used for model training and web application.
Flask: Web framework to build the application.
Random Forest Classifier: Machine learning algorithm for classification.
Scikit-learn: For building and evaluating the model.
Joblib: Used for saving and loading the trained model and scaler.
Pyngrok: To expose the Flask app to the public internet for testing purposes.
