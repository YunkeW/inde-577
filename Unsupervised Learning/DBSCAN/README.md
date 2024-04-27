# DBSCAN Clustering

## Introduction

This subdirectory is dedicated to the implementation and analysis of the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) clustering algorithm. DBSCAN is a robust, unsupervised machine learning algorithm that is used to identify clusters of varying shapes and sizes and to detect outliers in a dataset.

## Algorithm Description

DBSCAN groups together points that are closely packed together (points with many nearby neighbors) and marks as outliers the points that lie alone in low-density regions. This is achieved by two main parameters:

- `eps`: The maximum distance between two points for them to be considered as in the same neighborhood.
- `min_samples`: The minimum number of points required to form a dense region.

The algorithm starts by arbitrarily picking up a point in the dataset. If this point has a sufficient number of points (`min_samples`) within `eps` distance, a cluster is started. The cluster then grows by recursively adding all densely connected points to the cluster. Points not reachable from any other points are marked as noise.

## Theoretical Foundation

DBSCAN is based on a density-based notion of clusters and is designed to discover clusters of arbitrary shape. The algorithm defines a cluster as a maximal set of density-connected points. It captures the intuitive notion of "clusters" and "noise" in spatial data.

## Applications

DBSCAN's ability to find arbitrarily shaped clusters and its robustness to outliers make it applicable in various domains:

- **Geospatial Data Analysis**: Identifying areas of high traffic, land cover classification.
- **Astronomy**: Star cluster identification.
- **Anomaly Detection**: Fraud detection, system fault detection.
- **Image Processing**: Object separation in images for computer vision.
