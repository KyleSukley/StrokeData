This project makes use of a dataset from Kaggle, with the goal of predicting binary stroke outcomee. After exploring and visualizing the data, I create sklearn pipelines that transform the features and prepare them for model selection. 

I test three models:
1. Logistic Regression
2. Support Vector Classifier
3. RandomForestClassifier
4. K-Nearest Neighbor Classifier

Each model's hyperparameters are tuned using a parameter grid and HalvingGridSearchCV.

After assessing the quality of each model, I make use of SMOTE, and redo the prior steps. 
