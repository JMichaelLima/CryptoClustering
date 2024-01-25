# CryptoClustering

## Requirements

### Find the Best Value for k Using the Original Scaled DataFrame

Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11.

Visually identify the optimal value for k by plotting a line chart of all the inertia values computed with the different values of k.

Answer the following question: What’s the best value for k?

### Cluster Cryptocurrencies with K-Means Using the Original Scaled Data

Initialize the K-means model with four clusters by using the best value for k.

Fit the K-means model by using the original data.

Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values.

Create a copy of the original data, and then add a new column of the predicted clusters.

Using pandas’ plot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d".

### Optimize the Clusters with Principal Component Analysis

Create a PCA model instance, and set n_components=3.

Use the PCA model to reduce the features to three principal components, then review the first five rows of the DataFrame.

Get the explained variance to determine how much information can be attributed to each principal component.

Answer the following question: What’s the total explained variance of the three principal components?

Create a new DataFrame with the PCA data. Be sure to set the coin_id index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame.

### Find the Best Value for k by Using the PCA Data

Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11.

Visually identify the optimal value for k by plotting a line chart of all the inertia values computed with the different values of k.

Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data?

### Cluster the Cryptocurrencies with K-Means by Using the PCA Data

Initialize the K-means model with four clusters by using the best value for k.

Fit the K-means model by using the PCA data.

Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values.

Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters.

Using pandas’ plot, create a scatter plot by setting x="PC1" and y="PC2". 

### Determine the Weights of Each Feature on Each Principal Component

Create a DataFrame that shows the weights of each feature (column) for each principal component by using the columns from the original scaled DataFrame as the index.

Answer the following question: Which features have the strongest positive or negative influence on each component?