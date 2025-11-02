# 🎮 K-Means Clustering on Game Sales Data

This project uses **K-Means Clustering** to analyze and segment video game sales data based on `Units Sold`, `Price`, `Platform`, and `Region`.

## 🧠 Project Overview
- Cleaned and preprocessed the dataset  
- Converted categorical data to numeric using One-Hot Encoding  
- Scaled data using StandardScaler  
- Applied **Elbow Method** (WCSS) and **Silhouette Score** to find the optimal number of clusters  
- Trained final **K-Means model with k=5**  
- Used **PCA** to visualize clusters in 2D  

## 📊 Results
- Cluster 0: High sales, average price → most demanded games  
- Cluster 2: High price, low sales → premium niche games  
- Other clusters represent balanced and moderate performers  
- PCA visualization shows clear cluster separation.

## 🧩 Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## 📈 Key Insights
> The clustering reveals distinct market segments based on **sales performance** and **pricing strategy**, helping understand demand trends across platforms and regions.
