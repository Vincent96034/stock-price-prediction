# stock-price-prediction
**Classification task to forecast stock movements. 70% of the grade of the module "Financial Data Analytics".**

Task description:

1. Estimate an appropriate benchmark model using either the linear, logistic or softmax regression model for each of the target variables. You can decide which time periods to use for training and testing. The results generated with these models serve as benchmark results and you should compare them to results which are developed by yourself during the project.

2. Estimate and develop models for each of the target variables using either the DecisionTreeRegressor or DecisionTreeClassifier from sklearn. Hereby, make use of the GridSearchCV schedule to find good hyperparameters. Again, the time period can be chosen by yourself as well as the choices for hyperparameters and number of splits for the grid search.

3. Estimate and develop models for each of the target variables using either the GradientBoostingRegressor or GradientBoostingClassifier from sklearn. Or any other Gradientbossting from other packages. Hereby, make use of the GridSearchCV schedule to find good hyperparameters. Again, the time period can be chosen by yourself as well as the choices for hyperparameters and number of splits for the grid search.

4. Find out which technical indicators are most important for your tree and boosting based models. Choose a subset of important technical indicators and re-estimate the models only with these indicators, what is the impact on previous results?

5. Estimate company specific models using only the data from that company. For at least 2 companies. Compare your results with the ones of the model which uses all data regarding the metrics/scores. What do you observe? Additionaly compare feature importances between these models, inspect singular features for these companies (compare them, look at correlations to the respective target variable (graphically as well as numerical)). Discuss your observations.

6. Write a final summary with no more than 500 words what you think are the most important aspects of your model development and the corresponding results.
