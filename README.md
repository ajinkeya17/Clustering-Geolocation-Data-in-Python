# Clustering-Goelocation-Data-in-Python
## AIM: Identifying locations to build taxi service stations in Johannesburg based on Geolocation data using clustering based ML algorithms.

1.) Given an extensive dataset of taxi cab stop hubs in the city of Johannesburg we had to identify ideal locations to construct taxi service stations throughout the city.

2.) The data was preprocessed using pandas and visualized using matplotlib and Folium for geographical visualizations.

3.) The models used for initial clustering was kmeans and based on silhouette score identified 98 possible clusters and locations to construct service stations.

4.) For better results we used Density based clustering algos DBSCAN and HDBSCAN and the outliers were clustered using K Nearest Neighbours algo.

5.) The results obtained were more logically sound and compelling as a more practical density based feature was used rather than arbitrary euclidian distance of points as in kmeans and identified 67 clusters and locations to build service stations throughout the city.

The jupyter notebook contains entire implementation of preprocessing data,visualizaing it, implementing clustering algos like kmeans,DBSCAN and HDBSCAN and dealing of outliers using KNN.

The project outcome html file contains the final geographical visualization of the city of Johannesburg and all data points with their clusters found from HDBSCAN and KNN which was the most efficient method.
