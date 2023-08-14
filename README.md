            CryptoClustering - module 19

In this repository you will find how an unsupervised learning Machine Learning model was applied to cluster cryptocurrencies. The purpose of the analysis was to find the best way to cluster such currencies and to evaluate how inertia and the number of features affect the analysis.

Prepare the Data
Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Find the Best Value for k Using the Original Scaled DataFrame

Cluster Cryptocurrencies with K-means Using the Original Scaled Data

Optimize Clusters with Principal Component Analysis

Find the Best Value for k Using the PCA Data

Cluster Cryptocurrencies with K-means Using the PCA Data
