# 💳 Credit Card Fraud Detection: End-to-End Pipeline

This repository features a complete machine learning solution for identifying fraudulent credit card transactions. The project focuses on solving the "needle in a haystack" problem using advanced resampling techniques and real-time model deployment.

---

### ⚠️ The Challenge: Imbalanced Dataset
The primary hurdle in fraud detection is the extreme class imbalance. In this dataset, fraudulent transactions represent a tiny fraction of the total data. 
* **Problem:** Standard models tend to ignore the minority class, leading to high accuracy but zero fraud detection.
* **Solution:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** and **RandomOverSampler** to balance the training set, drastically reducing bias and improving the model's sensitivity to fraud.

---

### 🏗️ Workflow & Architecture
1. **Data Preprocessing:** Cleaning and scaling transactional data using Pandas and Scikit-learn.
2. **Handling Imbalance:** Utilizing `imbalanced-learn` to generate synthetic fraud samples.
3. **Model Training:** Training robust classifiers optimized for high precision and recall.
4. **Serialization:** Saving the trained model via **Joblib** for production use.
5. **Interactive UI:** Deploying a web-based interface using **Gradio** for real-time inference.

---

### 🛠️ Tools & Technologies
*   **Language:** Python 3.x
*   **Data Science:** Scikit-learn, NumPy, Pandas
*   **Sampling:** Imbalanced-learn (SMOTE)
*   **Deployment:** Gradio (Interactive UI)
*   **Environment:** Jupyter Notebook, GitHub

---

