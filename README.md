# Cryptocurrency Clustering with K-Means and PCA

This project demonstrates the use of K-Means clustering and Principal Component Analysis (PCA) to cluster cryptocurrencies based on their price change percentages. The main goal is to group cryptocurrencies with similar price change patterns into distinct clusters, which can provide valuable insights for investors and traders.

## Dataset
The dataset used in this project is titled "crypto_market_data.csv," which contains various price change percentage metrics for different cryptocurrencies over specific time intervals.

## Requirements
To run this project, you will need the following libraries installed in your Python environment:
- pandas
- hvplot
- scikit-learn

You can install these libraries using pip:
`pip install pandas hvplot scikit-learn`


## Project Structure
The project is organized into different steps:

1. Data Loading and Preparation
   - The data is loaded into a Pandas DataFrame and preprocessed for clustering.

2. Finding the Optimal Number of Clusters (K)
   - The Elbow Method is used to determine the optimal number of clusters for K-Means.

3. Clustering with K-Means using Original Data
   - K-Means is applied to the original data to cluster cryptocurrencies based on price change percentages.

4. Principal Component Analysis (PCA)
   - PCA is used to reduce the dimensionality of the data while retaining essential information.

5. Clustering with K-Means using PCA Data
   - K-Means is applied to the PCA-transformed data for clustering.

6. Visualization and Comparison
   - Composite plots are created to compare the Elbow curves and cryptocurrency clusters for both original and PCA data.

## How to Use
1. Make sure you have the required libraries installed in your Python environment.
2. Download the dataset "crypto_market_data.csv" and place it in the "Resources" folder.
3. Run the provided Python script step by step to go through the entire process of data preparation, clustering, and visualization.

## Results
The project aims to find meaningful clusters of cryptocurrencies based on their price change percentages. The Elbow curves help identify the optimal number of clusters for K-Means. The PCA-transformed data is used to perform clustering with reduced features, which can be computationally efficient and help in visualization. The visualization of clusters provides insights into the relationship between cryptocurrencies with similar price change patterns.

Overall, this project demonstrates the application of machine learning techniques like K-Means and PCA to analyze and group cryptocurrencies for investment and trading purposes.

