# Reservoir Characterization using Machine Learning

## Overview

This project applies machine learning techniques to predict rock facies from well log data for reservoir characterization in the oil and gas industry. Using data from the Hugoton and Panoma gas fields, multiple supervised learning algorithms are trained and evaluated to automate geological interpretation and improve reservoir characterization.

---

## Features

- Implemented and compared **8 machine learning algorithms**:
  - Random Forest
  - XGBoost
  - LightGBM
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Gaussian Naive Bayes
  - Neural Network (MLP)

- Performed comprehensive data preprocessing, feature engineering, model evaluation, and hyperparameter optimization.

- Generated interactive visualizations including:
  - 3D Scatter Plots
  - Correlation Heatmaps
  - Well Log Displays

- Conducted blind well testing to evaluate model performance on unseen wells.

- Enabled model persistence for deployment using serialized trained models.

---

## Dataset

The dataset consists of **3,232 well log samples** collected from **8 wells**, containing **7 wireline log measurements**:

- Gamma Ray (GR)
- ILD_log10
- Photoelectric Effect (PE)
- DeltaPHI
- PHIND
- NM_M
- RELPOS

The target variable consists of **9 geological facies classes**, ranging from Sandstone to Bafflestone.

---

## Results

Random Forest achieved approximately **77% classification accuracy** with strong cross-validation performance. Tree-based ensemble methods consistently outperformed other machine learning algorithms due to their ability to capture complex, non-linear geological relationships present in well log data.

---

## Applications

- Automated Facies Classification
- Reservoir Characterization
- Reservoir Modeling
- Drilling Optimization
- Exploration Planning

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- SciPy
- Matplotlib
- Seaborn
