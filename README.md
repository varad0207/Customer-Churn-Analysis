# Customer Churn Analysis
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
9. 
