# 🏦 Bank Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment bank customers based on their demographics and spending behavior. The goal is to help the bank better understand its customers and tailor marketing strategies accordingly.

---

## 📌 Objective

To perform **customer segmentation** using unsupervised learning techniques, enabling the bank to:

- Identify different groups of customers based on common patterns.
- Personalize marketing and product offerings.
- Improve customer retention and satisfaction.

---

## 📊 Dataset

The dataset includes features such as:

Number of unique values: 
Age                  53
Sex                   2
Job                   4
Housing               3
Saving accounts       4
Checking account      3
Credit amount       921
Duration             33
Purpose   

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets) or use your own.

---

## 🧠 Algorithm Used

**K-Means Clustering**  
- Unsupervised machine learning algorithm.  
- Groups data into `k` distinct clusters based on feature similarity.  
- Uses Euclidean distance to assign points to the nearest centroid.

---

## 📈 Project Steps

1. Data Cleaning and Preprocessing  
2. Feature Scaling (StandardScaler)  
3. Finding Optimal K using the **Elbow Method**  
4. Applying K-Means  
5. Visualizing the Clusters using 2D and 3D plots  
6. Interpreting Results

---

## 📌 Requirements

```bash
python>=3.8  
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
