# Stroke Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting stroke occurrence using machine learning techniques applied to a healthcare dataset. The aim is to identify individuals at risk of stroke while prioritizing recall, which is critical in medical prediction tasks.

## 📊 Dataset

* **Name:** Stroke Prediction Dataset
* **Source:** Kaggle
* **Link:** [https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
* **Records:** 5,110
* **Target Variable:** `stroke` (0 = No Stroke, 1 = Stroke)

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

## 🔍 Project Workflow

1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Encoding & Scaling
4. Model Development
5. Model Evaluation & Comparison
6. Best Model Selection

## 🤖 Machine Learning Models Used

* Logistic Regression
* Decision Tree
* K-Nearest Neighbors (KNN)

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy
* Recall (Primary Metric)
* Precision
* F1-Score
* Confusion Matrix

🔑 **Key Insight:**
Although KNN achieved higher accuracy, Logistic Regression performed best in detecting stroke cases due to its higher recall.

## ✅ Best Model

**Logistic Regression**
Selected due to its superior recall, making it more suitable for healthcare applications where minimizing false negatives is crucial.

## 📌 Results Visualization

All important plots and confusion matrices are available in the `images/` folder.

## 🚀 Future Scope

* Handle class imbalance using SMOTE
* Apply ensemble models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a healthcare decision-support system

## 👤 Author

**Arjun Maurya**
B.Tech CSE (Data Science Minor)
Lovely Professional University
