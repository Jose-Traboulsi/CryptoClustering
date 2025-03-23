Crypto Clustering Project

Overview

This project applies clustering techniques to analyze cryptocurrency market data. It leverages machine learning to identify distinct clusters of cryptocurrencies based on their market characteristics.

Technologies Used

Python

Pandas

Scikit-learn (KMeans, PCA, StandardScaler)

HvPlot for visualization

Dataset

The dataset used in this project is crypto_market_data.csv, which contains various cryptocurrency metrics. The data is preprocessed and used for clustering analysis.

Installation

Install the required dependencies:

pip install pandas scikit-learn hvplot

Ensure you have Jupyter Notebook installed to run the Crypto_Clustering.ipynb file.

Steps in the Notebook

Load Data: Import the dataset and perform initial exploration.

Preprocessing: Standardize the data using StandardScaler.

Clustering: Apply K-Means clustering to segment cryptocurrencies.

Dimensionality Reduction: Use PCA for visualization.

Visualization: Generate interactive plots to analyze cluster results.

Running the Notebook

Open Jupyter Notebook and run the Crypto_Clustering.ipynb file step by step to reproduce the clustering analysis.

Results

Identifies groups of cryptocurrencies based on similar market behavior.

Provides insights into market trends through visualizations.
