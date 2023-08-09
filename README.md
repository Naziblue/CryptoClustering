# CryptoClustering
Module 18


---

# Crypto Clustering

Crypto Clustering is a project aimed at grouping different cryptocurrencies based on their market data to identify patterns and relationships among them.

## Overview

The project utilizes various data science techniques and tools, including KMeans clustering, Principal Component Analysis (PCA), and interactive visualization using `hvplot`. By clustering cryptos, we can better understand the market and make more informed investment decisions.

## Dataset

The dataset used in this project contains various market metrics for different cryptocurrencies, including percentage price changes over different timeframes.

## Features

1. **Data Cleaning & Exploration**: Loaded and explored the cryptocurrency market data, visualizing initial data trends.
2. **Data Preprocessing**: Used `StandardScaler` from scikit-learn to normalize the data for better clustering results.
3. **KMeans Clustering**: Implemented KMeans clustering to group the cryptocurrencies.
4. **Elbow Method**: Used the elbow method to find the optimal number of clusters (k) for our dataset.
5. **PCA (Principal Component Analysis)**: Reduced the dimensionality of the data for visualization and to observe the effect of dimensionality reduction on clustering.
6. **Visualization**: Leveraged `hvplot` for interactive visualizations to visually inspect clusters and the elbow curve.

## Key Findings

1. **Optimal Number of Clusters**: Both the original and PCA-reduced data suggest an optimal k value of 4.
2. **PCA Explained Variance**: The three principal components used in the PCA accounted for approximately 89.5% of the total variance.
3. **Cluster Analysis**: Based on the scatter plots, two clusters were distinctly separate from the rest, suggesting these cryptos have unique characteristics different from the majority.

## Requirements

- Python
- Pandas
- Scikit-learn
- hvplot
- matplotlib

## Usage

1. Clone the repository.
2. Ensure all the required libraries are installed.
3. Run the script in your preferred environment.
4. Analyze the hvplot visualizations to understand crypto clustering results.

## Conclusion

Crypto Clustering allows for a deeper understanding of the similarities and differences among various cryptocurrencies. By reducing dimensionality with PCA and using KMeans clustering, we can categorize cryptos and potentially unveil hidden market trends.

---
