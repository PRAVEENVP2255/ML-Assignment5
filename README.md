K-Means is a centroid-based clustering algorithm that partitions data into K clusters by minimizing the distance between data points and cluster centroids. It is an unsupervised learning algorithm used for grouping similar data points together.

 Steps in K-Means Clustering
1) Choose K (number of clusters).
2) Initialize K centroids randomly within the dataset.
3) Assign each data point to the nearest centroid.
4) Recalculate centroids by computing the mean of all points in each cluster.
5) Repeat Steps 3 & 4 until centroids stop changing.

Why Use K-Means for the Iris Dataset?
  Iris naturally forms three clusters, making K-Means a good choice.
  Fast and efficient for small-to-medium datasets.
  Easily interpretable results with clear cluster assignments.
  K-Means is widely used in real-world applications such as customer segmentation, anomaly detection, and pattern recognition. 


Hierarchical Clustering is an unsupervised learning algorithm that groups data into a hierarchy of clusters. Unlike K-Means, it does not require a predefined number of clusters and organizes data in a tree-like structure.

 Steps in Agglomerative Hierarchical Clustering
1)Compute the distance between every pair of data points.
2) Merge the two closest points/clusters into a new cluster.
3) Repeat Step 2 until only one large cluster remains.
4) Visualize using a dendrogram to decide the optimal number of clusters.


Why Use Hierarchical Clustering for the Iris Dataset?
 Works well for small datasets like Iris.
 Dendrogram provides insight into how data points are related.
 No need to predefine the number of clusters.
 Hierarchical Clustering is commonly used in gene sequencing, customer segmentation, and document clustering. 
