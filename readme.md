# Don't just stick to K-Means anymore! 10 clustering algorithms in MATLAB for practical use, and directly reproducing scientific visualizations.

For conducting cluster analysis, you might have encountered the following questions: if there are outliers in the data, can K-Means still be used? *Why do circles and bent data always cluster incorrectly?** What should I do when I'm unsure how many classes to divide? This time, I have systematically organized the commonly used clustering algorithms: 3 major categories, 10 algorithms, all accompanied by MATLAB complete codes and visualization results. **

01 | 10 Clustering Algorithms, All in One Collection
① K-Means Clustering: The most classic partitioning clustering method, with centroid iteration updating, suitable for quickly understanding the basic idea of clustering.
② K-Medoids Clustering: Center is directly selected from real sample points, more robust to outliers compared to K-Means.
③ FCM Fuzzy C Means Clustering: A single sample is no longer "forced" into a single class but has different membership degrees to various classes, especially suitable for data with fuzzy boundaries.
④ DBSCAN Clustering: No need to prespecify the number of classes, can identify concentric rings, bent bands, etc., non-convex clusters, and can also automatically discover noise points.
⑤ DENCLUE Clustering: Based on kernel density estimation and density attractor, find potential cluster structures from the perspective of "data density."
⑥ GMM Gaussian Mixture Model Clustering: Not only consider distances, but also model means, covariances, and mixing weights, more flexible for clusters with elliptical shapes, orientations different, and scales different.
⑦ Spectral Clustering: Convert data into a graph structure, re-represent samples through Laplacian matrix eigenvectors, especially interesting for concentric rings, nonlinear separable structures.
⑧ Hierarchical Clustering: Starting from individual samples and continuously merge until a tree-like clustering diagram is formed.
⑨ CLIQUE Grid Clustering: Divide space into grids and discover cluster structures by finding dense grids and connected regions, can also directly generate grid density heatmaps.
⑩ AP Nearest Neighbor Propagation Clustering: Without prespecifying K, through continuous "message passing" between samples, automatically find representative points and determine the cluster structure.
02｜The truly useful is not just "running the code". Many online clustering codes end up with only one result: red, blue, yellow dots... It can run, but it's far from reaching the paper plotting stage. Therefore, in this chapter, apart from the clustering results, we have specially designed different ways to represent the results:
✅ Clustered point distribution
✅ Cluster centers / Medoid / Exemplar markers
✅ Bar chart of sample counts by category
✅ FCM maximum membership distribution
✅ DBSCAN neighborhood point count distribution
✅ Density isosurface of DENCLUE
✅ GMM probability density isosurface
✅ Spectral clustering feature values and spectral gaps
✅ Hierarchical clustering tree diagram
✅ CLIQUE grid density heatmap
✅ Even though we are doing clustering, the result graph could be more than one "colored point plot." Especially when writing a thesis, SCI papers, or conducting algorithm comparison experiments, how to present the results is actually a very important part.
Also welcome to share with that -
"No matter what data, first run K-Means."😂

## Images

![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](01.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](02.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](03.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](04.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](05.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](06.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](07.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](08.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](09.png)
![Stop relying solely on K-Means! 10 clustering algorithms in MATLAB for practical use, and direct reproduction of scientific plots.](10.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
