# Cryptocurrencies
The goal of this analysis is to find clusters for the Cryptocurrencies dataset.
For clustering K-means unsupervised learning technique is used and Principal Component Analysis (PCA) algorithm is used for the dimentionality reduction.

StandardScaler and MinMaxScaler methods are used for scaling the data before clustering.
The dataset is reduced to three principal components using PCA.
Elbow Curve method is used to find the best k value for the k-means model.
Finally clustered the dataset into 4 classes using kmeans.

53.95 percentage of data clustered as class 1
44.92 percentage of data clustered as class 0
0.94 percentage of data clustered as class 2
0.19 percentage of data clustered as class 3


Summary
In this case, its clear that the most of the dataset falls into only two classes as class 1 which is 53.95%, and class 0 which is 44.92. Only 5 points fall into class 2 and 1 point falls into class 3.
