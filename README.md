# Clinical Diagnosis Classification (Applied AI)

This repository contains a comprehensive machine learning project developed for the **COMP534 (Applied AI)** module at the **University of Liverpool**.

## 📌 Project Overview
The objective is to predict patient diagnoses—**Chronic Illness (CI)**, **Depression**, or **Both**—based on clinical and lifestyle features.

## 🛠️ Key Technical Steps
* **Data Management**: 
    * Handled data entry errors (PHQ-9 scores > 27) and removed non-predictive features (ID, Country).
    * Mitigated **multicollinearity** by analyzing correlation heatmaps (e.g., removing redundant sleep quality metrics).
* **Modelling**: Compared **Logistic Regression** and **Decision Trees** for multi-class classification.
* **Evaluation**: Achieved high accuracy on the test set, with feature importance analysis highlighting `pem_present` and `depression_phq9_score` as key discriminators.

## 📁 Repository Structure
* `Clinical_Diagnosis_AI_Model.ipynb`: Full implementation including EDA, preprocessing, and model training.
* `Technical_Report_Clinical_AI.pdf`: Formal technical report documenting experimental protocols and result analysis.

## 📊 Results
The Logistic Regression model achieved perfect separation on the test set. Analysis using shallow Decision Trees confirmed the dataset's high separability based on clinical indicators.
