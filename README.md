Models used for the Kaggle competition: https://www.kaggle.com/c/porto-seguro-safe-driver-prediction

Main approach was use and ensemble of different models (XGBoost, LightGBM, Logistic Regression, etc.). Feature engineering was hard as the meaning of the features was not given. Still I tried to discover some useful feature interactions.

- EDA.ipynb: Exploratory Data Analysis of the project
- Stacking - Approach 1.ipynb: Stacking predictions of different models.
- Stacking - Approach 2 (Allow different feature sets) - Stratified Version.ipynb: Stacking predictions of different models. Difference with respect approach 1 is that the predictions for the test set are generated during the Cross validation (and using a Stratified K-fold)
- Mean Ranking of several predictions and Stacking.ipynb: Generate predictions by doing the mean ranking of the predictions done by different models.
- Discovering feature interactions (numericals).ipynb: Code used to observe which features interactions could potentially improve the prediction accuracy.
