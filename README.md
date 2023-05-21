# Cryptocurrency Market Analysis with Clustering

This project performs an analysis of cryptocurrency market data to identify distinct groups of similar cryptocurrencies. This is achieved by using K-Means clustering and Principal Component Analysis (PCA).

The process followed in the project is:

1. **Data Importing:** Cryptocurrency market data is loaded into a pandas DataFrame from a CSV file.

2. **Data Preparation:** The data is then standardized using Scikit-Learn's StandardScaler.

3. **Determining Optimal Number of Clusters:** The optimal number of clusters (k) for K-Means is determined using the Elbow method.

4. **Clustering with K-Means:** The K-Means algorithm is used to cluster the cryptocurrencies.

5. **Dimensionality Reduction with PCA:** The dataset's dimensionality is reduced using PCA, which transforms it into a set of new orthogonal variables that maximize the variance.

6. **Determining Optimal Number of Clusters with PCA Data:** The optimal number of clusters is determined again using the elbow method, but this time using the PCA-transformed data.

7. **Clustering with PCA data:** The K-Means algorithm is applied again, this time using the PCA-transformed data.

8. **Visualization and Comparison of Results:** The cluster analysis results from the original data and the PCA-transformed data are visualized and compared.

## Technologies Used

* Python
* Pandas
* hvPlot
* Scikit-Learn

The findings can provide insights into the behavior of different cryptocurrencies, enabling better understanding of market trends and aiding in investment decision making.

## Getting Started

1. Clone this repository.
2. Install required Python packages:
   * pandas
   * hvplot
   * scikit-learn
3. Run the Jupyter Notebook.

