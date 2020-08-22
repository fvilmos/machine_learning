# Housing Prices Competition - Machine Learning

## About

Top 3% solution for [Kaggle Housing Prices Competition](https://www.kaggle.com/search?q=Housing+Prices+Competition+for+Kaggle+Learn+Users+in%3Acompetitions) (position 763 from 32354 teams...today).

### The story

We get a sample database having 79 variables per entry which describe all the aspects of a house (like the number of rooms, bathrooms, etc.), the ```challenge``` is to predict as accurately as possible the price on what was sold. 

### The approach on short

- Load the usual Machine Learning packages (sklearn, pandas, matplotlib);
- Analyze data with seaborn;
- transform labels to numerics;
- do some feature engineering to enhance accuracy;
- clean the database, drop empty values, delete insignificant values;
- train a [GradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html) with the enhanced training data;
- test data, submit it to Kaggle for ranking.

### How to run

Download the database from [kaggle](https://www.kaggle.com/c/home-data-for-ml-course/data), copy in a local ```./data``` directory. Use jupyther notebook or jupyther Lab, load the ```.ipynb``` file and run it.

If successful the ```./submission.cvs``` file will be generated, and you will have as console output something like this:
```
-------------------
first approach
MSE: 330557474.3138
mae: 12,711
score: 0.9999999999979714
min: 58401 max: 476649
-------------------

...
-------------------
second approach
MSE: 345248876.8241
mae: 12,797
score: 0.9989518939409097
min: 65777 max: 495037
-------------------
```

/Enjoy
