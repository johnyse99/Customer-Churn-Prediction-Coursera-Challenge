# Customer-Churn-Prediction-Coursera-Challenge
This project provides a professional solution to the Churn Prediction competition, strictly adhering to the technical constraints and requirements of the automated laboratory environment.

# 🚀 Subscription Churn Prediction Coursera Challenge

## 📋 Challenge Requirements
As defined in the technical documentation:
- **Output**: A specific DataFrame named `prediction_df`.
- **Dimensions**: Exactly 104,480 rows and 2 columns: `CustomerID` and `predicted_probability`.
- **Naming**: Strict adherence to variable and column naming conventions is required for the autograding process.

## 🛠️ Implementation Strategy
- **Baseline Replacement**: The original `DummyClassifier` was replaced with a `RandomForestClassifier` to provide accurate churn likelihoods while maintaining compatibility with the laboratory's structure.
- **Data Integrity**: Implemented a standardized preprocessing pipeline to ensure the test and training sets remain consistent for the scoring engine.
- **Validation**: Includes the original laboratory's assertion suite to ensure the output format matches the evaluation script's expectations exactly.

## ❓ FAQ (Interview Questions)
- **Why is it important to follow specific naming conventions in these labs?**
Automated grading scripts (autograders) search for specific memory objects and file headers. Even a minor typo in a column name will result in a failed submission.
- **What is the goal of using `predict_proba`?**
It provides the probability of a subscription belonging to the churn class, which is necessary for calculating the AUC (Area Under the Curve) metric, the standard for this competition.

📄 License 
This project is distributed under the MIT license. Its purpose is strictly educational and research-based, developed as an Applied Data Science solution.

Note for recruiters: This project demonstrates the ability to follow strict technical specifications and deliver results within a pre-defined framework, ensuring 100% compliance with external requirements.

Author: JUAN S. 
Contact: https://github.com/johnyse99
