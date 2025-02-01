# boston-crime-clustering
This repository contains an implementation of Agglomerative Hierarchical Clustering on the Boston Crime Dataset. The project analyzes crime patterns by clustering similar incidents together and evaluates the clustering performance using the Silhouette Score.
This project applies Agglomerative Hierarchical Clustering to the Boston Crime Dataset to analyze crime patterns and similarities. The goal is to group crime incidents based on their features and visualize the clustering results.

How It Works
Each data point starts as its own cluster.
The distance between all pairs of clusters is calculated using metrics like Euclidean distance, Manhattan distance, or Ward’s method.
The two closest clusters are merged repeatedly until only one cluster remains or the desired number of clusters is reached.
The clustering results are visualized using a dendrogram, which shows how the clusters were formed at each step.
Project Details
Algorithm Used: Agglomerative Hierarchical Clustering
Dataset: Boston Crime Dataset
Evaluation Metric: Silhouette Score (0.808)
Visualization: Dendrogram for cluster representation
