One of the features of Mac OS X that intrigued me is how my machine is able to detect my handwriting and allows me to copy-paste it in text format, inspired by this I was motivated to create my project which follows a similar process.

Results and findings:
1. For the SVM model using GridSearchCV: The best score across all searched parameters are 0.985894580549369
2. The best estimator across ALL searched params is given as SVC (C=1, cache_size=200, class_weight=None, coef0=0.0, decision_function_shape='ovr', degree=3, gamma=0.001, kernel='rbf', max_iter=-1, probability=False, random_state=None, shrinking=True, tol=0.001, verbose=False)
3. The best parameters across ALL searched params: {'C': 1, 'gamma': 0.001}
4. For SVM model, When evaluating the model on the test set, we get the Acurracy = 0.9888888888888889
5. For Logistic Regression model, after using cross-validation for 5 folds: When evaluating the model on the test set, we get the Acurracy = 0.9196666666666666
6. Hence, SVM performs better for this dataset as compared to Logistic Regression
