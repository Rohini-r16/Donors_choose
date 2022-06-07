# About Gradient Boosting Decision Trees(GBDT)

In decision trees we keep dividing on basis of their features starting with the ones which gives us the maximum information. We keep doing this until we have divided all the features, or our tree has become too long to avoid overfitting.
To overcome such problems, we have modified versions of decision trees such as random forest, XGBoost, Light GBM which use the concept of decision trees only and tries to give even better results. 

XGBoost is an implementation of Gradient Boosting Decision Trees in which decision trees are added in a sequential order to correct and minimize the error made by the previous model. This is done until there is no more room left for improvement. The reason to choose XGBoost in Decision trees is because its fast and performs great on huge dataset.
