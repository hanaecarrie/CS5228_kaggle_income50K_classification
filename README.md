# General

In this work, we address the task of predicting if an individual is earning 50K or more a year. It is a binary classification problem.
This work is a part of an in-class [Kaggle Competition for Knowledge Discovery and Data Mining](https://www.kaggle.com/c/cs5228) Course offered at NUS, Singapore in Semester 2 of AY 2019-2020.

Our final binary F1-score is 86,946\% on the private leaderboard and we were ranked 10th / 55.

# Set up

To clone this github repository, use the following command:
```$ https://github.com/hanaecarrie/CS5228_kaggle_income50K_classification.git```

Make sure you have Python 3.6 or above installed, as well as the following packages:
- numpy
- csv
- os
- pandas
- matplotlib
- seaborn
- sklearn
- pickle
- scipy
- lightgbm
- catboost
- xgboost
- IPython
- subprocess
- keras
- collections
- math
- time
- glob
- re

# Data description, exploration and visualisation

The Kaggle dataset consists of a separate training and test dataset, both consisting of 24,421 records each. 
The training dataset suffers from class imbalance, with 75.15\% of the samples being from the negative class (≤ \$50K, label=0) and the remaining 24.85\% being positive samples (> \$50K, label=1).
The dataset consists of 13 attributes described below:

![Alt text](figures/figure1.png?raw=true "Title")

Here are some plots from the report to summarise the dataset features and look at their relationships.

![Alt text](figures/figure2.png?raw=true "Title")

![Alt text](figures/figure3-4.png?raw=true "Title")


# Results and report

The full report is available [here](https://github.com/hanaecarrie/CS5228_kaggle_income50K_classification/Report.pdf)

![Alt text](figures/table3.png?raw=true "Title")

The description of the different preprocessed data: 

![Alt text](figures/table2.png?raw=true "Title")