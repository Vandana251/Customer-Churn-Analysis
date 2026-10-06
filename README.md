# 📊 Customer Segmentation & Churn Analysis

An end-to-end Machine Learning project demonstrating data preprocessing, exploratory data analysis (EDA), and unsupervised clustering techniques to segment customers and analyze churn behavior for targeted marketing strategies.

---

## 📌 Project Overview
Understanding customer behavior and spending patterns is crucial for business growth and customer retention. This project explores customer demographics, transaction history, and engagement metrics to discover distinct behavioral customer segments using unsupervised machine learning algorithms.

---

## 🚀 Key Features & Workflow

1. **Data Cleaning & Quality Checks**:
   - Handling missing values, negative records, and data inconsistencies.
   - Outlier detection using Interquartile Range (IQR).

2. **Exploratory Data Analysis (EDA)**:
   - Demographic distribution analysis (Age, Income, Education, Marital Status).
   - Spending behavior across categories (Wine, Meat, Fish, Gold, Sweets, etc.).
   - Correlation analysis and feature interactions.

3. **Feature Preprocessing & Engineering**:
   - One-Hot Encoding for categorical features.
   - Feature Scaling with `StandardScaler`.
   - Dimensionality reduction and 2D visualization using **Principal Component Analysis (PCA)**.

4. **Unsupervised Clustering Algorithms**:
   - **K-Means Clustering**: Optimal $K$ selection via Elbow Method & Silhouette Score.
   - **Hierarchical / Agglomerative Clustering**: Dendrogram analysis and linkage methods.
   - **DBSCAN (Density-Based Spatial Clustering)**: Parameter tuning (`eps`, `min_samples`) with k-distance graphs.

5. **Model Evaluation & Comparison**:
   - Evaluated using **Silhouette Score**, **Calinski-Harabasz Index**, and **Davies-Bouldin Index**.

6. **Customer Persona Profiling**:
   - Identified and labeled actionable customer segments (e.g., High Spenders, Budget Conscious, Promising/Engaged Customers) with targeted business recommendations.

---

## 📁 Repository Structure

```text
├── Customer_Segmentation_Unsupervised.ipynb   # Main Jupyter Notebook with full analysis & models
├── Supervised_Learning_Messy_Customer_Churn.csv # Customer churn dataset
├── LICENSE                                    # MIT License
├── .gitignore                                 # Git ignore file for clean repo
└── README.md                                  # Project documentation
```

---

## 🛠️ Tech Stack & Libraries
- **Language**: Python 3.x
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn` (`KMeans`, `AgglomerativeClustering`, `DBSCAN`, `PCA`, `StandardScaler`)
- **Statistical Analysis**: `scipy`

---

## ⚙️ How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vandana251/Customer-Churn-Analysis.git
   cd Customer-Churn-Analysis
   ```

2. **Install required dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn scipy
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook Customer_Segmentation_Unsupervised.ipynb
   ```

---

## 👤 Author
- **GitHub**: [@Vandana251](https://github.com/Vandana251)
