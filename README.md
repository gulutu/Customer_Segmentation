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
<img width="690" height="552" alt="clusters" src="https://github.com/user-attachments/assets/31ca3240-1c7e-402b-9223-5f0077929470" />
<img width="689" height="398" alt="age_per_cluster" src="https://github.com/user-attachments/assets/0e4b46af-6ea6-487f-b7e5-c74d19eb9e60" />
<img width="715" height="398" alt="income_per_cluster" src="https://github.com/user-attachments/assets/85f37e52-0530-4914-a67c-82f4a841d3ff" />
<img width="706" height="398" alt="total_spending_per_cluster" src="https://github.com/user-attachments/assets/d7d76119-b801-496c-8d3a-4149e6b995c5" />
<img width="694" height="398" alt="children_per_cluster" src="https://github.com/user-attachments/assets/f77de780-113e-4b47-8607-2035b305ed41" />
<img width="689" height="398" alt="recency_per_cluster" src="https://github.com/user-attachments/assets/dfb044b4-035c-48bb-b72d-f91f4ec7df4b" />
<img width="578" height="520" alt="campaign_response_rate" src="https://github.com/user-attachments/assets/558e3750-4dac-4023-92a0-9eab1c37bddc" />

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
