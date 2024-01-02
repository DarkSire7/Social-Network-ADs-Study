Ad Recommender
This repository contains code for an Ad Recommender system that utilizes a Decision Tree Classifier to predict whether an individual would purchase a certain product based on their age and estimated salary. The implementation is provided in a Jupyter Notebook and the model is saved using joblib. Additionally, the decision tree algorithm's graphical representation is available in a DOT file. The dataset used for training and testing the model is stored in a CSV file.

Files
ad-recommender code.ipynb: This Jupyter Notebook contains the predictor code implementing the Decision Tree Classifier for the ad recommender system.

ad-recommender.joblib: This file contains the serialized Decision Tree model saved using joblib. It can be loaded and used for making predictions without the need for retraining.

ad-recommender.dot: This file contains the graphical representation of the Decision Tree algorithm. It provides a visual overview of how the model makes decisions based on the input features.

social.csv: This CSV file contains the dataset with three columns: AGE, ESTIMATED SALARY, and PURCHASED. It is used for training and testing the Decision Tree model.
