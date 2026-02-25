# ❤️ Heart Disease Prediction: Clinical Classification Model

**Developer:** Hifza Nazir — AI Engineering Intern  
**Organization:** DevelopersHub Corporation  
**Task:** 03 - Heart Disease Classification  
**Date:** 11 February 2026

---

## 📌 Project Overview
This project involves building a Machine Learning classification model to predict the presence of heart disease based on clinical medical data (features like age, cholesterol, chest pain type, etc.). Using **Logistic Regression**, the model identifies whether a patient is at risk, providing a data-driven approach to healthcare diagnostics.

---

## 🛠️ Technical Workflow & Implementation

### 1. Data Acquisition & Preprocessing
* **Dataset**: Utilized the clinical heart disease dataset (TensorFlow medical data source).
* **Data Cleaning**: Verified the integrity of the data by checking for null values and performing statistical analysis.
* **Feature Engineering**: Implemented **One-Hot Encoding** on categorical features (like 'thal') to convert medical text data into numerical format for the algorithm.
* **Scaling & Splitting**: Segmented the data into an 80/20 train-test split to ensure unbiased evaluation.

### 2. Model Architecture
* **Algorithm**: **Logistic Regression** (Optimized with `max_iter=1000`).
* **Objective**: Binary classification (0: Healthy, 1: Heart Disease).

### 3. Evaluation Metrics
The model was rigorously tested using multiple performance indicators:
* **Accuracy Score**: Achieved a high accuracy of **83.61%**.
* **Confusion Matrix**: Visualized correct vs. incorrect classifications (True Positives, False Positives, etc.).
* **ROC Curve & AUC**: Measured the model's ability to distinguish between classes, achieving a strong **AUC score**.

---

## 📊 Performance Insights

*The Confusion Matrix confirms a high rate of successful predictions for both healthy and at-risk patients.*

*The ROC Curve illustrates the strong diagnostic ability of the model with a significant area under the curve.*

---

## 🧬 Key Skills Demonstrated
* **Supervised Learning**: Implementing binary classification algorithms.
* **Medical Data Preprocessing**: Handling clinical datasets and categorical encoding.
* **Statistical Visualization**: Interpreting model quality through Seaborn and Matplotlib.
* **Healthcare Analytics**: Applying AI to solve real-world diagnostic problems.

---
**Project Status:** ✅ Completed  
**Contact:** [Hifza Nazir](https://github.com/hifzanazir00781)  
*Final Submission for Task 3 | AI Engineering Internship*
