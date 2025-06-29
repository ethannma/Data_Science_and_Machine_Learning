# K Means Clustering and Principal Component Analysis

This project explores two fundamental unsupervised learning techniques: Principal Component Analysis (PCA) for dimensionality reduction and K Means for clustering. Unsupervised learning is used when we do not have pre-labeled data; instead, the goal is to find interesting patterns or structures within the data itself.

K-Means is an unsupervised clustering algorithm that partitions data into K distinct groups (clusters). It works by choosing K initial cluster centers (centroids), assigning each data point to the nearest centroid, recalculating centroids based on current assignments and then repeating until assignments stop changing, or a maximum number of iterations is reached.

PCA is a dimensionality reduction technique, not a clustering method. It transforms data into a new coordinate system where the first principal component captures the most variance, while the second captures the next most (orthogonal to the first), and so on.

# Data

The dataset used here contains Spotify file information. Link: https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db

# Libraries
The following python libraries are used.

matplotlib (https://matplotlib.org/)  
numpy (https://numpy.org/)  
pandas (https://pandas.pydata.org/)  
seaborn (https://seaborn.pydata.org/)  
scikit learn (https://scikit-learn.org/)  
