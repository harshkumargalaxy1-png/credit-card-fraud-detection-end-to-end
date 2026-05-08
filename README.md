💳 Credit Card Fraud Detection Pipeline
🛡️ Project Overview
This project addresses the critical challenge of identifying fraudulent credit card transactions using machine learning. Financial datasets are notoriously difficult to model due to extreme class imbalance—where legitimate transactions vastly outnumber fraudulent ones. This repository provides an end-to-end solution, from data resampling to a live interactive interface.

🏗️ Technical Architecture
The core of this project is a robust pipeline designed to handle "needle-in-a-haystack" scenarios. By implementing advanced sampling techniques, the model moves beyond simple pattern matching to genuine anomaly detection.

Handling Imbalance: Applied SMOTE (Synthetic Minority Over-sampling Technique) and RandomOverSampler to generate synthetic fraud cases. This ensures the model learns the specific characteristics of fraud rather than simply defaulting to the majority "legitimate" class.

Modeling Strategy: Developed using Scikit-learn, focusing on tree-based classifiers that excel at capturing non-linear relationships in transactional data.

Interactive Deployment: Integrated a real-time UI using Gradio, allowing users to input transaction features and receive instant fraud probability scores.

📊 Key Features
Data Resampling: Mitigated bias toward the majority class, significantly improving the Recall and AUPRC (Area Under Precision-Recall Curve) metrics.

Modular Workflow: Separate scripts for data preprocessing, model training, and deployment for high maintainability.

Feature Engineering: Includes scaling and transformation of anonymized features to maximize the predictive power of the model.

🛠️ Tech Stack
Core Logic: Python (Pandas, NumPy, Scikit-learn)

Imbalance Handling: Imbalanced-learn (SMOTE)

UI/Deployment: Gradio, Joblib

Environment: Jupyter Notebook, GitHub

🚀 Usage
