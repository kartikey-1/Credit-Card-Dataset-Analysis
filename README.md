# Credit-Card-Dataset-Analysis-using-KNN-and-DecisionTreeClassification
In this project, two well-known machine learning grouping algorithms—K-Nearest Neighbors (KNN) and Decision Tree Classifier—are used to analyze a credit card dataset. Based on a number of transactional characteristics, the study aims to forecast whether a particular credit card transaction is fraudulent or not.
Data preprocessing, feature engineering, model training, evaluation, and comparison of KNN and Decision Tree models are all demonstrated in this project.

The required libraries include:
pandas
numpy
scikit-learn
matplotlib
seaborn

Dataset Overview
The dataset used in this project is typically a credit card transaction dataset that contains the following features:
Transaction ID: Unique identifier for the transaction.
Transaction Amount: Amount of money spent in the transaction.
Card Holder Information: Demographics and card-related data (e.g., age, location).
Transaction Details: Features capturing characteristics of the transaction.
Target: A binary target variable indicating whether the transaction is fraudulent (1) or legitimate (0).

Data Preprocessing
Before training the models, the dataset must undergo several preprocessing steps:
Handling Missing Data: If any data points are missing, they are handled (either by removing or imputing missing values).
Feature Scaling: Standardize or normalize numerical features to bring them to a common scale, especially for KNN, which is sensitive to the scale of the data.
Feature Selection: Choosing the relevant features for classification.
Train-Test Split: The dataset is split into training and testing sets.

Conclusion
Based on the results of the model evaluation, both the Decision Tree and K-Nearest Neighbors (KNN) classifiers demonstrate excellent performance in predicting fraudulent transactions in the credit card dataset, with accuracies very close to 100%. Specifically:
Decision Tree Accuracy: 99.95%
KNN Accuracy: 99.94%

