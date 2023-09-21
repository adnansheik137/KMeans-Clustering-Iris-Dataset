# KMeans-Clustering-Iris-Dataset
Welcome to the K-Means Clustering assignment on the Iris dataset! In this project, we utilize the K-Means clustering algorithm to analyze and cluster the Iris flower dataset introduced by Ronald Fisher in 1936.

## About the Iris Dataset

The Iris flower dataset, also known as Fisher's Iris data set, comprises measurements of three Iris species: Iris Setosa, Iris Versicolour, and Iris Virginica. These measurements include sepal length and width, as well as petal length and width, all recorded in centimeters. Ronald Fisher used this dataset to develop a linear discriminant model for species classification based on these four features.

## Assignment Overview

In this assignment, we aim to implement K-Means clustering on the Iris dataset. K-Means is an unsupervised machine learning algorithm that groups data points into clusters based on their similarity. Here's a brief overview of how we're approaching the task:

### Implementation Steps:

1. **Choose the Number of Clusters (k)**: We'll decide on the number of clusters (k) that we want to identify within the Iris dataset. This is a critical step, as it determines the granularity of our clustering.

2. **Select Initial Centroids**: We'll randomly select k data points from the Iris dataset as the initial cluster centroids.

3. **Assign Data Points to Clusters**: We'll assign each data point in the dataset to the cluster with the nearest centroid. This step partitions the data into k clusters.

4. **Update Centroids**: We'll recompute the centroids of the newly formed clusters based on the mean of the data points in each cluster.

5. **Repeat Steps 3 and 4**: We'll iterate steps 3 and 4 until convergence, where the centroids no longer change significantly or a predefined number of iterations is reached.

## Getting Started

To dive into the details of our K-Means clustering implementation on the Iris dataset, please refer to the Jupyter Notebook included in this repository. It provides code, explanations, and visualizations of the clustering process.
