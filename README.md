# creditcard-fraud-detection-Exploratory-Analysis-
This project analyzes and predicts fraudulent credit card transactions using machine learning models. The main focus is on handling class imbalance and improving fraud detection rates.

*Data Loading:-
The credit card transactions dataset is loaded for analysis. Features are anonymized, and the Class column indicates fraud (1) or normal (0) transactions.

*Data Exploration:-
Overview of dataset shape and information.
Checking class distribution (extremely imbalanced dataset).
Basic visualization to understand transaction amounts and class imbalance.

*Data Preprocessing:-
Feature scaling: Standardization is applied to the Amount and Time features.
Dropping irrelevant columns if necessary.
Splitting data into training and testing sets (using an 80-20 split).

*Handling Imbalance:-
Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset by oversampling the minority class (fraudulent transactions).

*Model Building Trained and evaluated multiple machine learning models:-
-Logistic Regression
-Decision Tree Classifier
-Random Forest Classifier

*Model Evaluation:-
Evaluated using Confusion Matrix, Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
Special focus was given to Recall because correctly identifying fraud is more important than overall accuracy.

*Final Insights:-
Random Forest performed best among the models, achieving a strong balance between recall and precision after applying SMOTE.

*Technologies Used:-
Python 3

*Libraries:-
pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

*Dataset:-
The dataset used: Credit Card Fraud Detection (Kaggle)
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code
Contains transactions made by European cardholders in September 2013.
Highly imbalanced with only 0.172% fraudulent transactions.

*Results:-
Random Forest achieved the best performance after SMOTE resampling.
Emphasis was placed on Recall to minimize false negatives (i.e., missing fraudulent transactions).


for code go to https://github.com/pranavdusane/creditcard-fraud-detection-Exploratory-Analysis-
