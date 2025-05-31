Here’s a professional `README.md` for your **OCD Medication Prediction & Clustering Project**, suitable for GitHub:

---

# 🧠 OCD Treatment Prediction and Clustering using Machine Learning

This project focuses on understanding and predicting **Obsessive-Compulsive Disorder (OCD)** treatment patterns. It includes two major components:

1. **Classification Model** to predict the most suitable medication.
2. **Clustering Model** to uncover hidden patient subgroups based on symptoms and behavior.

The ultimate goal is to improve treatment personalization for better mental health outcomes.

---

## 🩺 Project Overview

**Obsessive-Compulsive Disorder (OCD)** is a chronic mental health condition characterized by recurring, unwanted thoughts (obsessions) and behaviors (compulsions). Treatment typically involves medication and/or therapy. However, patient response can vary widely.

This project applies machine learning to:

* Predict medication categories (SSRIs, CBT, others) based on patient data.
* Cluster patients into meaningful groups for tailored treatment strategies.

---

## 📊 Dataset Description

The dataset contains anonymized patient records with features such as:

| Feature             | Description                                        |
| ------------------- | -------------------------------------------------- |
| `Age`               | Patient's age                                      |
| `Gender`            | Male/Female/Other                                  |
| `Symptom Severity`  | Scale or score representing OCD severity           |
| `Compulsion Type`   | e.g., checking, washing, counting                  |
| `Duration (months)` | How long symptoms have persisted                   |
| `Comorbidities`     | Co-existing conditions (anxiety, depression, etc.) |
| `Family History`    | Yes/No                                             |
| `Medication Taken`  | Target variable (for classification)               |

---

## 🧪 Methodology

### 1. Data Preprocessing

* Handled missing and inconsistent values
* Encoded categorical features
* Scaled numerical data

### 2. Exploratory Data Analysis (EDA)

* Visualized distributions of age, severity, and compulsion types
* Analyzed relationships between medication and symptoms
* Checked class balance for medication labels

### 3. Classification Modeling (Supervised)

* Models tried:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Evaluation metrics:

  * Accuracy, Precision, Recall, F1-Score
  * Confusion Matrix

### 4. Clustering (Unsupervised)

* Used KMeans and DBSCAN to discover patient segments
* Visualized clusters using PCA & t-SNE
* Interpreted clusters based on compulsion types, severity, and comorbidities

---

## 📈 Results

### Classification:

* Best model: **XGBoost**
* Accuracy: **X%**
* Most influential features:

  * Symptom severity
  * Comorbidities
  * Family history

### Clustering:

* Identified **K distinct patient groups**
* Each cluster represents a different behavioral or symptom profile

---

## 📁 Project Structure

```
ocd-treatment-prediction/
│
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter notebooks for analysis and modeling
├── models/               # Saved model files
├── clustering/           # Scripts for unsupervised learning
├── classification/       # Scripts for medication prediction
├── utils/                # Utility functions
├── plots/                # Visualizations and charts
├── main.py               # Run pipeline end-to-end
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/ocd-treatment-prediction.git
cd ocd-treatment-prediction
pip install -r requirements.txt
```

---

## 🧠 Technologies Used

* Python (Pandas, Scikit-learn, XGBoost)
* Clustering: KMeans, DBSCAN, PCA, t-SNE
* Classification: Logistic Regression, Random Forest
* Visualization: Matplotlib, Seaborn

---
