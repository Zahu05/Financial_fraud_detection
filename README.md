# Financial_fraud_detection

This project implements a financial fraud detection system using machine learning techniques. It uses a Random Forest Classifier to predict fraudulent transactions based on various features such as transaction type, amount, and account balances.
DATASET Info
This is a sample of 1 row with headers explanation:

1,PAYMENT,1060.31,C429214117,1089.0,28.69,M1591654462,0.0,0.0,0,0

step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount -
amount of the transaction in local currency.

nameOrig - customer who started the transaction

oldbalanceOrg - initial balance before the transaction

newbalanceOrig - new balance after the transaction.

nameDest - customer who is the recipient of the transaction

oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

Dataset used:
https://www.kaggle.com/datasets/ealaxi/paysim1

Features
Fraud Prediction: Classifies transactions as fraudulent or non-fraudulent.
Web Application Interface: A simple Flask web app that allows users to input transaction details and receive a fraud prediction.
Model and Scaler: The model is trained using financial transaction data, and the scaler ensures that the input features are properly normalized before prediction.



https://github.com/user-attachments/assets/2ecf3351-ec28-4e80-8931-d311cba65c91





Technologies Used
Python: Programming language used for model training and web application.
Flask: Web framework to build the application.
Random Forest Classifier: Machine learning algorithm for classification.
Scikit-learn: For building and evaluating the model.
Joblib: Used for saving and loading the trained model and scaler.
Pyngrok: To expose the Flask app to the public internet for testing purposes.
