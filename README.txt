Bank Marketing Data Analysis-
Overview-

This project involves analyzing the Bank Marketing dataset using machine learning techniques. The dataset contains information about a direct marketing campaign (phone calls) from a Portuguese banking institution. The goal is to predict whether a client will subscribe to a term deposit (y).

Dataset-
The dataset used in this project consists of two parts:

bank-full.csv: The full dataset with 45,211 observations.
bank-additional-full.csv: A more recent dataset with additional attributes and 41,188 observations.
Both datasets are included in the project as zip files (bank.zip and bank-additional.zip).

Project Workflow
Data Extraction:

Extracted the datasets from the zip files.
Data Loading and Preprocessing:

Loaded the datasets into Pandas DataFrames.
Checked for missing values and confirmed no missing data.
Applied Label Encoding to categorical features for compatibility with machine learning algorithms.
Feature Selection:

Selected features (X) and target variable (y) from the bank-additional-full dataset.
The target variable y indicates whether the client subscribed to a term deposit.
Model Training and Evaluation:

Split the data into training and testing sets.
Trained a Decision Tree Classifier on the training data.
Evaluated the model using accuracy, precision, recall, confusion matrix, and classification report metrics.
Visualization:

Visualized the Decision Tree to understand the decision-making process.
Results
Accuracy: X.XX
Precision: X.XX
Recall: X.XX
Confusion Matrix and Classification Report are provided for a detailed breakdown of the model's performance.

Files-
bank.zip: Contains the bank-full.csv dataset.
bank-additional.zip: Contains the bank-additional-full.csv dataset.
decision_tree.png: Visualization of the trained Decision Tree.
Dependencies
Python 3.x
pandas
scikit-learn
matplotlib