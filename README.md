# classical-machine-learning

### Introduction

This repository contains some notebooks applying and analysing some classic machine learning algorithms suited for tabular data, like Random Forest, Gradient Boosted Trees, Support Vector Machines and Naive Bayes.

In the main structure of the repository are the Jupyter Notebook containing the analysis. The data folder contain all the data used in the projects and the utils folder contains some auxiliary code used on the projects.

Below each project is described in more details. Wherever new projects are added, they will be described here.

### Projects

#### [finding-donors-ml](https://github.com/luiznonenmacher/classical-machine-learning/blob/master/finding_donors.ipynb)

This projects is based on the first project on the Udacity Machine Learning Engineer. In this project, I analyse data from 1994 US census trying to classify each person as having an income bigger or lower than $50,000. 

After cleaning and preprocessing the data, I tested 3 methods for classification: Support Vector Machines (SVM), Gradient Boosting Trees (GBT) and Naive Bayes Classifier (NB). More details about each method are in the notebook.

After applying each method, the best one was the GBT (in terms of the FBeta Scoring). The next step was to optimize the method in terms of hyperparameters. Lastly, we selected the 5 best features with the feature importance attribute of the GBT and trained another model with just this 5 features. 



