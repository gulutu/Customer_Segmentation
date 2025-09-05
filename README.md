# Customer Segmentation with Clustering

This project applies clustering techniques to a retail dataset in order to identify distinct customer segments.  
The goal is to demonstrate how data science can be used to support targeted marketing strategies and improve customer understanding.

---

## 📊 Project Overview
- **Dataset**: Retail customer dataset with demographic, spending, and campaign response variables.  
- **Techniques**:  
  - Exploratory Data Analysis (EDA) for understanding demographics, purchasing behavior, and customer engagement.  
  - Data cleaning and feature engineering (handling outliers, creating aggregated features).  
  - **K-Means clustering** for segmentation.  
  - Cluster profiling with descriptive statistics and visualization.  

---

## 🔑 Key Insights
- Customers can be grouped into **three distinct clusters**:  
  1. **Affluent Heavy Spenders** – High income, very high spending, highly responsive to campaigns.  
  2. **Budget-Conscious Families** – Low income, more children, very low spending, little to no response to campaigns.  
  3. **Established Middle Spenders** – Medium income, moderate spending, stable customer base with some campaign responsiveness.  

- These insights can guide **marketing strategy**:  
  - Premium offers for high-value customers (Cluster 0).  
  - Low-cost maintenance for low-value families (Cluster 1).  
  - Selective campaigns for stable mid-value customers (Cluster 2).  

---

## 📂 Repository Structure
- `Retail_Customer_Segmentation.ipynb` → Jupyter Notebook with full analysis and clustering.  
- `customer_segmentation.csv` → Dataset used in the project, retrieved from Kaggle (https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering/data).  
- `README.md` → Project overview (this file).  

---

## ⚙️ Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- Jupyter Notebook for analysis and visualization  

---

## 🚀 Next Steps / Future Work
- Experiment with alternative clustering methods (e.g., Hierarchical, DBSCAN).  
- Explore dimensionality reduction techniques beyond PCA.  
- Build predictive models to estimate cluster membership for new customers.
