Assignment Module 17
Statement of business: The business objective of this practice is to evaluate the success of a campaign aimed at acquiring new bank account subscribers. This will be achieved by implementing a Data Mining (DM) project based on the CRISP-DM methodology. The project involves developing various models to assess the campaign's success and identify the most effective model. The performance of different classifiers, including k-nearest neighbors, logistic regression, decision trees, and support vector machines, will be directly compared to determining the best approach for this campaign.
Model Building and Evaluation:
o	Established a baseline model using DummyClassifier with the 'most_frequent' strategy to provide a simple performance benchmark.
o	Split the data into training and testing sets (X_train, X_test, y_train, y_test).
o	Built and evaluated a Logistic Regression model on the one-hot encoded data, calculating its accuracy.
o	Built and evaluated several other classification models using their default settings:
	K-Nearest Neighbors (KNN)
	Decision Tree
	Support Vector Machine (SVM) (using a pipeline with StandardScaler)
o	Measured the training time and calculated training and testing accuracy for each of these models.
o	Visualized and compared the performance of the models using ROC curves and calculated the Area Under the Curve (AUC) for each.
o	Implemented a cumulative lift curve comparison to visualize how well each model targets the positive class.
2.	Model Improvement (Tuning):
o	Introduced hyperparameter tuning using GridSearchCV and RandomizedSearchCV to improve the performance of Logistic Regression, KNN, Decision Tree, and SVM models.
o	Defined parameter grids/distributions for each model.
o	Fitted the tuning methods on the training data to find the best hyperparameters based on AUC.
o	Evaluated the performance of the tuned models on the test set using AUC.
