# Dnomads
Developed in the Machine Learning course by: Fernanda Avendaño, Diego Quezada and Kevin Reyes.
## Objectives
- Predict the cost of travel packages using linear models (exclusive).
- Identify and correct non-compliance with theoretical requirements of linear models.
- Apply feature engineering using internal and external information to the data set, in addition to applying natural language processing methods.

## Description
Linear model to predict the cost of travel packages for digital nomads.

## Conclusions
- When working with simple models, the importance of feature engineering is experienced to obtain good results, since the difference in performance between different linear models is negligible, therefore, the great improvements in performance are totally correlated with the attributes that are included in the model.
- The fact of eliminating variables to avoid multicollinearity between the independent variables does not always lead to an improvement in the performance of the linear regression.
- As the number of attributes increases, the impact of the regularizer on the performance of the models is more significant.
- When carrying out a process of creating new features, it must always be taken into account that multicollinearity could be introduced into the model, for example, when we apply one-hot-encoding, we directly introduce a multicollinearity into the model, which can be resolved by eliminating a of the one-hot-encoding variables.

## Technology stack
- Spacy.
- Scipy.
- Pandas.
- Numpy.
- Matplotlib.
- Seaborn.
- Scikit-learn.