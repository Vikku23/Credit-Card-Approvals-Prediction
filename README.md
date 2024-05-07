# Credit Card Approvals Prediction

Predicting Credit Card Approvals using Machine Learning
Credit cards are one of the most commonly used financial tools. However, obtaining a credit card can be a difficult task for many individuals due to various factors such as income level, and employment status. To help streamline the application process and improve the approval rate, machine learning models can be used to predict credit card approval.
In this project, we will explore how various factors affect credit card approval rates and use predictive models to improve the accuracy of credit card approval predictions.

Key Components:

Data Exploration: The dataset is thoroughly examined to understand its structure, variables, and potential correlations between features affecting credit card approval.
Model Development: Several machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, XGBoost, and Random Forest are implemented to predict credit card approvals.
Model Performance Evaluation: The performance of each model is assessed using accuracy metrics, comparing their effectiveness in predicting credit card approvals.
Hyperparameter Tuning: GridSearchCV is employed to fine-tune the Random Forest model, optimizing its parameters to achieve even higher accuracy.


## Model Performance Comparison

| Model            | Accuracy |
|------------------|----------|
| Logistic Regression | 89%      |
| KNN              | 88%      |
| SVM              | 90%      |
| Decision Tree    | 89%      |
| XGBoost          | 90%      |
| Random Forest    | 93%      |
| Random Forest (Hyperparameter Tuning) | 92% |


Conclusion:
The Machine Learning Model is able to predict Credit Card Approvals with an enhanced accuracy of 93%.
The Random Forest model achieves an accuracy of 93%, demonstrating its ability to capture dataset patterns and make accurate predictions for the majority of cases. The hyperparameter tuning performed using GridSearchCV further enhances the model's accuracy to 92.90%. This suggests that the model could be suitable for your specific use case.
