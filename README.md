# Context
---------------
In this study, we analyze a loan applicant database, where each applicant is labeled as 0 if they have repaid their loan on time and 1 if they have experienced repayment difficulties. We then define a data-driven credit score using three machine learning classifiers: Logistic Regression, Random Forest, and XGBoost. The objective of this score is to assist client relationship managers in evaluating whether an applicant's situation requires more attention by assigning a score between 0 and 1. To enhance interpretability, we also identify and represent the features that most significantly impact the model's prediction process.

# Tech used
---------------------
* Binary classification tasks : RandomForestClassifier, LogisticRegression,  XGBoost
* Hyperparameter tuning : RandomizedSearchCV, GridsearchCV
* Visualisation : Seaborn
* Interpretability : SHAP

