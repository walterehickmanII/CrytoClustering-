
# CryptoClustering ReadMe
## Overview
In this challenge, we apply the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies based on their price fluctuations over various timeframes. Specifically, we analyze price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

## Before You Begin
Create Repository: Create a new repository named CryptoClustering for this project.
Clone Repository: Clone the newly created repository to your local machine.
Push Changes: Push your changes to GitHub.
##Files
Download the following files to get started:

Module 11 Challenge files (Links to an external site.)
## Instructions
Rename File: Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.
Load Data: Load the crypto_market_data.csv into a DataFrame and set the index to the "coin_id" column.
Summary Statistics: Obtain summary statistics to understand the data.
Prepare Data: Normalize the data using StandardScaler() from scikit-learn.
Find Best Value for k: Utilize the elbow method to determine the best value for k.
Cluster Cryptocurrencies with K-Means: Cluster cryptocurrencies using the original scaled data.
Optimize Clusters with PCA: Perform PCA to reduce features and optimize clusters.
Find Best Value for k Using PCA: Determine the best value for k using PCA data.
Cluster Cryptocurrencies with K-Means Using PCA: Cluster cryptocurrencies using PCA data.
Determine Weights of Each Feature on Each Principal Component: Identify feature weights on principal components.
# Summary
Total Explained Variance: Calculate the total explained variance of the three principal components.
Best Value for k: Determine the best value for k using both original data and PCA data.
Impact of Using Fewer Features: Discuss the impact of using fewer features to cluster the data using K-Means.
Feature Influence: Identify features with the strongest positive or negative influence on each principal component.
Conclusion
This project demonstrates the application of K-means clustering and PCA in classifying cryptocurrencies based on price fluctuations. By analyzing various timeframes and optimizing clustering techniques, we gain insights into the underlying patterns and relationships within the cryptocurrency market data.

# Support
For any inquiries or assistance, please contact Walter E Hickman Jr at walter.hickman@gmail.com
