Developed a machine learning project to cluster Iris flowers based on sepal and petal features using K-Means. Performed EDA, scaling, inertia & silhouette analysis to find optimal clusters. Deployed a Streamlit app to predict cluster assignments for new samples in real-time.

# 🌼 Iris Flower Species Clustering using K-Means

This project applies **unsupervised learning** to cluster Iris flowers based on sepal and petal dimensions using K-Means. It includes **EDA, feature scaling, cluster evaluation**, and deployment via **Streamlit**.

---

## 🚀 Project Overview

The Iris dataset contains 150 samples with 4 features: `sepal length`, `sepal width`, `petal length`, and `petal width`.  
The objective is to group similar flowers into clusters without using target labels.

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized data with **pairplots**, **histograms**, and **correlation heatmap**  
- Checked feature distributions and relationships  
- Applied **StandardScaler** to normalize feature ranges

---

## 🤖 Clustering Method

- **Algorithm:** K-Means  
- **Cluster Evaluation:**  
  - **Elbow Method** to determine optimal K using inertia  
  - **Silhouette Score** to validate cluster quality  

- **Number of clusters:** 3 (matches Iris species naturally)

---

## 🏆 Deployment

A **Streamlit web app** allows users to input sepal and petal measurements and predict the corresponding cluster:

```bash
streamlit run app.py
