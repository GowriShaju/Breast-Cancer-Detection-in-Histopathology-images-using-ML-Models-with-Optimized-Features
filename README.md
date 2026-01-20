# Breast Cancer Detection using Machine Learning with Optimized Features

## Project Overview
This project presents a comparative study on detecting breast cancer using machine learning models trained on optimized feature sets extracted from histopathology image data. The objective is to analyze how evolutionary optimization algorithms improve classification performance when compared to models trained on the full feature set.

The study focuses on classifying breast tumors as **Benign** or **Malignant** using the Wisconsin Breast Cancer (Wincosin) dataset.

---

## Dataset Description
- Dataset: **Wincosin Breast Cancer Dataset**
- Total Instances: **569**
- Benign Cases: **357**
- Malignant Cases: **212**
- Total Features: **30 numerical attributes**

This dataset contains features extracted from histopathology images of breast tissue samples.

---

## Objective
- To evaluate machine learning models for breast cancer classification.
- To improve classification accuracy using feature selection through optimization algorithms.
- To compare model performance with and without optimized features.

---

## Machine Learning Models Used
The following classification algorithms were implemented:

1. Logistic Regression  
2. Support Vector Machine (SVM)  
3. K-Nearest Neighbors (KNN)  
4. Random Forest  

---

## Feature Optimization Algorithms

To improve model performance, the following evolutionary optimization techniques were applied:

- Particle Swarm Optimization (PSO)
- Ant Colony Optimization (ACO)
- Genetic Algorithm (GA)
- Differential Evolution (DE)
- Whale Optimization Algorithm (WOA)

These algorithms were used to select the most relevant subset of features before training the models.

---

## Methodology

### Phase 1 – Without Optimization
- All 30 features were used.
- Models were trained and evaluated.
- Baseline accuracy, precision, recall, and F1 score were recorded.

### Phase 2 – With Optimization
- Optimization algorithms selected optimal feature subsets.
- Models were retrained using selected features.
- Performance metrics were compared with Phase 1 results.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## Key Results

- The best performing model was:
**Logistic Regression + Genetic Algorithm**

- Achieved:
  - **Accuracy: 98.24%**
  - **Precision: 97.67%**
  - **Recall: 97.67%**
  - **F1 Score: 97.67%**

This shows that feature optimization significantly improves classification performance.

---

## Technologies Used

- Python  
- Scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn 

