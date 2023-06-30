# CreditCardFraudDetection

Credit Card Fraud Detection
This project focuses on detecting credit card fraud using machine learning techniques. The goal is to develop models that can accurately classify credit card transactions as either legitimate or fraudulent. The project utilizes various algorithms such as Decision Trees, K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), Random Forest, and XGBoost for classification.

Dataset
The dataset used for this project is creditcard.csv. It contains a large number of credit card transactions labeled as fraudulent (Class = 1) or legitimate (Class = 0). The dataset includes features such as transaction amount, time, and anonymized information about the transaction.

Data Preprocessing
Before training the models, the data undergoes preprocessing steps. Some of the key preprocessing steps include:

Removing transactions with an amount of 0, as they are considered irrelevant.
Scaling the transaction amount using the StandardScaler to normalize the data.
Model Training and Evaluation
The following classification algorithms are implemented and evaluated:

Decision Tree: A decision tree classifier is trained with a maximum depth of 4 and entropy as the criterion.
K-Nearest Neighbors (KNN): The KNN classifier is trained with a value of K = 7.
Logistic Regression: Logistic regression is applied as a linear classifier.
Support Vector Machines (SVM): SVM is utilized with default parameters.
Random Forest: A random forest classifier with a maximum depth of 4 is trained.
XGBoost: XGBoost classifier is trained with a maximum depth of 4.
The models are evaluated using accuracy score and F1 score metrics to measure their performance in detecting fraud transactions.

Results
The accuracy and F1 scores achieved by the models are as follows:

Decision Tree: Accuracy score = 99.94% and F1 score = 0.825
K-Nearest Neighbors (KNN): Accuracy score = 99.95% and F1 score = 0.8349
Logistic Regression: Accuracy score = 99.91 and F1 score = 0.7027
Support Vector Machines (SVM): Accuracy score = 99.93% and F1 score = [F1 Score]
Random Forest: Accuracy score = 99.93%
XGBoost: Accuracy score = 99.95% and F1 score = 0.8487
Based on the evaluation, the XGBoost model achieves the highest accuracy score of 99.95%.

