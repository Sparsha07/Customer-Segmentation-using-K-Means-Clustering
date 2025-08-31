# Customer-Segmentation-using-K-Means-Clustering

## 📌 Overview

This project applies **K-Means Clustering** to segment mall customers into distinct groups based on their **Annual Income** and **Spending Score**.
Such segmentation helps businesses:

* Identify high-value customers
* Personalize marketing strategies
* Improve customer retention
* Optimize product recommendations

## 📂 Dataset

The dataset used is **Mall\_Customers.csv**, which contains information about 200 customers.

**Features:**

* `CustomerID` → Unique ID for each customer
* `Gender` → Male / Female
* `Age` → Customer age (18–70 years)
* `Annual Income (k$)` → Customer’s income (15k–137k)
* `Spending Score (1–100)` → Score assigned by the mall based on spending habits

## 🧠 Methodology

1. **Data Exploration & Cleaning**

   * Check for missing values
   * Summarize dataset statistics
   * Visualize distributions (Age, Income, Spending Score)

2. **Feature Selection**

   * Selected key features: `Annual Income (k$)` and `Spending Score (1–100)`

3. **Elbow Method**

   * Determine optimal number of clusters `k`

4. **K-Means Clustering**

   * Apply algorithm using `scikit-learn`
   * Assign cluster labels to customers

5. **Visualization**

   * 2D scatter plots (Income vs Spending Score)
   * 3D plots with Age, Income, Spending Score
    

 The notebook will:

   * Display EDA & plots
   * Show optimal number of clusters using Elbow Method
   * Visualize clusters in 2D & 3D

## 📊 Visualizations

* **Elbow Curve** to determine best `k`
* **Clustered Scatter Plot**: Annual Income vs Spending Score
* **3D Cluster Visualization** with Age included


## 📈 Results

* Customers are segmented into **distinct groups** such as:

  * High Income – High Spending
  * High Income – Low Spending
  * Low Income – High Spending
  * Low Income – Low Spending
  * Average/Moderate group


