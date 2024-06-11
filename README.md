# Liver-Disease-Classification-Iteration-2
This document outlines a comprehensive machine learning exploration for diagnosing liver disease based on patient data. 


 Data

The project utilizes the "Liver Patient Dataset (LPD)_train copy.csv" file containing patient information and a binary target variable indicating the presence or absence of liver disease.

Methodology

1. Data Preprocessing:
    * Load the data using pandas.
    * Explore the data to understand its structure and identify potential issues.
    * Perform feature engineering:
        * Encode categorical features (e.g., gender).
        * Impute missing values in numerical features (e.g., using mean imputation).
        * Select relevant features for model training.
2. Model Training and Evaluation:
    * Split the data into training and testing sets for model evaluation.
    * Standardize features using StandardScaler to ensure consistent scaling.
    * Train and evaluate the performance of various machine learning models:
        * Logistic Regression
        * Support Vector Machine
        * K-Nearest Neighbors
        * Random Forest
    * Employ metrics like accuracy, precision, recall, and F1-score to assess model performance.
    * Visualize confusion matrices to gain insights into true/false positives and negatives.
3. Feature Importance Analysis:
    * Analyze feature importance within the Random Forest model to identify the most impactful features for disease prediction.
    * Visualize feature importance using bar charts for better understanding.
4. Hyperparameter Tuning :
    * Explore tuning hyperparameters of the best performing model (e.g., Random Forest) to potentially improve its accuracy.

Results and Discussion

* The project will identify the best performing machine learning model for liver disease prediction based on the evaluation metrics.
* Feature importance analysis will reveal the most significant factors contributing to the model's predictions.
* The results can be further analyzed through:
    * Learning Curves: Examining the model's performance with varying training set sizes.
    * Model Persistence:*Saving the best model for future predictions on new data.

