# Customer Segmentation in E-commerce 🛍️
Using KMeans Clustering on the UCI Online Retail Dataset

## 📌 Project Overview
This project performs customer segmentation based on purchasing behavior using **unsupervised machine learning**. We use the **UCI Online Retail Dataset**, which contains transactional data of a UK-based online retailer between 2010 and 2011.

The goal is to group customers into meaningful clusters to better understand shopping patterns and help businesses make data-driven marketing decisions.

---

## 🧠 Key Concepts
- **Customer Segmentation**
- **RFM Analysis (Recency, Frequency, Monetary)**
- **Data Preprocessing & Cleaning**
- **StandardScaler (Normalization)**
- **KMeans Clustering**
- **Elbow Method** for optimal `k`
- **Silhouette Score** for cluster quality
- **Cluster Visualization (Pairplots, Boxplots)**

---

## 📂 Dataset Info
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Size**: ~540,000 transactions
- **Features**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🚀 How to Run
1. Upload the dataset file: `9. Customer Segmentation in E-commerce.csv`
2. Run the Python script (`.ipynb` or `.py`)
3. The code:
   - Cleans data
   - Extracts RFM values
   - Applies scaling
   - Runs KMeans
   - Shows Elbow graph and Silhouette scores
   - Displays cluster insights and visualizations

---

## 📊 Output
- Optimal number of clusters (`k`)
- Cluster-wise breakdown of customer behavior
- Visualizations (Pairplots, Elbow Curve, Silhouette Scores)
- Cluster centroids

---

## ✅ Requirements
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
