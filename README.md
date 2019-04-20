# News_Text_Clustering

Input data (provided as training data) consists of 8580 text records in sparse format.

Cluster the data such that you obtain > 100 clusters using an off-the-shelf clustering
method (e.g., K-means).

A variation of the DBSCAN clustering algorithm that takes as input clusters,
rather than individual points. Compute inter-cluster distances to identify which points
are core, border, or noise points.

Assign each of the instances in the input data to K
clusters identified from 1 to K. All objects in the training data set must be assigned to a
cluster so noise points are assign to cluster K+1 or applied post-processing
after DBSCAN and assign noise points to the closest cluster.


Evaluation metric -- Normalized Mutual Information Score (NMI)

