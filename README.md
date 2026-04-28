# Unsupervised-Learning-K-Means-DBSCAN-Clustering

### Project Overview

#### This project demonstrates unsupervised learning using K-Means and DBSCAN clustering algorithms. The goal is to group similar data points together and compare how both algorithms behave on different data shapes.
---

### Algorithms Used

1. K-Means Clustering
- Divides data into K clusters
- Uses centroid-based approach
- Works best for circular clusters
- Requires number of clusters (K)

2. DBSCAN Clustering
- Density-based clustering algorithm
- Detects irregular cluster shapes
- Automatically identifies noise points
- Does not require number of clusters
---

### Dataset

Synthetic datasets are generated using sklearn:
- Blob dataset (for K-Means)
- Moon-shaped dataset (for DBSCAN comparison)
---

### Results

K-Means:

- Works well for circular clusters
- Requires manual K selection
- Fails for non-linear data

DBSCAN:

- Handles irregular shapes
- Detects noise points
- No need to specify cluster count
