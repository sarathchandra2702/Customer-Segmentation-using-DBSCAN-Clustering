# Customer Segmentation using DBSCAN Clustering

## Overview

This project applies **unsupervised machine learning** to perform **customer segmentation** using the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm. The goal is to identify natural groups of customers based on their purchasing patterns.

DBSCAN is particularly useful because it can discover clusters of **arbitrary shapes** and detect **outliers**, making it well-suited for real-world customer data.

---

## Problem Statement

Businesses often need to understand different groups of customers in order to design better marketing strategies, optimize product offerings, and improve customer experience.

The objective of this project is to apply **DBSCAN clustering** to identify distinct groups of customers based on their **spending behavior**.

---

## Dataset

This project uses the **Wholesale Customers Dataset**, which contains annual spending amounts of customers across different product categories.

### Dataset Features

The dataset includes customer spending on the following categories:

- Fresh products
- Milk
- Grocery
- Frozen products
- Detergents & Paper
- Delicatessen

Each row represents a **customer**, and each column represents the **annual spending in a product category**.

---

## Project Workflow

### 1. Data Loading

- Imported dataset using **Pandas**
- Inspected dataset structure and feature types

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the distribution of spending patterns:

- Examined feature distributions
- Identified relationships between product categories
- Visualized customer spending behavior

---

### 3. Data Preprocessing

Before applying clustering:

- Selected relevant numerical features
- Standardized the dataset using **feature scaling**
- Prepared the dataset for clustering analysis

---

## Clustering Model

This project uses the **DBSCAN algorithm**, a density-based clustering technique.

DBSCAN groups data points based on **density of points in a region** rather than distance to a centroid.

Key advantages of DBSCAN:

- Detects clusters of **irregular shapes**
- **Does not require specifying the number of clusters**
- Can identify **noise and outliers**

Important parameters used:

- **eps (epsilon)** – maximum distance between points in the same cluster
- **min_samples** – minimum number of points required to form a cluster

---

## Model Analysis

The clustering results help identify:

- Groups of customers with similar purchasing patterns
- High-value customer segments
- Potential outliers or unusual spending behaviors

These insights can help businesses make **data-driven marketing and sales decisions**.

---

## Key Insights

Some insights from the clustering analysis include:

- Customers with similar purchasing patterns tend to form natural clusters.
- Certain product categories strongly influence segmentation.
- DBSCAN can effectively identify **outlier customers with unusual spending behavior**.

---

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## Machine Learning Concepts Demonstrated

This project demonstrates key concepts in machine learning such as:

- **Unsupervised Learning**
- **DBSCAN Clustering**
- **Customer Segmentation**
- **Outlier Detection**
- **Exploratory Data Analysis**
- **Feature Scaling**

---

## Project Structure

```
DBSCAN-Customer-Segmentation/
│
├── DBSCAN_Project.ipynb
├── wholesome_customers_data.csv
└── README.md
```

---

## Future Improvements

Possible improvements for this project include:

- Applying **Principal Component Analysis (PCA)** for better cluster visualization
- Comparing DBSCAN with other clustering algorithms such as:
  - K-Means
  - Hierarchical Clustering
- Creating interactive visualizations for cluster analysis

---

## Conclusion

This project demonstrates how **DBSCAN clustering can be used to segment customers based on purchasing behavior**. By identifying natural clusters and detecting outliers, businesses can gain valuable insights into customer behavior and improve marketing strategies.
