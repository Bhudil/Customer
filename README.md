# Customer Segmentation

The following model takes in a dataset of customer's income and spent in a particular enterprise(taken from kaggle). The data is visualized to check the spread of the customers. Then with the help of Kmeans and PCA algorithm we fit the data and create visualizations(using matplotlib.puplot) with discrete seperation of customers into various bins/clusters.

STEPS-

1) Import the dataset and visualize it using matplot to determine the spread of the data(scatterplot)

2) Use the elobow method to determine the number of clusters to be used in the Kmeans model(use PCA)

3) Determine he silhouette coefficient to measure how similar the data is with in the cluster compared to other clusters(for KMeans)

4) Fit KMeans to the data and visualize the clusters(scatterplot)

5) Use Dendrograms to identify the optimal number of clusters

6) Fit them into the dataset and visualize the clusters again

7) The final scatterplot is the ideal visualizations that segments the customers accurately
