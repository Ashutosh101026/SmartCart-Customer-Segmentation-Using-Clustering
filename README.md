# SmartCart Customer Segmentation Using Clustering

## 📌 Project Overview

SmartCart Customer Segmentation is an Unsupervised Machine Learning project that analyzes customer behaviour and groups customers into meaningful segments based on demographics, income, and purchasing patterns.

The objective of this project is to help businesses understand different customer categories and improve marketing strategies using data-driven insights.

---

# 🎯 Problem Statement

Companies collect large amounts of customer data but often lack insights about customer groups.

This project uses clustering techniques to automatically identify customer segments based on:

- Spending behaviour
- Income level
- Customer demographics
- Purchase patterns


---

# 📂 Dataset Information

Dataset: SmartCart Customer Dataset

Total Records: 2240 customers

Total Features: 22


The dataset contains information about:

- Customer demographics
- Income
- Product spending
- Purchase frequency
- Customer engagement


---

# 🛠️ Technologies Used

Programming Language:

- Python


Libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


Machine Learning Techniques:

- Data Preprocessing
- Feature Engineering
- One Hot Encoding
- Feature Scaling
- PCA
- Clustering Algorithms


---

# 🔄 Project Workflow


## 1. Data Loading

Loaded customer dataset using Pandas and performed initial analysis.


## 2. Data Cleaning

Performed:

- Missing value analysis
- Missing value treatment
- Removed unnecessary features


## 3. Feature Engineering

Created new meaningful features:

- Customer Age
- Total Spending
- Total Children


These features helped in better understanding customer behaviour.


## 4. Exploratory Data Analysis

Performed:

- Statistical analysis
- Feature distribution analysis
- Correlation analysis
- Heatmap visualization


## 5. Data Preprocessing

Applied:

### One Hot Encoding

Converted categorical features into numerical format.


### Standard Scaling

Normalized numerical features for clustering.


## 6. Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce feature dimensions and visualize customer groups.


## 7. Finding Optimal Number of Clusters

Used:

- Elbow Method
- Silhouette Score


to determine suitable cluster count.


# 🤖 Machine Learning Models


## K-Means Clustering

Used K-Means algorithm to divide customers into different groups based on similarity.


## Agglomerative Hierarchical Clustering

Applied hierarchical clustering to compare customer grouping performance.


---

# 📊 Results

The model successfully segmented customers into different groups based on:

- Purchasing behaviour
- Income patterns
- Customer engagement


These clusters provide valuable insights for targeted marketing and customer relationship management.


---

# 📈 Visualizations

Project includes:

- Correlation Heatmap
- Elbow Method Graph
- PCA Cluster Visualization
- Cluster Analysis


---

# 💡 Business Applications

This customer segmentation system can help businesses in:

- Personalized marketing campaigns
- Customer retention strategies
- Premium customer identification
- Product recommendation strategies
- Better decision making


---
 # 📁 Project Structure

SmartCart-Customer-Segmentation-Using-Clustering

├── SmartCart_Clustering_System.ipynb
│   └── Complete machine learning workflow including data preprocessing, EDA, PCA, and clustering models

├── smartcart_customers.csv
│   └── Customer dataset used for analysis and segmentation

├── README.md
│   └── Project documentation and explanation

└── requirements.txt
└── Required Python libraries for running the project



---

# ⚙️ Installation


Clone repository:


Install required libraries:


---

# 📌 Future Improvements

- Add customer profiling dashboard
- Deploy using Streamlit
- Apply DBSCAN clustering
- Add automated cluster recommendations


---

# 👨‍💻 Author

Machine Learning Project

**SmartCart Customer Segmentation Using Clustering**
