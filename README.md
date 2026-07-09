# Reservoir-Characterization-using-ML

#Overview
#This project applies machine learning techniques to predict rock facies from well log data for reservoir characterization in the oil and gas industry. Using data from the Hugoton and Panoma gas fields, we build and compare multiple classification models to automate geological interpretation.

#Features
#8 ML Algorithms: Random Forest, XGBoost, LightGBM, SVM, KNN, Decision Tree, Naive Bayes, Neural Network
#Comprehensive Analysis: Data preprocessing, feature engineering, model evaluation, and optimization
#Interactive Visualizations: 3D scatter plots, correlation heatmaps, well log displays
#Blind Well Testing: Validation on unseen data for real-world reliability
#Model Persistence: Exportable models for production deployment
#Dataset:
3,232 samples from 8 wells with 7 wireline log measurements (GR, ILD_log10, PE, DeltaPHI, PHIND, NM_M, RELPOS) and 9 facies classes ranging from Sandstone to Bafflestone.

#Results
Random Forest achieves ~77% accuracy with robust cross-validation performance. Tree-based models consistently outperform other algorithms due to their ability to capture non-linear geological relationships.

#Applications
#Automated Facies Classification: Real-time well log interpretation
#Reservoir Modeling: Enhanced geological models
#Drilling Optimization: Data-driven decision support
#Exploration Planning: Improved target identification
