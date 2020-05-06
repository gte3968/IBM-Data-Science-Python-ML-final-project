# IBM-Data-Science-Python-ML-final-project
Use 4 types of classifiers to build models for loan outcome (paidoff/collection) predictions based on a data set that contain: age, gender, education, principal loan amount, loan term, loan effective date, and labeled outcome of the loan: paidoff or collection.

KNN (k is scanned and the best one is used); Decision Tree; Support Vector Machine (4 kernel types are evaluated and picked one base on the results); Logistic Regression. 

Each model's performance is evaluated using Jaccard similarity score and F1 score, plus log loss for logistic regression using the model fit from a train_test split with 20% test data. The models are then applied on new unseen test data, and the performance of each model is compared. 

