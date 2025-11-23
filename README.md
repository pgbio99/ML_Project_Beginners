# KMeans Clustering to study downregulated genes (BRCA-subtypes)
BRCA subtypes The GEO dataset is chosen, followed by normalization and differential expression analysis. Downregulated genes are sorted from the differentially expressed genes data. Here, the downregulated genes file is used to perform KMeans clustering.

To analyze the downregulated genes on a scale of low, moderate, and high, the KMeans clustering machine learning model is applied to the data. Here, K=3 is chosen as suggested by the elbow plot, resulting in clustering all the downregulated genes in three respected clusters.

From this clustering, it is interpreted that the genes that fall under the red cluster (cluster value 1) are characterized as highly significant downregulated genes. The genes in the pink cluster show moderate significant downregulation, while those in the green cluster show low significant downregulation.
