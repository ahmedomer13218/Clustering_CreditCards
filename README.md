# Clustering Techniques on Credit Card Dataset  

This repository demonstrates the application of multiple clustering techniques on a Credit Card dataset. The project explores preprocessing, feature engineering, dimensionality reduction, and the evaluation of clustering performance using various metrics.  

## Table of Contents  
- Overview  
- Dataset  
- Key Features  
- Project Structure  
- Installation  
- Usage  
- Evaluation Metrics  
- Contributing  
- License  

## Overview  
This project applies and evaluates three clustering methods:  
- **K-Means++**  
- **DBSCAN**  
- **Agglomerative Clustering**  

It explores the impact of data preprocessing (scaling, transformation) and dimensionality reduction on clustering results, with comprehensive evaluations using Silhouette Scores, WCSS, and visualizations.  

## Dataset  
The dataset used for this project can be found [here](https://www.kaggle.com/code/nataliaole/cc-general-clustering).  

## Key Features  
1. **Data Preprocessing**  
   - Data exploration, feature cleaning, and imputation.  
   - Applied transformations (Box-Cox, Yeo-Johnson, Log) and scaling (Standard, MinMax, Robust).  
   - Dimensionality reduction for improved clustering.  

2. **Clustering Techniques**  
   - **K-Means++**: Explored multiple transformation and scaling combinations, with WCSS and Silhouette Score evaluations to select the best clusters.  
   - **DBSCAN**: Tested different `eps` and `min_samples` combinations for optimal clustering.  
   - **Agglomerative Clustering**: Used dendrograms and Silhouette Scores to identify the best number of clusters, testing linkage methods (Ward, Complete, Average, Single).  

3. **Ready-to-Use Functions**  
   - Predefined functions for clustering tasks, making this notebook highly reusable for similar projects.  

## Project Structure   
- [Clustering_CreditCard.ipynb](./Clustering_CreditCard.ipynb)  
- [LICENSE](./LICENSE)  
- [CC GENERAL.csv](./CC GENERAL.csv)  
- [README.md](./README.md)  

### Data Preprocessing  
- Loaded and explored the dataset.  
- Applied feature engineering and imputation techniques.  
- Transformed and scaled features for clustering compatibility.  

### Installation  
- Clone this repository:  
```bash  
git clone https://github.com/ahmedomer13218/Clustering_CreditCards  

cd Clustering_CreditCards  
```
### Usage
Open and run the Clustering_CreditCard.ipynb notebook.

### Evaluation Metrics
- WCSS (Elbow Method)
- Silhouette Score
- Visual Inspection of clustering results.

### Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

###
This repository provides a complete guide to clustering techniques, offering detailed analysis and reusable functions for efficient implementation. 🎯
