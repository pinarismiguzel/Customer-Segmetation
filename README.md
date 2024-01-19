We have Mall customer data to cluster them according to their Age, Annual Income, and Spending Score.

We get the first insight into five different customer segments using visualization tools.

Before modeling, we used Hopkins Statistics to understand if our data was suitable for clustering. We got a 0.16 score, which shows that the data is not uniformly distributed. Clustering can be useful to classify the observations.

We build two relations based on the Spending Score; the first variable is Age, and the second one is Annual Income. We consider these two relations, 'Age-Spending Score' and 'Annual Income and Spending Score', for clustering our customers.

We separately determine the optimal number of clusters using the elbow method, Silhouette Score, for K-means modeling for these two data sets. We got 4 clusters for the 'Age - Spending Score' data set and 5 clusters for the 'Annual Income - Spending Score' data set according to the Elbow method and Silhouette Score.

The k-Means model made good predictions for our clusters as Customer Segments. We also showed our predicted clusters using plotting.

We also used a dendrogram to determine an optimal number of clusters, but dendrogram clusters were incompatible with Silhouette scores. So, we disregarded the Dendogram results for agglomerative clustering.

In conclusion, to cluster our customers in different segments, 'Annual Income and Spending Score' gives better results.
