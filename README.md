# Cryptocurrencies

## Overview

The purpose of this analysis is to use unsupervised machine learning on a Cryptocurrency dataset to uncover what cryptocurrencies are on the trading market and how they can be grouped to create a classification system.

## Steps

1. Data Preprocessing: This step included cleaning the data. Null values were removed, columns were dropped, and the data was transformed via get_dummies, and fit_transform.

2. Reducing Data Dimensions Using PCA: This step included reducing the data's principal dimensions to three pincipal components and a new dataframe was created. 

3. Clustering Cryptocurrencies Using K-means: This step included creating an elbow curve using hvPlot to find the best value for K and the K-means algorithm was used to make predictions of the K clusters.

4. Visualizing Cryptocurrencies Results: This step included creating a 3D-Scatter plot with the PCA data and the cluster, a table with tradable cryptocurrencies, and a hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply".