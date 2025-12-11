Dain Jang — AI & Data Science Portfolio (2025)

This repository presents my collection of projects in Deep Learning, Medical AI, PGHD analysis, and Recommendation Systems.
All projects include preprocessing, modeling, evaluation, and interpretation (XAI) in reproducible Jupyter Notebooks.

1. Medical Image Analysis (Deep Learning)
Brain MRI Tumor Classification
Goal: Classify MRI brain tumors.
Model: CNN
Performance: Accuracy 93%
Highlights:
Full preprocessing and augmentation pipeline
Confusion matrix & misclassification analysis

Chest X-ray Pneumonia Detection (XAI)
Goal: Detect pneumonia using CNN + Grad-CAM
Performance: Accuracy 90%
Highlights:
Grad-CAM heatmap aligned with lung lesion region
Strong model interpretability

X-ray Body Part Classification
Goal: Identify anatomical region from X-ray images
Performance: Accuracy 95%

2. PGHD (Personal Health Data) Analytics
Stress Index Prediction
Model: RandomForest, Gradient Boosting
Performance: MAE 2.31, R² 0.91
Highlights:
Feature importance (SHAP)
Full pipeline from cleaning → modeling → evaluation

Body Fat Percentage Regression
Performance: RMSE 3.1, R² 0.93
Highlights:
Exploratory analysis
Multiple regression models comparison

3. Recommender System
E-commerce Personalized Recommendation System
Model: Collaborative Filtering
Metrics: NDCG@10 0.41, Precision@10 0.32
Award: Selected as Outstanding Project at OUTTA AI Bootcamp
Highlights:
End-to-end system (EDA → model → ranking metrics)
Reproducible notebook structure

Tech Stack
Python, PyTorch, Scikit-learn, Pandas, NumPy
Grad-CAM, SHAP
Matplotlib, Seaborn
Collaborative Filtering, Implicit Feedback Modeling
