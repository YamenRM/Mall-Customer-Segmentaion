# 🛍️ Mall Customer Segmentation using KMeans Clustering

This project applies unsupervised machine learning techniques to segment customers of a mall based on their demographic and behavioral attributes. The goal is to help the mall understand different customer groups and optimize marketing strategies accordingly.

---

## 📊 Project Overview

- **Type**: Unsupervised Machine Learning
- **Algorithm Used**: KMeans Clustering
- **Tools**: Python, scikit-learn, pandas, matplotlib, seaborn
- **Dataset**: [Mall Customer Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 💡 Objectives

- Identify distinct customer segments based on:
  - Age
  - Annual Income
  - Spending Score
  - Gender (encoded)
- Apply PCA for dimensionality reduction and visualization
- Visualize and interpret the resulting customer clusters

---

## 🧠 Features Used

| Feature | Description |
|--------|-------------|
| `Gender` | Encoded numerically (0 or 1) |
| `Age` | Customer age |
| `Annual Income (k$)` | Income in thousands of USD |
| `Spending Score (1-100)` | Score assigned by the mall based on spending behavior |

---

## 🛠️ Technologies Used

- **Python** (v3.8+)
- **Pandas**: Data manipulation
- **Scikit-learn**: KMeans, PCA, scaling
- **Matplotlib / Seaborn**: Visualization

---


## 🔍 How It Works

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical columns (e.g. gender)
   - Standardize features

2. **Choosing Optimal Clusters**
   - Elbow Method
   - Silhouette Score

3. **KMeans Clustering**
   - Fit `KMeans(n_clusters=k)`
   - Assign each customer to a cluster

4. **Dimensionality Reduction**
   - Apply PCA to reduce features to 2D
   - Use for visualization only

5. **Labeling Clusters**
   - Assign segment names based on behavioral interpretation

---
## ▶️ How to Run This Project

### 📦 1. Clone the Repository

```bash
git clone https://github.com/YamenRM/Mall-Customer-Segmentaion.git
cd Mall-Customer-Segmentaion
```
## 📥 3. Install Dependencies
  - pip install -r requirements.txt

---

## 📊 Visualizations

- Elbow plot for choosing K
- PCA scatter plot with clusters
- Income vs Spending Score by cluster

---

## 💾 Output
The final CSV includes the following columns:

 - Age

 - Annual Income (k$)

 - Spending Score (1-100)

 - Cluster

 - Segment

 - PCA1 / PCA2 (for plotting)

 - Saved as: clustered_customers.csv

## 🔮 Future Improvements
 - Try alternative clustering methods: DBSCAN, GMM, Hierarchical

 - Include more features (e.g. visit frequency, customer loyalty)

 - Deploy app on Streamlit Cloud or HuggingFace Spaces

 - Build classifier to predict segment for new customers

## 🧑‍💻 Author
 - YamenRM
 - AI Engineering Student | UP
 - 📫 yamenrafat132@gmail.com
 - 🌍 Gaza, Palestine
 - 💪 Stay strong
