# Credit_card_Fraud_Detection_Model
This project focuses on detecting fraudulent credit card transactions using machine learning on a highly imbalanced dataset. The dataset includes both legitimate and fraudulent transactions, with fraudulent transaction


Project Description:
----------------------
This project aims to detect fraudulent credit card transactions using machine learning techniques on a highly imbalanced dataset. The dataset contains a mix of legitimate and fraudulent transactions, with fraudulent transactions being significantly less frequent.

Key Steps:
-----------
1)Data Loading and Exploration:

Load the dataset (creditcard.csv) into a Pandas DataFrame.
Inspect the dataset's structure and check for missing values.
Analyze the distribution of legitimate and fraudulent transactions.

2)Data Preprocessing:
----------------------

Separate the dataset into legitimate and fraudulent transaction DataFrames.
Perform statistical analysis on transaction amounts for both classes.
Address class imbalance through under-sampling, creating a balanced dataset.

3)Feature and Target Separation:
---------------------------------

Define features (X) by excluding the Class column.
Define the target (Y) as the Class column.

4)Data Splitting:
------------------

Split the data into training and testing sets (80-20 split) with stratification to maintain class distribution.
Model Training:

Train a Logistic Regression model on the training data.

Model Evaluation:
Evaluate the model's accuracy on both the training and testing sets.

Results:
---------
The project demonstrates effective fraud detection using Logistic Regression, achieving competitive accuracy scores on both training and testing data.

Dependencies:
---------------
The project requires the following Python libraries:

numpy
pandas
scikit-learn
Install the dependencies using:


pip install numpy pandas scikit-learn
Usage:
Run the project script to load the dataset, preprocess data, train the model, and evaluate its performance:


python credit_card_fraud_prediction.py


This project provides a robust approach to credit card fraud detection using machine learning, highlighting the importance of addressing class imbalance and careful model evaluation.




