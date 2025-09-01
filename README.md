# Customer-Segmentation-KMeans

Customer segmentation using K-Means clustering on the Mall Customers dataset.

---

## Description

This project analyzes customer data from the Kaggle dataset ["Mall Customers"](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) to identify distinct customer segments using the K-Means clustering algorithm. 

The analysis starts with two features (**Annual Income** and **Spending Score**) and then extends to three features by including **Age**. Visualizations include 2D scatter plots, 3D plots, and cluster profile charts to interpret customer behavior. 

---

## Dataset

- The dataset contains 200 customer records.
- Columns:
  - `CustomerID`: Unique customer identifier
  - `Gender`: Customer gender
  - `Age`: Customer age
  - `Annual Income (k$)`: Annual income in thousand dollars
  - `Spending Score (1-100)`: A score representing customer spending behavior

---

## Features Used

- **2D Clustering:** Annual Income and Spending Score
- **3D Clustering:** Age, Annual Income, Spending Score

---

## Methodology

1. **Data Preprocessing**
   - Check for missing values and duplicates
   - Select relevant features

2. **Exploratory Data Analysis**
   - 2D scatter plots of features
   - 3D visualization for three features

3. **Finding Optimal Clusters**
   - Elbow method (Inertia)
   - Silhouette score

4. **K-Means Clustering**
   - Apply K-Means on 2D and 3D feature sets
   - Visualize clusters with distinct colors
   - Calculate cluster centers

5. **Cluster Analysis**
   - Compute mean values for each cluster
   - Interpret customer segments

---

## Results

- **Optimal number of clusters (2D):** 5
- **Optimal number of clusters (3D):** 6 or 7

**Cluster Profiles (3D):**
- Cluster 0: Older, medium income, medium spending
- Cluster 1: Young adults, high income, high spending (premium buyers)
- Cluster 2: Young, low income, high spending (budget-active shoppers)
- Cluster 3: Middle-aged, high income, very low spending (frugal segment)
- Cluster 4: Young, above-average income, very high spending (key target segment)
- Cluster 5: Middle-aged, low income, low spending (price-sensitive)
- Cluster 6: Young adults, medium income, medium spending (average buyers)

---

## Visualizations

- 2D scatter plots of Annual Income vs Spending Score
- Elbow method and Silhouette score plots
- 3D scatter plots with cluster colors
- Bar charts showing average cluster profiles

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/apostolosmav/Customer-Segmentation-KMeans.git

