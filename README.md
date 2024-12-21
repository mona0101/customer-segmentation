# Customer Segmentation using K-Means Clustering 🛒

This project performs customer segmentation based on purchasing behavior using K-means clustering. It involves data cleaning, feature engineering, PCA for dimensionality reduction, and clustering.

## Steps Overview 📊

### 1. Data Preparation 🧹
- Read data from "Online Retail.xlsx".
- Clean the data by removing missing values and negative values from `Quantity` and `UnitPrice`.
- Handle outliers using box and violin plots.

### 2. Feature Engineering 🔧
- Added features like `OrderFrequency`, `TotalSpending`, `Recency`, and `BasketSize`.
- Aggregated customer data to create a consolidated view of customer behavior.

### 3. Principal Component Analysis (PCA) 🔍
- Scaled the data and determined the optimal number of PCA components (4 components).
- Applied PCA for dimensionality reduction.

### 4. Determining Optimal Number of Clusters 🔢
- Used the elbow method to determine 6 clusters.

### 5. K-Means Clustering 🔀
- Applied K-means with 6 clusters to segment customers.
- Analyzed cluster characteristics such as recency, spending, and order frequency.

### 6. Cluster Profiling 🧑‍💼
- Visualized the average metrics per cluster (Order Frequency, Total Spending, Basket Size, Recency).
- Explored the distribution of countries within clusters.

### 7. Visualization 📈
- Used t-SNE to visualize clusters in a 2D space before and after clustering.

### 8. Evaluation 🔍
- Assessed clustering quality using silhouette scores.

## Dependencies 📦
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Results 🎯
- Customer segments were identified, each exhibiting unique purchasing patterns, providing insights for targeted marketing strategies.
