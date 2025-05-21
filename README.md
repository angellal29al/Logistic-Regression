# 🔍 Predicting Banknote Authenticity Using Logistic Regression

## 📌 Objective
This project aims to apply a **classification algorithm (Logistic Regression)** to solve a problem in the **Finance/Business Analytics** domain — predicting the **authenticity of a banknote** based on image-based statistical features.

---

## 📊 Dataset Description

- **Observations**: 1,372 instances.
- **Features**:
  - `V` – Variance of Wavelet Transformed image (continuous)
  - `S` – Skewness of Wavelet Transformed image (continuous)
  - `K` – Kurtosis of Wavelet Transformed image (continuous)
  - `E` – Entropy of image (continuous)
  - `Class` – Target variable (0: Authentic, 1: Inauthentic)

---

## 📈 Exploratory Data Analysis (EDA)

- Count plot revealed:
  - **Authentic Notes**: ~55.54%
  - **Inauthentic Notes**: ~44.46%
- The class distribution is fairly balanced, so **SMOTE or other resampling techniques were not required**.
- Additional visualizations were used to understand the distribution and relationship of features.

---

## 🧠 Model Implementation

### ✅ Algorithm: Logistic Regression

- A **Logistic Regression classifier** was trained on the dataset.
- The dataset was split into training and test sets.
- Evaluation metrics were computed on the test set.

### 🔍 Accuracy:Accuracy on test set: 0.99

### 📉 ROC Curve & AUC:
- **ROC Curve** was plotted.
- **Area Under Curve (AUC)** = 0.99 — indicates **excellent classification performance**.

---

## 📝 Summary Report

This project tackled a finance-related problem by building a **binary classifier** that predicts whether a banknote is genuine based on statistical characteristics of its image. 

The model achieved:
- **99% Accuracy**
- **AUC of 0.99**

This shows that Logistic Regression is a **highly effective and interpretable** model for this classification task.

---

## 📌 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

⭐ Feel free to fork or star this repository if you find it helpful!
