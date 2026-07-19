# K-Means Clustering From Scratch

This project was completed as part of the  
**Algorithm Design and Analysis for AI** course.

## Project Overview

The goal of this project is to implement the **K-Means Clustering algorithm from scratch using NumPy**, without using the ready-made KMeans model from scikit-learn.

The algorithm groups unlabeled data points into clusters by repeatedly assigning each point to its nearest centroid and updating the centroids until convergence.

## Dataset

The dataset was generated using:

python
sklearn.datasets.make_blobs

# Dataset Details

- 500 samples
- 2 features
- 4 clusters
- Random state: 42

## Algorithm Steps

1. Initialize `k` random centroids.
2. Calculate the Euclidean distance between each point and every centroid.
3. Assign each point to its nearest centroid.
4. Recompute each centroid as the mean of the points assigned to it.
5. Repeat the assignment and update steps until convergence.
6. Return the cluster ID assigned to every data point.

## Technologies Used

- Python
- NumPy
- scikit-learn datasets
- Google Colab
- Jupyter Notebook

## Evaluation

Since K-Means is an unsupervised algorithm, each predicted cluster was mapped to its majority true label.

## Final Result

**Clustering Accuracy: 100%**

