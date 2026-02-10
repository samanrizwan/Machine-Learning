This repository contains a learning experiment exploring how K-Means clustering can be applied to text data. The focus is simply to understand
how unsupervised algorithms work with textual features.


Algorithm: K-Means clustering

Data Type: Text documents (short sentences)

Goal: Group similar sentences into clusters based on content

This code demonstrates how text can be converted into numerical features (TF-IDF) and clustered. 
Visualizations using dimensionality reduction help illustrate the clusters.

Notes & Recommendations

Small datasets (like a few sentences) may produce unreliable clusters, often assigning most points to a single cluster.

For better results, consider:

- Using a larger dataset with more documents per topic

- Normalizing vectors to simulate cosine similarity

- Using n-grams to capture word combinations

- Exploring other clustering algorithms such as Agglomerative Clustering or DBSCAN
