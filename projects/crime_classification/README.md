# San Fransisco Crime Classification Problem
## Capstone Project

## Problem Statement:
From 1934 to 1963, San Francisco was infamous for housing some of the
world's most notorious criminals on the inescapable island of Alcatraz.
Today, the city is known more for its tech scene than its criminal past. But,
with rising wealth inequality, housing shortages, and a proliferation of
expensive digital toys riding BART to work, there is no scarcity of crime in
the city by the bay.

From Sunset to SOMA, and Marina to Excelsior, this competition's dataset
provides nearly 12 years of crime reports from across all of San Francisco's
neighborhoods. This is a multi-class classification problem, given time and
location, the goal is to predict the category of crime that occurred.

## software and libraries used:
* [ipython notebook](https://ipython.org/ipython-doc/3/notebook/)
* [pandas](https://pandas.pydata.org/pandas-docs/stable/) 
* [matplot](https://matplotlib.org/contents.html)
* [numpy](https://docs.scipy.org/doc/)
* [basemap](https://matplotlib.org/basemap/api/basemap_api.html#module-mpl_toolkits.basemap)

## Data:
https://www.kaggle.com/c/sf-crime/data

## Metrics:
[LogLoss](http://wiki.fast.ai/index.php/Log_Loss) and [Fscore](https://en.wikipedia.org/wiki/F1_score)

## Algorithms and Techniques:
There are 4 algorithms used and compared against the random predictor
* Naive random predictor
* [DecisionTreeClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
* [MLPClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
* [XGBClassifier](http://xgboost.readthedocs.io/en/latest/python/python_api.html)
* [SVClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)

## Results:
* The chosen algorithm is XGBoostClassifier as it is the most suitable one.

Final score on kaggle = 2.85673

