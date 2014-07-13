scikit-learn_BayesianOptCV
==========================

A cross validation hyper-parameter optimization module.

This module uses Bayesian optimization and Gaussian Processes 
to find optmum set of cross validation parameters. It uses the
cross_val_score and Gaussian Processes objects from sklearn.

Ultimately the goal is to add this technique to sklearn's
cross validation / model selection module.
