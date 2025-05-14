# ML-Clustering

## 🧠 Unsupervised Learning — Customer Segmentation with Clustering  
**Date:** April 24, 2024  
**Author:** Clement Airohuodion  

---

## 🔍 Project Overview

This project demonstrates how clustering — a powerful unsupervised learning technique — can be used to identify customer segments in the competitive world of **online retail**, specifically in the **footwear industry**. The goal is to support **data-driven decisions** in marketing, credit strategy, and customer retention.

Using a combination of **K-Means** and **Hierarchical Clustering**, this analysis reveals meaningful insights into customer behaviors, spending patterns, and demographic trends.

---

## 📊 Dataset

- **Source**: [Kaggle - Online Shop Dataset](https://www.kaggle.com/datasets/mohamadmahdijadidi/online-shop-data-for-clustering)
- **Size**: 8,950 entries × 18 features  
- **Fields**: `Balance`, `Purchases`, `Credit Limit`, `Payments`, `Tenure`, and more  
- **Privacy**: Fully anonymized and GDPR-compliant

---

## 🧹 Preprocessing

1. **Missing Values**: Handled using mean imputation
2. **Outliers**: Removed using IQR method
3. **Standardization**: Applied `StandardScaler` for uniform scale
4. **Data Visualizations**:
   - Pairplots & histograms to explore feature distribution
   - Interactive scatter plots & heatmaps using `plotly`
   - Boxplots & KDEs to understand payment and balance behaviors

---

## 🧠 Algorithms Applied

### ✅ K-Means Clustering
- **Elbow method** used to identify optimal clusters (K = 3)
- **PCA** reduced data to 2D for visualization
- Key Clusters:
  - High-spending customers
  - Discount seekers
  - Cash-advance-dependent segments

### ✅ Hierarchical Clustering
- **Ward's method** used
- **Dendrogram** helped visualize group formation
- Showed evolving behavioral clusters and niche segments

---

## 📈 Results & Insights

- **Silhouette Score**: `0.37` (Moderate clustering quality)
- **Customer Segments**:
  - Identified 3 major clusters with distinct spending and payment patterns
  - Cross-cluster comparison revealed actionable strategies for:
    - Loyalty rewards
    - Risk mitigation (credit stress)
    - Personalized promotions

---

## 📌 Conclusion

Clustering enabled strategic segmentation of customers, unlocking critical insights to:
- Enhance **customer experience**
- Improve **credit risk management**
- Enable **targeted marketing**

By integrating both **K-Means** and **Hierarchical Clustering**, this project provides a comprehensive view of customer behavior in online retail, aligning with real business challenges.

---

## 📁 [Click to See Supporting Code & Notebooks](https://github.com/Clemobrain/Clem_Portfolio/blob/main/Clustering%20Project)

📧 **Contact**: C.O.Airohuodion@edu.salford.ac.uk  
🔗 **LinkedIn**: [linkedin.com/in/yourprofile](https://www.linkedin.com/in/yourprofile)  
🔗 **GitHub**: [github.com/Clemobrain](https://github.com/Clemobrain)

---
