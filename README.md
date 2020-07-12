# Cryptocurrencies

In this Challenge we were asked by Accountability Accounting to analyze and group together cryptocurrencies and how they can be developed into a new investment product.

#### Objectives
* Process the dataset for dimension reduction with PCA and clustering using K-means.
* Predict clusters with the cryptocurrencies data using the K-means algorithm from sklearn.
* Present the results using plots and data tables.

##### Resources
* Python, sklearn, hvplot
* crypto_data.csv

#### Summary
In this Challenge we had to process the dataset in the csv file that was provided before we could reduce, cluster and visualize it. To do this we had to first filter through and remove certain values that might affect our clustering model. This included cryptocurrencies that were not being traded, did not have a defined algorithm, had null values, and did not have coins mined. Then we created dummies variables for all the features that were text in the dataframe. Finally we used the StandardScaler from sklearn to standardize all the data so that we could further reduce the dataframe. 

After all the processing was completed, we used the PCA algorithm from sklearn to reduce the dimensions of the dataframe into three principal components. Bascially, the PCA algorithm takes a large dataset and breaks it down smaller components. This speeds up the machine learning process for when we want to determine how to best visualize and present the data to Accountability Accounting. To determine how many clusters we should produce, we used the K-Means from sklearn and came to the conclusion that four clusters would be best for our dataset. 

To visualize the data, two plots and a table were created. The first plot is a 3D-Scatter plot to show the clusters produced by the K-Means algorithm. The second plot is a 2D-Scatter plot. It is good to compare and contrast the 3D and 2D plots. It is difficult to see the separate clusters in the 2D plot. Finally we produced table that had all the data from the processed dataset so that those in Accountability Accounting who wanted to look through dataset could do so.
