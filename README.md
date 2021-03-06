# Introduction

Purpose of this repository is to provide very simple introductory tutorials for energy analytics novices. Each tutorial has the same process. Main objective of this exercise is to provide a quick introduction to basic machine learning models in Python. Students can pick up from where the tutorial ends and improve model performance by simply changing the hyperparameters.

+ Data is preprocessed and cleaned (see [preprocessing](https://github.com/berkorbay/wind-tutorial/blob/main/preprocessing_cnr.ipynb) notebook)
+ Only scikit-learn models are used.
+ Focused on regression models. Data is actually for forecasting, but we currently do not apply time series models.
+ State-of-the-Art (SotA) approaches are avoided. This is not an ML-Ops repository. Each notebook is an almost-copy of the other, except the model object. See vchapparo's repository in the resources for a sophisticated example.
+ Hyperparameter tuning is not covered.
+ Convenient reproducibility is at the center. You only need the input data file and the Jupyter Notebook.
+ Performance is not important and only basic metrics are used in evaluation. But discussion about interpretation in terms of bias, absolute deviation and relative deviation is good practice. *sklearn.metrics* is used to show more of sciki-learn.

Briefly, this repository covers fundamentals, provides hands on applications (good if you are bored of iris dataset), 

# Available Notebooks

## Linear Models
+ [Elastic Net](https://github.com/berkorbay/wind-tutorial/blob/main/sklearn_ElasticNet.ipynb)
+ [Linear Regression](https://github.com/berkorbay/wind-tutorial/blob/main/sklearn_linearRegression.ipynb)

## Tree Models
+ [Decision Tree](https://github.com/berkorbay/wind-tutorial/blob/main/sklearn_DecisionTree.ipynb)
+ [Gradient Boosting](https://github.com/berkorbay/wind-tutorial/blob/main/sklearn_GradientBoostingRegressor.ipynb)
+ [Random Forests](https://github.com/berkorbay/wind-tutorial/blob/main/sklearn_randomForest.ipynb)

# Resources

+ [scikit-learn](https://scikit-learn.org)
+ [ENS - CNR Challenge](https://challengedata.ens.fr/challenges/34) **(data set)**
+ [vchapparo's repository](https://github.com/vchaparro/wind-power-forecasting)

# Usage & License

You can use this repository under the permissive [MIT License](https://github.com/berkorbay/wind-tutorial/blob/main/LICENSE) as long as you respect data license (see [here](https://challengedata.ens.fr/terms_of_use) and [here](https://www.etalab.gouv.fr/licence-ouverte-open-licence)) and scikit-learn license (see [here](https://github.com/scikit-learn/scikit-learn/blob/main/COPYING)).

# Contact

1. Simply add an [issue](https://github.com/berkorbay/wind-tutorial/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc)
2. [Add me](https://www.linkedin.com/in/berkorbay/) on Linkedin.

# Next

+ Add more models.
+ Add explanations, more notes and guidelines to tutorials. Try to give the intuition of models with as few words as possible.
