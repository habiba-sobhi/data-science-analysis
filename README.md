# E-Commerce Transactions Data Analysis

## 📌 Description
A data science project analyzing customer purchasing behavior using an e-commerce transactions dataset. The project applies data cleaning, visualization, and machine learning techniques to extract meaningful insights and identify customer segments.

## 🎯 Objectives
- Analyze customer spending patterns
- Identify popular product categories
- Explore payment method preferences
- Segment customers based on purchasing behavior

## 📊 Dataset
- Source: Kaggle (E-Commerce Transactions Dataset)
- Size: 50,000 records
- Features: Customer info, product category, purchase amount, payment method, transaction date
- Type: Synthetic but realistic transactional dataset

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Data Processing
- Data cleaning (missing values, duplicates)
- Outlier detection and removal (IQR method)
- Data type conversion (datetime)
- Feature selection and scaling

## 📈 Data Visualization
- Product category distribution (bar chart)
- Purchase amount distribution (histogram)
- Payment method usage (pie chart)
- Outlier detection using boxplots

## 🤖 Machine Learning
- **K-Means Clustering**
  - Segmented customers into 3 groups
  - Based on purchase amount and age
  - Applied data standardization before clustering

## 💡 Key Insights
- Certain product categories dominate transaction volume
- Customer spending follows a specific distribution with few high-value outliers
- Payment method preferences are clearly identifiable
- Customer segmentation enables targeted marketing strategies

## ▶️ How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
