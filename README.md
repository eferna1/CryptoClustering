# Crypto Clustering

## Overview
### Using Python and unsupervised learning, in this assignment we wil perdict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

## Steps
### 
1. Load and prepare the data. 
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.

## Results
### The project includes the following visualizations: 
1. Elbow curve on the original data.
![image](https://github.com/eferna1/CryptoClustering/assets/145945547/0781f5c6-df0d-4ac4-afab-4c6d4f58739d)

2. Elbow curve using PCA data.
![image](https://github.com/eferna1/CryptoClustering/assets/145945547/92834c62-f858-49f3-bb6c-b434adec0822)

3. Scatter plot of cryptocurrency clusters based on original data.
![image](https://github.com/eferna1/CryptoClustering/assets/145945547/2201a3cd-6084-46c6-9363-82662193928f)

4. Scatter plot of cryptocurrency clusters based on the PCA data.
![image](https://github.com/eferna1/CryptoClustering/assets/145945547/876addb0-96f4-4967-af03-297667b57d3d)

## Conclusion
### 
After visually analyzing the cluster, reducing the number to cluster the data had a significant impact.   In the initial plot, the elbow curve indicated that the optimal value for K was 4, resluting in 4 clusters.  However, there were two clusters that only contained one data point each and the other two clusters were not clearly separated.  By implementing the PCA prediction and using the optimal value for K of 2 the resulting plot was more accurate.  
   
