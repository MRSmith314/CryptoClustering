# CryptoClustering
Predicting if cryptocurrencies are affected by 24-hour or 7-day price changes using Python and Unsupervised learning models.

# Contents of Repository
Resource Folder
  - contains crypto market data csv file
Jupyter Notebook

# Process
Initialize and fit K-means modes with the original data scaled in order to plot clusters that will be compared to PCA (Principal Component Analysis) clusters. The elbow method was used to determine the optimal number of clusters. The variance is found and analyzed to determine the accuracy of models and whether the data is tightly clustered around the mean in the sphere of the cluster. By reducing the features in the PCA model we can determine whether this helps to reduce the noise and better fit the data to the mean.

# Conclusion
The PCA model demonstrated that the clusters were more accurate in the predictions with more defined clusters.
