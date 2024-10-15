## K Means Clustering using NumPy on the Old Faithful Dataset

### Variables: 
1. `k`: number of clusters
2. `d`: number of data pts
3. `data`: stores imported csv file (d, data_dim)
4. `cluster`: cluster centre coordinates (k, data_dim)
5. `assign`: calculates Euclidean(L2) norm of each data point from each cluster (d, k)
6. `temp`: hard assignment of clusters. nearest center =1 (d, k)
7. `index`: assigned cluster number for each data point (d) 

### Functions:
1. clustering(): returns `assign` with calculated Euclidean distances and `temp` with hard assignment of data.  
2. re_mean(): calculates the new `cluster` with newly clustered data points. 
