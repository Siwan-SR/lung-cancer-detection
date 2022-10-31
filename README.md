# Lung Cancer Detection

A machine learning model that can detect whether a patient has lung cancer or not.

## Data

The data is from: https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer

#### About the data

Total no. of attributes: 16
No. of instances: 284

Attribute information:

* Gender: M(male), F(female)
* Age: Age of the patient
* Smoking: YES = 2, NO = 1.
* Yellow fingers: YES = 2, NO = 1.
* Anxiety: YES = 2, NO = 1.
* Peer_pressure: YES = 2, NO = 1.
* Chronic Disease: YES = 2, NO = 1.
* Fatigue: YES = 2, NO = 1.
* Allergy: YES = 2, NO = 1.
* Wheezing: YES = 2, NO = 1.
* Alcohol: YES = 2, NO = 1.
* Coughing: YES = 2, NO = 1.
* Shortness of Breath: YES = 2, NO = 1.
* Swallowing Difficulty: YES = 2, NO = 1.
* Chest pain: YES = 2, NO = 1.
* Lung Cancer: YES, NO.


## How the model was made

The model was made using [Scikit-Learn](https://scikit-learn.org) an excellent machine learning library. I used Random Forest Classifer as the model.

## How the notebook is structured

* Explore the data
* Visualize our data
* Fit and instantiate the model
* Describe our model

## What you will find

* Awesome Graphs that visualize the data
* Use of [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/)
* Use of Scikit-Learn's manu features
* Testing with two models
* A ROC Curve
* Visual Confusion Matrix
* A custom Classification Report
