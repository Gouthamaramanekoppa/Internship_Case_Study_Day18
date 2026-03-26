# Internship_Case_Study_Day18


Hyperparameter tuning was performed to improve the performance of the machine learning models. Hyperparameter tuning involves adjusting model parameters to find the best configuration that produces the highest predictive performance.
For this project, the Random Forest and XGBoost models were optimized using grid search techniques.

Objectives
The main objectives of this phase were:
- Improve model accuracy and fraud detection capability
- Tune important hyperparameters of machine learning models
- Identify the best parameter combination
- Optimize model performance for real-world deployment

Hyperparameter Tuning Method
The tuning process was performed using **GridSearchCV**, which systematically searches through different parameter combinations and evaluates model performance using cross-validation.
This approach ensures that the selected model parameters provide the best possible performance.


Parameters Tuned
Random Forest
The following parameters were optimized:
- Number of trees (`n_estimators`)
- Maximum depth (`max_depth`)
- Minimum samples split (`min_samples_split`)

XGBoost
The following parameters were optimized:
- Learning rate (`learning_rate`)
- Maximum depth (`max_depth`)
- Number of estimators (`n_estimators`)

Benefits of Hyperparameter Tuning
Hyperparameter tuning helps:
- Improve prediction accuracy
- Reduce overfitting
- Increase model reliability
- Improve fraud detection capability
