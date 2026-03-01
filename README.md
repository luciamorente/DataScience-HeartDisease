# Clinical Factors Associated with Heart Disease

This project aims to identify and analyze clinical factors associated with heart disease in patients. Statistical analyses, exploratory data analysis, and machine learning techniques are applied to uncover relationships between variables and build predictive models.

## Overview
Developed by **Teresa Conde Germán-Coley** and **Lucía Morente Navas**, this study examines a clinical dataset of patients suspected of having heart disease, including demographic, physiological, and symptomatic variables, to determine their impact on diagnosis.

The analysis includes:  
- Data cleaning and preprocessing.  
- Exploratory data visualization and outlier detection.  
- Statistical tests to assess associations (Wilcoxon, Chi-square, Kruskal–Wallis).  
- Predictive modeling using logistic regression, PCA, and K-Means clustering.  
- Model evaluation with AUC and principal component analysis interpretation.

## Key Features
- **Data Preprocessing:** Handling missing and invalid values, converting variables to appropriate formats.  
- **Data Visualization:** Boxplots, density plots, and grouped analyses by age ranges.  
- **Statistical Analysis & Modeling:** Normality tests, correlations, Chi-square tests, logistic regression, PCA, K-Means clustering.  
- **Model Evaluation:** ROC curves, AUC metrics, Odds Ratios, and confidence intervals for clinical interpretation.

## Dataset
- **Source:** Cleveland Heart Disease dataset.  
- **Variables:** Age, sex, chest pain type, resting blood pressure, cholesterol, maximum heart rate, exercise-induced angina, ST depression (*oldpeak*), among others.  
- **Target variable:** `diagnosis` (0 = no heart disease, 1 = heart disease present).

## Results
- Identification of clinical factors significantly associated with heart disease.  
- Logistic regression and PCA models show strong predictive performance (AUC ≈ 0.87).  
- K-Means clustering reveals distinct patient profiles and risk patterns.

## Installation
To run this project locally, you need **R** and **RStudio**.

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/DataScience-HeartDisease.git
cd DataScience-HeartDisease
