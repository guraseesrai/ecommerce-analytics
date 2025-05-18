# 🛒 E-Commerce Customer Segmentation Capstone

This project performs end-to-end customer segmentation using transactional data from a UK-based online retailer. It includes robust **data preprocessing**, **feature engineering**, **clustering**, **classification**, and a **recommendation system**, showcasing real-world data engineering and applied ML practices.

---

## 📦 Project Overview

**Goal**: Segment customers based on purchasing behavior to enable targeted marketing and product recommendations.

**Key Tasks**:
- Clean and transform raw transactional data
- Engineer customer-centric features (RFM)
- Cluster customers using K-Means and Hierarchical Clustering
- Classify customers using supervised ML
- Recommend products within each customer segment

---

## 🧰 Tools & Technologies

- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (KMeans, RandomForest, PCA, cross-validation)
- **Unsupervised Learning**: K-Means, Hierarchical Clustering
- **Supervised Learning**: Random Forest Classifier
- **Feature Engineering**: Recency, Frequency, Monetary Value (RFM)
- **Recommendation System**: Cluster-based top-N product suggestions

---

## 🗃️ Dataset

- Source: UCI Machine Learning Repository  
- Contains ~540,000 transaction records from 2010–2011
- Features include InvoiceNo, StockCode, Quantity, UnitPrice, InvoiceDate, CustomerID, and Country

---

## 🧪 Project Pipeline

### 1. 🧹 Data Cleaning & Preprocessing
- Removed missing values and duplicates
- Filtered invalid quantities/prices
- Converted and formatted date/customer fields

### 2. 🧠 Feature Engineering & EDA
- Created RFM features for each customer
- Explored 1D & 2D visualizations (histograms, scatterplots)

### 3. 🔢 Customer Clustering
- Used KMeans and Hierarchical Clustering
- Determined optimal `k` using Elbow Method & Silhouette Score
- Reduced dimensions using PCA and visualized clusters

### 4. 📊 Segment Classification
- Trained Random Forest to classify customers into clusters
- Evaluated with accuracy, precision, recall, F1-score
- Achieved >99% accuracy with cross-validation

### 5. 🎯 Recommendation System
- Suggested top-selling products per segment
- Recommended items not yet purchased by customers in the same cluster

---

## 📈 Results Summary

- Identified 4 distinct customer segments based on RFM behavior
- Achieved 99.4% classification accuracy (Random Forest)
- Built a simple, cluster-aware recommendation engine

---

## 💼 Why It Matters for Data Engineering

This project demonstrates:
- End-to-end **data transformation and pipeline design**
- Use of **machine learning in production-style logic**
- Skills in **feature engineering, clustering, and automation**
- Integration of modeling with real-world business use cases

---


