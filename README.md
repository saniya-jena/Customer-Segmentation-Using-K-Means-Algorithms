# Customer-Segmentation-Using-K-Means-Algorithms
The project performs Customer Segmentation using KMeans Clustering and PCA. Here's a brief overview:

Data Import & Cleaning:
- Loads the dataset, removes irrelevant columns, and handles outliers.

Exploratory Data Analysis (EDA):
- Visualizes Gender, Age, Annual Income, and Spending Score distributions.

Feature Engineering:
- Encodes the Gender feature and scales numerical features for consistency.

Cluster Analysis:
- Uses the Hopkins Score to check data suitability for clustering.
- Determines the optimal number of clusters using the Elbow Method and Silhouette Score (5 clusters chosen).

KMeans Clustering:
- Creates 5 customer segments with unique spending and income characteristics.
- Visualizes clusters with distinct colors and centroids.
  
PCA (Principal Component Analysis):
- Reduces data to 2D to improve visualization and resolve overlapping clusters.
  
Business Insights:
- Identifies key customer groups like Budget Shoppers, Big Spenders, and Potential Buyers for targeted marketing strategies.
