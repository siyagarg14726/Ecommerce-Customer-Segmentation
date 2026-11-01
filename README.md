# 🛍️ E-Commerce Customer Segmentation Using Machine Learning

## 📌 Project Overview

This project focuses on analysing e-commerce customer purchasing behaviour and identifying meaningful customer segments using unsupervised machine learning techniques.

It uses **RFM (Recency, Frequency, Monetary) Analysis** along with K-Means and DBSCAN clustering algorithms to group customers based on their transaction history.

The project also uses PCA and t-SNE for dimensionality reduction and visualisation, helping understand customer patterns and cluster distributions.

## 🎯 Objectives

- Analyse customer purchasing behaviour and transaction patterns.
- Identify valuable, loyal, potential and at-risk customers.
- Perform customer segmentation using unsupervised learning.
- Compare K-Means and DBSCAN clustering algorithms.
- Visualise customer segments using PCA and t-SNE.
- Generate actionable insights for targeted marketing strategies.

## 📂 Dataset

**Dataset:** UCI Online Retail Dataset

The dataset contains transactional records of a UK-based online retail store.

**Important features:**
- InvoiceNo – Transaction identification number.
- StockCode – Product identification code.
- Description – Product description.
- Quantity – Number of products purchased.
- InvoiceDate – Date and time of transaction.
- UnitPrice – Price per unit.
- CustomerID – Unique customer identifier.
- Country – Customer's country.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Machine learning |
| Google Colab | Development environment |

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Load the Online Retail dataset.
- Inspect dataset structure and data types.
- Analyse statistical summaries and missing values.

### 2. Data Cleaning and Preprocessing
- Handle missing CustomerID values.
- Remove duplicate records.
- Convert InvoiceDate into datetime format.
- Remove cancelled transactions.
- Remove invalid quantities and prices.
- Calculate total transaction amount.

### 3. Exploratory Data Analysis (EDA)
- Analyse transaction distributions.
- Identify top-performing countries.
- Examine purchase amounts and quantities.
- Visualise patterns and outliers.

### 4. RFM Feature Engineering

Calculate three important customer behaviour metrics:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer made purchases.
- **Monetary:** How much a customer spent.

Apply log transformation and feature scaling to prepare the data for clustering.

### 5. K-Means Clustering
- Determine the optimal number of clusters using the Elbow Method.
- Analyse Silhouette Scores.
- Apply K-Means clustering.
- Visualise customer segments.

### 6. DBSCAN Clustering
- Analyse neighbourhood distances using a K-distance graph.
- Experiment with different `eps` and `min_samples` values.
- Identify dense customer groups and noise points.

### 7. Dimensionality Reduction
- Apply PCA for two-dimensional visualisation.
- Apply t-SNE to explore local cluster structures.
- Visualise customer segments using scatter plots.

### 8. Model Evaluation
Compare clustering performance using:

- Silhouette Score

### 9. Customer Persona Generation
Interpret customer clusters using RFM characteristics and identify customer groups such as:

- Champions
- Loyal Customers
- Potential Customers
- At-Risk Customers
- Hibernating Customers

## 📊 Expected Outcomes

- Identification of distinct customer segments.
- Better understanding of customer purchasing behaviour.
- Comparison of two clustering approaches.
- Visual representation of customer groups.
- Data-driven marketing and customer retention recommendations.

## 💡 Business Applications

The insights generated can help e-commerce businesses:

- Design personalised marketing campaigns.
- Improve customer retention.
- Reward high-value customers.
- Re-engage inactive customers.
- Identify opportunities for increasing customer lifetime value.

Machine Learning | Python | Data Science | Unsupervised Learning

---

⭐ If you find this project useful, consider giving it a star!
