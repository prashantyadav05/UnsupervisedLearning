# Unsupervised Learning
## k-means Clustering
k-means works by searching for K clusters in your data. Here is the no-math algorithm of k-means clustering:
1. Pick K centroids (K = expected distinct # of clusters).
2. Randomly place K centroids anywhere amongst your existing training data.
3. Calculate the Euclidean distance from each centroid to all the points in your training data.
4. Training data points get grouped in with their nearest centroid.
5. Amongst the data points grouped into each centroid, calculate the mean data
point and move your centroid to that location.
6. Repeat this process until convergence, or when the membership in each group no longer changes.
## Hierarchical Clustering
1. Given n sample data points, view each point as an individual "cluster" with just that one point as a member.
2. Calculate the pairwise Euclidean distance between the centroids of all the clusters in your data.
3. Group the closest point pairs together.
4. Repeat Step 2 and Step 3 until you reach a single cluster containing all the data inyour set.
5. Plot a dendrogram to show how your data has come together in a hierarchical structure. A dendrogram is simply a diagram that is used to represent a tree structure, showing an arrangement of clusters from top to bottom.
6. Decide what level you want to create the clusters at. An Example Walk-Through of Hierarchical Clustering
## Neighborhood Approaches and DBSCAN
1. Given n unvisited sample data points, move through each point in a loop and mark
as visited.
2. From each point, look at the distance to every other point in the dataset.
3. For all points that fall within the neighborhood radius hyperparameter, connect
them as neighbors.
4. Check to see whether the number of neighbors is at least as many as the minimum
points required.
5. If the minimum point threshold is reached, group together as a cluster. If not, mark the point as noise.
6. Repeat until all data points are categorized in clusters or as noise.
## Dimension Reduction and PCA
## Autoencoders
## Market Basket Analysis
## Hotspot Analysis
