# Breast Cancer KNN & K-Means Project

This project analyzes a breast cancer dataset using two machine learning techniques: **K-Nearest Neighbors (KNN)** for classification and **K-Means** for clustering. The goal is to evaluate model performance and compare supervised and unsupervised learning approaches.

## 📁 Project Overview

* The notebook loads and preprocesses the breast cancer dataset.
* Features are standardized for improved model accuracy.
* A **KNN classifier** is trained to predict cancer diagnoses.
* A **K-Means clustering model** is used to explore natural data groupings.
* Evaluation metrics and visualizations are provided.

## 🔍 Methods Used

### **1. KNN Classification**

* Standardizes features using `StandardScaler`.
* Splits the dataset into training and testing sets.
* Trains a classifier with different values of *k*.
* Evaluates using accuracy, confusion matrix, and classification report.

### **2. K-Means Clustering**

* Applies K-Means to the standardized dataset.
* Compares clustering output with true labels.
* Visualizes clusters using PCA-reduced dimensions.

## 📊 Results Summary

* KNN provides strong performance for cancer prediction.
* K-Means shows reasonable clustering structure, though unsupervised methods are naturally less accurate.

## 🛠️ Requirements

To run the notebook, install:

* `numpy`
* `pandas`
* `matplotlib`
* `scikit-learn`

Install using:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## ▶️ How to Run

1. Open the `.ipynb` file in Jupyter Notebook, JupyterLab, or VS Code.
2. Run cells in order.
3. View outputs such as accuracy scores and clusters.

## 📚 Dataset

The project uses the **Breast Cancer Wisconsin dataset** included in `sklearn.datasets`.

## 📦 Output

* Model performance metrics
* Visualizations for clustering
* Comparative insights on supervised vs. unsupervised learning

---

Feel free to ask if you want enhancements, diagrams, or explanations for any section!
