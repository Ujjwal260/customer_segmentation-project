# 🧠 Customer Segmentation for SBI Life Insurance

## 📌 Objective
This project aims to perform **customer segmentation** for SBI Life Insurance based on behavioral credit card data. The goal is to identify distinct customer groups that can be targeted with tailored offerings such as savings plans, loans, and wealth management solutions.

## 🧰 Tools & Techniques Used
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- PCA (Principal Component Analysis)
- Clustering Algorithms: K-Means, Hierarchical Clustering, DBSCAN, Spectral Clustering, Gaussian Mixture

## 🧪 Data Description
- Dataset: Contains 18 behavioral features for ~9,000 active credit card users over the past 6 months.
- Features include: Balance, Purchase Frequency, Credit Limit, Payments, and Cash Advances.

## 🔍 Key Analysis Performed
- Data cleaning and preprocessing, including handling missing values and feature scaling.
- Applied **PCA** to reduce dimensionality and improve clustering performance.
- Performed **unsupervised clustering** using multiple algorithms:
  - K-Means Clustering
  - Hierarchical Clustering
  - DBSCAN
  - Spectral Clustering
  - Gaussian Mixture Models
- Evaluated cluster quality using **silhouette scores** and visualizations.

## 💡 Business Outcomes
- Identified **distinct customer segments** based on behavior and usage patterns.
- Found clusters suitable for targeted campaigns (e.g., high spenders, low engagement users, potential up-sell customers).
- The segmentation results can support **personalized marketing strategies** and **product recommendation systems**.
