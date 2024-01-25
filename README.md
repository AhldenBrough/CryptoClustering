# CryptoClustering

Given a dataset of different cryptocurriencies and price change information, this notebook first scales the data and then uses the K-means clustering algorithm to create clusters of cryptocurrencies. The optimal number of clusters (4) is determined by using the elbow method. Second, we use PCA to condense the number of features to 3, losing 11 percent accuracy but gaining a more clearly defined visualization of our same 4 clusters. Finally, the original and pca visualizations are compared using a composite plot.
