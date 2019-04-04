# classical-machine-learning

### Introduction

This repository contains some notebooks applying and analysing some classic machine learning algorithms suited for tabular data, like Random Forest, Gradient Boosted Trees, Support Vector Machines and Naive Bayes.

Each project is in a separated folder, containing the Jupyter Notebook used, the data and another useful functions. Each project is described in more details below. Wherever new projects are added, they will be described here.

### Projects

##### [finding-donors-ml](https://github.com/luiznonenmacher/classical-machine-learning/blob/master/finding_donors/finding_donors.ipynb)

This projects is based on the first project on the Udacity Machine Learning Engineer. In this project, I analyse data from 1994 US census trying to classify each person as having an income bigger or lower than $50,000. 

After cleaning and preprocessing the data, I tested 3 methods for classification: Support Vector Machines (SVM), Gradient Boosting Trees (GBT) and Naive Bayes Classifier (NB). More details about each method are in the notebook.

After applying each method, the best one was the GBT (in terms of the FBeta Scoring). The next step was to optimize the method in terms of hyperparameters. Lastly, we selected the 5 best features with the feature importance attribute of the GBT and trained another model with just this 5 features. 

#### [finding-donors-boosting](https://github.com/luiznonenmacher/classical-machine-learning/blob/master/finding_donors_boosting/finding_donors_boosting.ipynb)

In this project, I used the same dataset of the finding donors project to demonstrated and compare the three most famous gradient boosted trees implementations (UXGBoost, LightGBM and CatBoost). The main objective of this comparison is to ilustrate a presentation a gave on the 13° Edition of the Machine Learning [Meetup](https://www.meetup.com/pt-BR/Machine-Learning-Porto-Alegre/events/259764047/)in Porto Alegre. The repository also contains the pdf file used in the Meetup (in Portuguese). 
