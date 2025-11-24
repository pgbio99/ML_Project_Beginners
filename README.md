# K-Means Clustering for Prioritizing Critical Downregulated Genes (BRCA Subtypes)
Analyzing gene expression data from BRCA subtypes (using a GEO dataset) after Normalization and Differential Expression Analysis (DEA). The challenge is to filter and prioritize the large list of downregulated genes.
We applied Unsupervised Learning (K-Means) to the final list of downregulated genes to segment them based on their expression profiles. This is where the ML step provides value by creating an objective classification.
To ensure our classification is statistically sound, we utilized the Elbow Method (calculating WCSS for K=1 to K=X). The elbow point clearly suggested K=3 as the optimal number of clusters for this specific biological dataset.
The K-Means model successfully categorized the downregulated genes into three clusters, which we interpret as levels of biological significance:
* Red Cluster (Cluster 1): Highly Significant Downregulation. These are the primary candidates for follow-up functional studies.
* Pink Cluster: Moderate Downregulation.
* Green Cluster: Low Downregulation.
This project showcases how ML can be a powerful decision-support tool in genomics.
