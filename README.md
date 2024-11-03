# 🔍 ML Clustering Explorations
This repository contains a series of notebooks exploring various clustering techniques in machine learning. Each notebook demonstrates different methods, compares their performance, and provides insights into their strengths and weaknesses. These explorations are useful for understanding data science clustering techniques, such as choosing the right method for different data structures and how these methods handle different clustering challenges.

## 📒 Notebooks Overview

1. **🌀 Comparing K-Means and DBSCAN Algorithms**  
   This notebook explores two popular clustering algorithms, **K-Means** and **DBSCAN**. We compare their behavior on different datasets, examining how they respond to various shapes, densities, and distributions of data points.

2. **🔄 Gaussian Mixture Models (GMM)**  
   This notebook dives into **Gaussian Mixture Models (GMM)** for clustering. We cover the probabilistic foundations of GMMs, model fitting, and visualization. The notebook highlights how GMMs can capture complex cluster shapes by assuming data comes from a mixture of Gaussian distributions.

3. **📉 Principal Component Analysis (PCA)**  
   Here, we explore **Principal Component Analysis (PCA)** as a tool for dimensionality reduction and feature extraction. Although PCA isn’t a clustering method itself, this notebook demonstrates how it can aid clustering by reducing data dimensionality and improving the interpretability of results.

4. **🌳 Hierarchical Clustering**  
   This notebook examines **Hierarchical Clustering**, an algorithm that builds nested clusters in a tree structure (dendrogram). We explore different linkage criteria, visualize the dendrogram, and discuss how to select the optimal number of clusters.

## 🚀 Getting Started

### 🔧 Prerequisites
- Python 3.12.7
- Jupyter Notebook
- Common Python libraries such as:
  - ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  - ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  - ![Matplotlib](https://img.shields.io/badge/Matplotlib-35495E?style=for-the-badge&logo=python&logoColor=white)
  - ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
  - ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
  
  
Install the required libraries using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 📂 Repo Structure
```bash
ML_Clustering_Explorations/
│
├── KMeans_vs_DBSCAN.ipynb
├── GMM.ipynb
├── PCA.ipynb
└── Hierarchical_Clustering.ipynb
```
