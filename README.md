# Customer Churn Analysis

Dataset - Teleco-Customer-Churn.csv

### Background:
- Aim of this machine learning project is  to predict telecom users will churn or not depending on their subscription, monthly bill, tenure and basic demographic info
- This is a binary classification 
- Models i chose to evaluate - Decision Trees, Random Forest Classifier, Gradient Descent Boost, Ada Boost

### Steps Performed:
1. Importing packages
2. Importing data
3. Exploratory Data Analysis & Feature Engineering
4. Training base models
5. Evaluating base models
6. Oversampling 
- The dataset had an imbalance in class distribution, this bias in training dataset influences the ml algorithms, leading them to ignore the minority classes thus effecting model's performance. This imbalance is a problem as it is typically the minority class on which predictions are most important
-  One approcah to addressing this problem of class imbalance is to randomly duplicate examples from minority class, called oversampling
-  Random oversampling involves randomly duplicating examples from the minority class and adding them to the training dataset
7. Training models on oversampled data
8. Evaluating these models
9. Tuning of hyperparameter using gridsearch cross validation
- Gridsearch cross validation is a method used to determine the best hyperparameters for that model
10. Evaluating hypertuned models
11. Conclusion
- We can observe that our models score improved a lot after performing oversampling
- Hypertuned models performed only slightly better
- Top predictive features are Payment Methods, contract type, total & monthly charges and tenure
- Hypertuned Decision Tree, Random Forest, Gradient Boost performed better than Ada boost
