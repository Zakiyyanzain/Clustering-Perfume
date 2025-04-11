# Clustering-Perfume
📌 Project Overview

This project aims to analyze **customer behavior in purchasing perfumes** by implementing clustering techniques. Using data scraped from **eBay**, the project groups customers based on **price preferences**, **types of perfumes purchased**, and **availability**, enabling deeper understanding of purchasing patterns and aiding in **strategic pricing decisions**.

## 🧠 Introduction

Understanding customer preferences is crucial in competitive markets like fragrances. This project applies unsupervised and supervised learning techniques to:

- Identify key **customer segments** based on buying behavior.
- Evaluate how price and availability impact **sales volume**.
- Provide insights for **targeted pricing** and marketing strategies.

## 🔧 Methodology

The project follows the standard machine learning workflow:

1. **Data Preprocessing**
   - Handling missing values, duplicates, and outliers
   - Normalization/scaling of numerical features

2. **Exploratory Data Analysis (EDA)**
   - Analyzing price distribution, availability, perfume types
   - Correlation analysis and visual insights

3. **Modeling**
   - **Clustering** using DBSCAN (Density-Based Spatial Clustering)
   - **PCA** for dimensionality reduction
   - **Regression** analysis to assess impact on sales

4. **Evaluation**
   - Silhouette Score for cluster validation
   - RMSE and R² for regression performance

## 📊 Result & Analysis

The clustering process revealed:

- **Two primary customer segments**:
  - **Cluster 1**: Price-sensitive consumers
  - **Cluster 2**: Premium buyers influenced by exclusive offerings or regional factors

- **Regression Findings**:
  - Price shows a **negative correlation** with sales volume
  - Product **availability** shows a **positive correlation** with sales

These insights highlight the need for **pricing strategies** that accommodate:
- **Budget-conscious consumers**
- **Niche premium markets**
