Objective: To prepare a comprehensive data analysis report and build predictive models that identify high-potential customers for future banking transactions.

Dataset Details: * 200 anonymized numerical features (var_0 to var_199) representing customer behavioral data.

Imbalanced target variable where 1 indicates a transaction and 0 indicates no transaction.

Modeling Workflow:

Preprocessing: Scaled high-dimensional data and addressed class imbalance using scale_pos_weight.

Algorithms: Implemented multiple classifiers including Logistic Regression, Decision Trees, and XGBoost.

Optimization: Performed Hyperparameter Tuning on the XGBoost model using GridSearchCV to maximize robustness.
