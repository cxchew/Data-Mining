# Project Phase 2: Unsupervised Pattern Extraction via Advanced Clustering Engines 🔍

## 1. Project Summary
Phase 2 shifted the project scope from supervised classification models toward unsupervised machine learning frameworks to discover natural, hidden employee groupings within the tech sector. Utilizing the same normalized survey logs, the technical execution focused on the following structural stages:
* **Dimensionality Preparation and Scaling Staging:** Transformed categorical inputs into mathematical spaces, configuring data arrays to run safely inside distance-sensitive unsupervised clustering algorithms.
* **K-Means Centroid Allocation Modeling:** Built iterative K-Means models to partition the data space. I used the Elbow Method to trace total within-cluster sum of squares (WCSS) trends and determine the optimal cluster size ($k=2$).
* **Agglomerative Hierarchical Tree Synthesis:** Built independent bottom-up clustering trees, using Ward's linkage methods to construct structural dendrograms that visually map how employee groups naturally connect.
* **Multi-Cluster Characteristic Profiling:** Evaluated and cross-profiled the resulting clusters, identifying distinct workforce segments—such as a well-supported work-from-home group versus an isolated in-office segment—to provide actionable workplace recommendations.

---

## 2. Evidence and Explanation

<img src="images/Screenshot 2026-06-21 015024.png" width="500" alt="Unsupervised Clustering Synthesis">

*Figure 1: Unsupervised Clustering Synthesizer and Metric Matrix Evaluation*

* **Optimal Grouping Configuration:** Ran structural iterations to establish mathematical cut-off boundaries, using WCSS elbow charts to find clean cluster splits that minimize internal data variance.
* **Natural Group Profiling Validation:** Partitioned the workspace dataset into distinct, actionable segments, as shown in **Figure 1**. This analysis revealed how remote work privileges and mental health benefits naturally align to influence overall employee satisfaction.

---

## 3. Reflection

### What I Learned
* Implementing unsupervised clustering models completely changed how I look at pattern discovery. Seeing how algorithms find distinct employee groups without using predefined labels showed me the true analytical power of exploratory data mining.
* Analyzing the mathematical differences between distance models taught me how to match algorithms to data structures. While K-Means cleanly separated distinct employee groups, Hierarchical dendrograms provided a clearer picture of how sub-segments naturally link together like tree branches.
