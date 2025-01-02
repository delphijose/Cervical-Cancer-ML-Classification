# **Cervical Cancer Prediction Utilizing Machine Learning Techniques**

This project focuses on building a machine learning classification model to predict the likelihood of cervical cancer risk using patient health history data. The ultimate goal is to aid in early detection and better patient care.

---

## **Overview**
- **Objective**: Develop a classification model to predict high risk for cervical cancer based on patient health data.
- **Dataset**: Data collected from 'Hospital Universitario de Caracas,' Venezuela. Includes 35 features with the target variable `Biopsy` (binary: 1 = high risk, 0 = low risk).  
  Dataset link: [Cervical Cancer Risk Factors](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors).

---

## **Features**
- Utilized classification models:  
  - k-Means Clustering  
  - Linear SVM  
  - RBF Kernel SVM  
  - Polynomial Kernel SVM  
  - Logistic Regression  
- Dimensionality reduction techniques:  
  - Linear Discriminant Analysis (LDA)  
  - Principal Component Analysis (PCA)  

---

## **Results**
- **Best Model**: RBF Kernel SVM (no dimensionality reduction).  
  - Training Accuracy: **96.36%**  
  - Test Accuracy: **95.35%**  
- Dimensionality reduction (LDA and PCA) generally reduced accuracy.  

### Model Comparison Table:

| Model                | Training Accuracy | Test Accuracy |
|----------------------|-------------------|---------------|
| k-Means              | 93.59%           | 93.6%         |
| Linear SVM           | 96.5%            | 93.6%         |
| RBF Kernel SVM       | 96.36%           | 95.35%        |
| Logistic Regression  | 96.36%           | 93.6%         |
| Polynomial SVM       | 97.67%           | 94.77%        |

---

## **Future Work**
- Explore deep learning methods for further performance improvements.
- Consider developing a cancer risk scoring system for unsupervised learning applications.
