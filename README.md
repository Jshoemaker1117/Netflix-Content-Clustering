# Netflix Content Clustering Analysis

## Project Overview

This project applies **unsupervised machine learning (K-Means clustering)** to group Netflix movies and TV shows based on content characteristics such as release year, duration, and genre-related features.

The goal is to uncover hidden patterns in Netflix’s catalog that can support **content strategy, recommendations, and audience segmentation**.

---

## Objective

* Identify natural groupings within Netflix content
* Determine the optimal number of clusters using data-driven evaluation
* Translate clustering results into business-relevant insights

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## Dataset

* ~8,800 Netflix movies and TV shows
* Features engineered from raw metadata:

  * Release year
  * Duration
  * Encoded content attributes

---

## Methodology

1. Data cleaning and preprocessing
2. Feature engineering and scaling
3. Elbow Method and Silhouette Score evaluation
4. K-Means clustering (k = 5)
5. PCA visualization for cluster interpretation

---

## Results & Insights

* Identified **5 distinct content clusters**
* Clear separation between short-form vs long-form content
* Patterns related to release era and content structure
* Insights applicable to recommendation systems and content acquisition

---

## Outputs

* `netflix_clustered_final.csv`
* `netflix_clustered_analysis.csv`
* `netflix_clustered_pca.csv`

---

## Future Improvements

* Add NLP features from descriptions
* Compare with DBSCAN or Hierarchical Clustering
* Build an interactive dashboard

---

## Status

Project complete and portfolio-ready.

