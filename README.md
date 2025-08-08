# Milestone Assignment 2 – Principal Component Analysis (PCA)

## Project Overview
As a Data Analyst at the Anderson Cancer Center, the objective is to build a model that identifies essential variables for securing donor funding, using **Principal Component Analysis (PCA)** to reduce dimensionality in the dataset.  

The dataset used is the **Breast Cancer Wisconsin Dataset** from `sklearn.datasets`.

This project:
- Performs PCA to determine important components.
- Reduces data into **2 principal components**.
- Implements **Logistic Regression** for classification.
- Includes clear steps for reproduction.

---

## Dataset
I used the **Breast Cancer Wisconsin dataset** provided by Scikit-Learn.

**Features:** 30 numeric predictors (e.g., radius mean, texture mean, etc.)  
**Target:** Binary classification (`0` = malignant, `1` = benign)  
**Shape:** 569 samples × 30 features

---

## Results
- **Explained Variance Ratio (PC1 & PC2):** Typically around 0.63 and 0.05 (may vary slightly), meaning the first 2 PCs explain about **68%** of the variance.
- **Logistic Regression Accuracy:** Usually around **90–95%** on the reduced dataset.

---


