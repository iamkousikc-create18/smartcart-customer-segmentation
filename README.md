# 🛒 SmartCart Customer Segmentation System

## 📌 Project Overview
This project develops an intelligent customer segmentation system for SmartCart using Unsupervised Machine Learning techniques.

The objective is to group customers into meaningful clusters based on purchasing behavior, engagement patterns, and demographic information to enable data-driven marketing strategies.

---

## 📊 Dataset Details
- Total Records: 2240+
- Total Features: 22
- Data Includes:
  - Customer Demographics
  - Purchase Behavior (Amount & Frequency)
  - Website Activity
  - Customer Feedback

---

## 🧠 Machine Learning Approach

### 1️⃣ Data Preprocessing
- Handling missing values
- Feature engineering (Age, Total Spending, Customer Tenure, etc.)
- Encoding categorical variables
- Feature scaling using StandardScaler

### 2️⃣ Dimensionality Reduction
- PCA (Principal Component Analysis)
- Reduced high-dimensional feature space to improve clustering efficiency

### 3️⃣ Clustering Algorithm
- KMeans Clustering
- Optimal cluster selection using:
  - Elbow Method
  - Silhouette Score

---

## 🔄 Model Pipeline

Raw Data  
→ Data Cleaning  
→ Feature Engineering  
→ Scaling  
→ PCA  
→ KMeans Clustering  
→ Cluster Profiling  

---

## 📈 Business Insights

The clustering model helps to:

- Identify High-Value (Premium) Customers
- Detect Low Engagement Users
- Recognize Potential Churn Customers
- Improve Marketing Targeting
- Support Personalized Campaign Strategies

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📌 Results

Customers were segmented into distinct groups based on behavioral and demographic patterns.  
These insights can significantly improve SmartCart's marketing efficiency and customer retention strategy.

---

## 🚀 Future Improvements

- Deploy model using Streamlit
- Real-time prediction system
- Advanced clustering comparison (Hierarchical vs KMeans)
- Integration with CRM systems

---

## 👨‍💻 Author
Kousik Chakraborty 
