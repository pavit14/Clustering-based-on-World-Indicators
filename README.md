# Clustering-based-on-World-Indicators
This project aims to cluster countries based on their socio-economic indicators using the K-means clustering algorithm. The analysis is performed on a real-life World Bank Indicators dataset, which contains a variety of socio-economic indicators for countries around the world.

Understanding the socio-economic development of countries is crucial for making informed decisions in fields such as international development and global economics. This project aims to provide valuable insights into country clustering based on their socio-economic indicators using data-driven methods.

### <a href='https://databank.worldbank.org/source/world-development-indicators'> Dataset </a>


## Features
* Imported a real-life World Bank Indicators dataset for countries and prepared it for analysis using Python's numpy and pandas libraries.
Performed data cleaning and normalization to ensure accurate clustering results.
* Employed the Elbow Method, Silhouette Score, and Calinski-Harabasz Index to determine the optimal number of clusters for the K-means algorithm.
* Conducted clustering using both K-means and Hierarchical Clustering methods.
* Visualized the clustering results through scatter plots, allowing for easy identification of clusters with similar socio-economic indicators.

## Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## Methodologies
* Data Preprocessing:
- Imported the World Bank Indicators dataset and performed necessary data cleaning and transformation using pandas and numpy.
- Normalized the data to bring all indicators to a similar scale, ensuring each indicator contributes equally to the clustering process.
* Determining Optimal Clusters:
- Utilized the Elbow Method, Silhouette Score, and Calinski-Harabasz Index to determine the ideal number of clusters for the K-means algorithm.
* Clustering:
- Applied the K-means clustering algorithm to group countries based on their socio-economic indicators.
- Explored Hierarchical Clustering as an alternative method for comparison.
* Visualization:
- Visualized the clustering results using scatter plots, where each data point represents a country with socio-economic indicators.

## Results
The clustering results offer valuable insights into the socio-economic development of different countries. The scatter plot visually demonstrates how countries are grouped into clusters based on similar socio-economic indicators. This information can be leveraged for decision-making in fields such as international development and global economics.
