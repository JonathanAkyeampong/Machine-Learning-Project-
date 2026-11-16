# COM7022 Machine Learning – Task 1: Product Clustering

Clustering of 1,000 e-commerce fragrance listings (`Sales-5444.csv`) into segments by product characteristics and sales performance.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JonathanAkyeampong/Machine-Learning-Project-/blob/main/COM7022_Task1_Clustering.ipynb)

## Contents
- `COM7022_Task1_Clustering.ipynb`: the full analysis: data cleaning, feature engineering, scaling, PCA, K-Means, agglomerative (Ward) and DBSCAN clustering, model comparison and stability, and cluster profiling with written analysis.
- `Sales-5444.csv`: the dataset.

## Running
Open the notebook in Colab (badge above) or Jupyter, keep `Sales-5444.csv` in the same folder, and run all cells. Requires pandas, numpy, scikit-learn, scipy, matplotlib and seaborn.

## Result
K-Means (k = 4) was selected as the final model and produced four segments: High-volume best-sellers, Premium slow movers, Stale listings and Travel-size & minis.
