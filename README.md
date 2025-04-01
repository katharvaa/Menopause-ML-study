# Menopause: ML Analysis

This repository contains the source code and resources for the "Menopause: ML Analysis" project. The study investigates the influence of various clinical parameters on menopause symptom severity, utilizing advanced machine learning techniques to enhance clinical understanding and personalized healthcare.

## Overview

- **Objective:**  
  Analyze real-time clinical data to predict the severity of menopause symptoms (mild, moderate, severe) by identifying key diagnostic indicators.

- **Motivation:**  
  Menopause is a critical transition in a woman’s life characterized by diverse symptoms. This study aims to improve clinical decision-making and tailor interventions by uncovering influential predictors.

## Features

- **Data-Driven Insights:**  
  Leverages clinical data from Chettinad Hospital, Chennai, covering parameters like hormonal levels, BMI, and medical history.

- **Machine Learning Techniques:**  
  Implements four classifiers: SVM, KNN, Random Forest, and XGBoost along with four feature extraction methods:
  - Mutual Information (MI)
  - F-Statistics
  - Correlation Analysis
  - Chi-Squared Test

- **Model Optimization:**  
  Utilizes hyperparameter tuning and rigorous model evaluation to achieve high predictive accuracy.

- **Visualization:**  
  Provides interactive visualizations (heatmaps and more) to interpret the key clinical indicators influencing menopause symptom severity.

## Methodology

- **Data Collection:**  
  - Sourced real-time clinical data from physicians at Chettinad Hospital, Chennai.
  
- **Data Preprocessing:**  
  - Data augmentation using SHAP to address imbalance.
  - Extensive data cleaning to ensure quality and reliability.

- **Feature Extraction & Classification:**  
  - Applied four feature extraction techniques.
  - Combined each extraction method with four classifiers to identify the best predictive model.
  
- **Outcome:**  
  - The model categorizes the impact on menopause symptoms into three levels: mild, moderate, and severe.

## Technologies Used

- **Programming Language:** Python  
- **Development Environment:** Google Colab  
- **Machine Learning Libraries:** scikit-learn, XGBoost, and others as required
- **Visualization:** Libraries such as matplotlib and seaborn

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/katharvaa/Menopause-ML-study.git
   cd Menopause-ML-study
