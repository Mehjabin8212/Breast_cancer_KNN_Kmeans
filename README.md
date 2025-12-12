# Breast Cancer Diagnosis using KNN & K-Means

This assignment presents a very simplified and intuitive tutorial on how we can better analyze breast cancer data with the help of machine learning. Through using **K-Nearest Neighbors Classification**, as well as **K-Means clustering**, we will be exploring the ways on how we can classify cancer instances or identify any natural grouping within the data.

## What This Project Does

The workflow follows a structured pipeline:

* Converts diagnosis labels into numeric form

  * **M → 1 (Malignant)**
  * **B → 0 (Benign)**
* Drops unnecessary columns such as:
* Splits the dataset into:

  * **80% Training**
  * **20% Testing**
* Applies **K-Means clustering (k = 2)** to observe natural groupings
* Trains a **KNN classifier (k = 5)** on the scaled training set
* Evaluates the classification model using standard metrics

## Methods & Workflow

### **1. Preprocessing**

* Loaded the CSV dataset
* Encoded diagnosis labels (M = 1, B = 0)
* Removed unnecessary or empty columns
* Normalized all numeric features with **MinMaxScaler** for consistency

### **2. K-Means Clustering**

* Applied **k = 2**, suitable because the dataset has two classes
* Compared the resulting clusters to the actual diagnosis labels
* Helped visualize how well unsupervised grouping aligns with real classifications

### **3. KNN Classification**

* Used **KNeighborsClassifier (k = 5)**
* Trained the model using normalized training data
* Tested on the 20% held-out test set

## Model Evaluation

The KNN classifier performed strongly.

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | ~0.95–0.97 |
| Precision | ~0.95      |
| Recall    | ~0.95      |
| F1-score  | ~0.95      |

## Files Included

### **Breast_Cancer_Diagnosis.ipynb**

The full notebook containing:
* Preprocessing
* K-Means clustering
* KNN classification
* Evaluation.

### **README.md**

A summarized and user-friendly explanation of the entire project.

## How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Upload the dataset when prompted.
3. Run all cells in sequence.

