# Heart Disease Prediction – MLOps Assignment

## Overview
This project implements an end-to-end MLOps pipeline to predict the presence of heart disease using the UCI Heart Disease dataset.  
The focus is on reproducibility, experiment tracking, and production readiness following MLOps best practices.

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Target:** Presence of heart disease (binary classification: 0 / 1)
- **Features:** Age, sex, blood pressure, cholesterol, and other clinical attributes

## Tasks Completed
- **Task 1 – Data Acquisition & EDA**
  - Data cleaning and preprocessing
  - Exploratory Data Analysis with visualizations
- **Task 2 – Model Development**
  - Logistic Regression and Random Forest models
  - Evaluation using accuracy, precision, recall, and ROC-AUC
- **Task 3 – Experiment Tracking**
  - MLflow used to log parameters, metrics, and models
- **Task 4 – Model Packaging & Reproducibility**
  - Final model packaged as a reusable artifact
  - Dependencies captured using `requirements.txt`

## Repository Structure
```
mlops-heart-disease/
├── notebooks/
│   └── Task1_2_3_MLflow_FINAL.ipynb
├── artifacts/
│   ├── model.pkl
│   └── requirements.txt
```

## Final Model
- **Model Used:** Random Forest Classifier
- **Saved Artifact:** `artifacts/model.pkl`

## Reproducibility
The project is fully reproducible using the provided notebook and dependency file.  
The packaged model can be directly consumed by downstream services such as APIs, Docker containers, and CI/CD pipelines.

## Next Steps
- CI/CD pipeline setup
- Model serving via FastAPI
- Docker containerization
- Cloud/Kubernetes deployment
- Monitoring and logging

---

This repository serves as the ML foundation for the complete MLOps workflow.
