Heart Disease Prediction Project

This repository contains a complete machine learning pipeline for predicting heart disease using clinical patient data.

Features
Data cleaning and preprocessing (handling missing values, scaling, encoding)
Exploratory Data Analysis (EDA)
Clustering (K-Means, Hierarchical)
Dimensionality Reduction (PCA)
Supervised Models:
Random Forest 
XGBoost 
Neural Network (MLP) 
CNN experimentation (MNIST dataset)
Model evaluation using Accuracy, F1-score, AUC
Feature importance analysis
Streamlit web app for deployment
Results
Best ML Model: XGBoost / MLP (~87% accuracy)
Random Forest AUC: 0.94
CNN (MNIST accuracy): 97%
 Deployment

Run the Streamlit app:
streamlit run app.py
Files Included
heart_model.pkl → trained ML model
scaler.pkl → preprocessing scaler
processed dataset
Streamlit app code
Jupyter notebook analysis
 Dataset

Cleveland Heart Disease Dataset (UCI Repository)

 Conclusion

This project demonstrates a full machine learning lifecycle from data analysis to deployment, providing a practical healthcare prediction system.
