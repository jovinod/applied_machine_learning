# {About}

* The KMeans algorithm clusters data by trying to separate samples in n groups of *equal variance*, minimizing a criterion known as the inertia or *within-cluster sum-of-squares*. This algorithm requires the number of clusters to be specified. It scales well to large number of samples and has been used across a large range of application areas in many different fields.
    * The *equal variance* here is an assumption. K-Means inherently assumes that the variance across each group is constant. In fact the variation across each dimension is also constant. This is also the reason it results in Spherical, Convex or Isotrpoic clusters 
    * The *within-cluster sum-of-squares* is the overall summation of distance of each point to its centroid
    * K-means is often referred to as **Lloyd’s algorithm**
    * K-means is equivalent to the expectation-maximization algorithm with a small, all-equal, diagonal covariance matrix.

*An arial view of cluster of localities in Dehradun*
![Arial](Cluster.jpg "Arial View of cluster of localities in Dehradun")
