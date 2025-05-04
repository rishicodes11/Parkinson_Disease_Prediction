# Parkinson Progression: EDA and Feature Engineering

This repository contains exploratory data analysis (EDA), preprocessing, and feature engineering steps performed on clinical and proteomic data for Parkinson's disease patients. The goal is to understand disease progression and prepare the dataset for predictive modeling.

# Project Overview

Parkinson’s disease progression is studied using the AMP PD dataset focusing on Unified Parkinson’s Disease Rating Scale (UPDRS) scores and associated proteomic biomarkers. This notebook explores the dataset in detail, handling missing values, transforming features, and visualizing relationships to support future machine learning models.

# Dataset
“Dataset and competition details were sourced from the Kaggle competition: AMP Parkinson’s Disease Progression Prediction.
 https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction

## Key Steps Performed

#Data Integration
- Merged multiple data sources: clinical, peptide, protein, and demographic data

#Feature Engineering
- Created logarithmic features: `log_NPX`, `log_PeptideAbundance`
- Developed temporal features: `prev_updrs_3`, `delta_updrs_3`, `rolling_updrs_3`
- Created interaction features

## Exploratory Data Analysis (EDA)
- Skewness analysis of numerical features
- Correlation heatmap
- Distribution plots for all numerical features
- Boxplots grouped by UPDRS-III quartiles
- Countplot for medication state distribution

## 🧰 Tools and Libraries

- Python 3.8+
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- Jupyter Notebooks
