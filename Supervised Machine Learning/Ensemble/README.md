# Other Ensemble Methods

While Random Forests are an example of an ensemble method, there are many other ensemble methods used in machine learning. Boosting is another powerful type of ensemble method that builds models sequentially. Each new model is trained to correct the errors made by the previous ones. This process focuses on the "hard-to-predict" cases, often leading to models with very high accuracy.

AdaBoost (Adaptive Boosting) was the first successful boosting algorithm. It works by adjusting the weights of the data points at each iteration. Misclassified points are given higher weights, forcing the next model in the sequence to focus more on them.

# Data

The dataset used here tracks all basic box score and biographical stats of every NBA player from 1996 to 2022 such as height, weight, points per game, net rating, season, and many more. Link: https://www.kaggle.com/datasets/justinas/nba-players-data

# Libraries
The following python libraries are used.

matplotlib (https://matplotlib.org/)  
numpy (https://numpy.org/)  
pandas (https://pandas.pydata.org/)  
seaborn (https://seaborn.pydata.org/)  
scikit learn (https://scikit-learn.org/)  
