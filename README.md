# Titanic-Survival-Prediction
  This project predicts the survival of passengers on the Titanic dataset using logistic regression.   We focus on the following features: **Age, Sex, Pclass, and Fare**.   The goal is to analyze patterns of survival and evaluate the predictive power of these features.
🛳️ Titanic Survival Prediction
📌 Project Overview

This project analyzes the Titanic dataset to predict passenger survival using Logistic Regression.
I focused on the following variables:

*Age

*Sex

*Passenger Class (Pclass)

*Fare

The goal is to explore survival patterns and build a machine learning model that predicts whether a passenger survived or not.

🔎Steps Performed

Data Loading & Cleaning

Selected relevant columns

Handled missing values (Age filled with median)

Encoded categorical variable (Sex)

Exploratory Data Analysis (EDA)

Count plots for Survived, Pclass, and Sex

Boxplot of Age by Pclass

Survival distributions visualized

Modeling

Train-test split (80-20)

Logistic Regression applied

Model evaluation using Accuracy, Confusion Matrix, and Classification Report

Feature Importance

Coefficients analyzed to see which features most affect survival.

📊 Key Findings

Sex was the strongest predictor (females had much higher survival chances).

Pclass showed that 1st-class passengers survived more often than 3rd-class.

Age had a small negative effect (younger passengers survived more).

The model achieved a reasonable accuracy with interpretable results.
⚙️ Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

✅ Conclusion

This project demonstrates how basic data preprocessing, visualization, and a logistic regression model can be used to understand survival patterns on the Titanic.
