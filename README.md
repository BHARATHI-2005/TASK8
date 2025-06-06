Task 8: Clustering with K-Means

Objective
Perform **unsupervised learning** using **K-Means Clustering** on the Mall Customers dataset to segment customers into groups based on similar characteristics.

Dataset
- Name:Mall_Customers.csv  

Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- PCA for visualization  
- KMeans for clustering

Steps Followed

1. Data Loading:Loaded dataset using pandas.
2. Preprocessing:Selected relevant features and standardized data using `StandardScaler`.
3. Elbow Method:Used to find the optimal number of clusters `k`.
4. K-Means Clustering: Applied KMeans with optimal `k` (in this case, 5).
5. PCA Visualization:Reduced features to 2D for plotting clusters.
6. Evaluation:Calculated Silhouette Score to evaluate clustering quality.

Elbow Curve
The Elbow method was used to determine the optimal number of clusters by plotting the inertia values for `k = 1` to `10`.  
Optimal k = 5

Cluster Visualization
A 2D scatter plot was created using PCA to visualize the clusters, with each point colored by its assigned cluster.

 Evaluation

- Silhouette Score: Measures how similar an object is to its own cluster vs others.  
Score Achieved:e.g., 0.55(Higher is better)

Files in This Repository

| File Name            | Description                                |
|---------------------|--------------------------------------------|
| `Mall_Customers.csv`| Dataset used for clustering                |
| `task8_kmeans.ipynb`| Main code notebook for the task            |
| `README.md`          | Project explanation and report             |
| `cluster_plot.png`  | Screenshot of cluster visualization (optional) |
| `elbow_plot.png`    | Screenshot of Elbow Method plot (optional)  |
