# 📊 Social Media User Behavior Analysis

This project analyzes social media usage patterns, emotional expression, and engagement using machine learning and data visualization.

---

## 🔧 Tech Stack

* **Python**: Pandas, NumPy, Scikit-learn, Statsmodels  
* **Visualization**: Seaborn, Matplotlib  
* **ML Models**: Linear & Logistic Regression, K-Means  
* **Notebook**: Jupyter

---

## 📁 Dataset Summary

* Cleaned data: `cleaned_train.csv`, `cleaned_val.csv`, `cleaned_test.csv`  
* Key features: `Age`, `Gender`, `Platform`, `Dominant_Emotion`, `Posts_Per_Day`, `Likes_Received_Per_Day`

---

## 🔍 Workflow Overview

### 1. Data Preprocessing

* Removed invalid `Gender` entries (e.g., '27', 'Marie')  
* Imputed missing `Age` with median  
* Encoded categorical features  
* Standardized features for clustering

### 2. EDA Highlights

* **Instagram**: Most engaging platform  
* **Females**: Higher activity and emotional expression  
* **Posts ↔ Likes**: Strong positive correlation

### 3. Modeling

* **Linear Regression**: Predicted likes (R² ≈ 0.93)  
* **Logistic Regression**: Classified emotion (90% accuracy)  
* **K-Means**: Identified 3 distinct user clusters

---

## 🧠 Insights

* **Engagement** depends more on activity than age  
* **Emotion** influenced by comments and platform  
* **Clusters** reveal passive, moderate, and active users

---

## 🚀 Next Steps

* Add advanced ML models (e.g., XGBoost)  
* Explore NLP-based sentiment analysis  
* Investigate behavioral trends over time

 ## 📎 License
 academic and exploratory use
