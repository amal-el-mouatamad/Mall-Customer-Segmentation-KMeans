# 🛍️ Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies the K-Means clustering algorithm to segment mall customers based on their annual income and spending score. The objective is to identify customer groups that can help businesses improve their marketing strategies and better understand customer behavior.

---

## 🎯 Objectives

- Explore the dataset
- Clean and preprocess the data
- Encode categorical features
- Analyze feature correlations
- Detect outliers
- Apply StandardScaler
- Determine the optimal number of clusters using the Elbow Method
- Train the K-Means clustering model
- Visualize customer segments

---

## 📊 Dataset Information

- Dataset: Mall Customer Segmentation Dataset
- Number of samples: 200
- Number of features: 4
- Features:
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Missing Value Check
4. Duplicate Check
5. Remove Customer ID
6. Encode Gender
7. Correlation Matrix
8. Boxplot Visualization
9. Feature Scaling using StandardScaler
10. Elbow Method
11. K-Means Clustering
12. Cluster Prediction
13. Customer Segmentation Visualization

---

## 📈 Model Performance

- Optimal Number of Clusters (K): **5**
- Clustering Algorithm: **K-Means**

---

## 📉 Visualizations

### Correlation Matrix
<img width="752" height="702" alt="image" src="https://github.com/user-attachments/assets/125a107d-7a63-4bd3-b469-348aa0c6233c" />

### Boxplot
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/609763cb-c764-434c-83d8-d4a0f0c53fc3" />

### Elbow Method
<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/416f674b-b601-4338-aaa0-436ab1633dec" />

### Customer Segmentation
<img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/c5d85e24-5073-41fa-8885-0fc029efeb67" />

### Cluster Centers

<img width="695" height="547" alt="image" src="https://github.com/user-attachments/assets/940d4d7d-c706-44e2-a981-70e4ddcfa88c" />

---

## 📁 Project Structure

```
Mall-Customer-Segmentation-KMeans/
│
├── mall_customer_segmentation_kmeans.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
└── images/
    ├── correlation_matrix.png
    ├── boxplot.png
    ├── elbow_method.png
    ├── customer_segmentation.png
    └── cluster_centers.png
```

---

## 🚀 Future Improvements

- Compare K-Means with Hierarchical Clustering
- Apply PCA for cluster visualization
- Test different numbers of clusters
- Build an interactive dashboard

---

## 👩‍💻 Author

**Amal El Mouatamad**

AI & Data Analytics Student

ISTA NTIC Rabat
