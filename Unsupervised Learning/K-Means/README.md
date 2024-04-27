# k-Means Clustering Analysis on Mall Customers Dataset

## Overview

This subdirectory contains resources and notebook implementations of the k-means clustering algorithm applied to the "Mall Customers" dataset. The objective is to segment customers based on their shopping behavior data.

## Algorithm Description

k-Means clustering is a popular unsupervised learning algorithm used for partitioning a dataset into K distinct, non-overlapping clusters. It involves the following steps:

1. **Initialization**: K initial "means" (centroids) are randomly generated within the data domain.
2. **Assignment**: Each data point is assigned to the closest centroid, and clusters are formed.
3. **Update**: Centroids of the clusters are recalculated based on the assigned points.
4. **Iteration**: Steps 2 and 3 are repeated until the centroids no longer move significantly or a maximum number of iterations is reached.

The algorithm aims to minimize the within-cluster variance, also known as the inertia or the sum of squared distances between data points and their corresponding cluster centroid.

## Theoretical Foundation

k-Means works on the principle of distance metrics (usually Euclidean distance). The theory posits that by minimizing the inertia, one can achieve clusters where the intra-cluster similarity is high, and the inter-cluster similarity is low.

## Applications

- **Market Segmentation**: Segmenting customers based on purchasing habits, income, etc.
- **Document Clustering**: Grouping similar documents in terms of topics and themes.
- **Image Segmentation**: Classifying pixels in an image into different categories.
- **Anomaly Detection**: Identifying unusual data points by their distance from cluster centroids.
