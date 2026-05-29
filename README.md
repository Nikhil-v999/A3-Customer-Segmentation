# A3 — Customer Segmentation + Anomaly Detection

## What this project does
Takes 541k raw retail transactions and identifies distinct customer segments
and unusual customers using unsupervised machine learning.

## Dataset
Online Retail Dataset — UCI Machine Learning Repository
541,909 transactions | 8 columns | UK-based online retailer 2010-2011

## Techniques used
- RFM Feature Engineering (Recency, Frequency, Monetary)
- K-Means Clustering (K=4)
- Elbow Method + Silhouette Score
- PCA for visualization
- Isolation Forest for anomaly detection
- Z-score comparison

## How to run
pip install pandas numpy matplotlib seaborn scikit-learn scipy
jupyter notebook notebook.ipynb

## Key results
- 4 customer segments found: Champions, Regular, New, Lost
- 217 anomalous customers detected out of 4338
