# Customer Segmentation Model Using K-Means Clustering

🚀 **Project Overview**  
This project focuses on segmenting customers into distinct groups based on their behaviors and attributes. By leveraging clustering techniques, the model provides actionable insights for targeted marketing and enhanced customer experiences.

---

## 🎯 **Project Objective**
To perform customer segmentation using K-Means clustering and generate meaningful insights to support data-driven decision-making in areas like marketing, product development, and customer retention.

---

## 🛠️ **Process & Methodology**

1. **Data Cleaning & Exploration**  
   - Dropped irrelevant columns (`ID`, `Dt_Customer`, `Z_CostContact`, `Z_Revenue`) and rows with missing `Income` data.  
   - Converted categorical variables (`Education`, `Marital_Status`) into numeric format using one-hot encoding.

2. **Feature Scaling**  
   - Standardized the dataset using `StandardScaler` to ensure uniform contribution of all features to the clustering process.

3. **Dimensionality Reduction**  
   - Applied **Principal Component Analysis (PCA)** to reduce the feature dimensions to two components, enabling efficient computation and visualization.

4. **K-Means Clustering**  
   - Determined the optimal number of clusters using the **Elbow Method** and **Sum of Squared Errors (SSE)**.  
   - Segmented customers into **4 distinct clusters** using K-Means.

5. **Evaluation**  
   - Measured cluster quality with the **Silhouette Score** to ensure well-defined and meaningful segments.

6. **Visualization**  
   - Plotted the clusters in a 2D space (PCA-reduced) and added descriptive legends to explain the characteristics of each segment.

---

## 📈 **Key Takeaways**
- Hands-on experience in preprocessing and transforming raw data for clustering tasks.  
- Practical application of PCA for dimensionality reduction and the Elbow Method for cluster optimization.  
- A deep understanding of customer segmentation and its importance in driving data-informed strategies.

---

## 📊 **Technologies Used**
- **Python Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
- **Clustering Algorithms**: K-Means  
- **Dimensionality Reduction**: Principal Component Analysis (PCA)

---
