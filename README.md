# Breast_Cancer_Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-1.5-brightgreen) 
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-purple)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-1.2-orange)  


This repository contains a Python implementation of feature importance analysis using a Random Forest Classifier. The code identifies and visualizes the most important features in a given dataset, helping in feature selection and improving model interpretability.  

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#HousingDataset)  
- [Exploratory Data Analysis](#exploratory-data-analysis)   
- [Tools & Libraries](#Tools&Libraries)
- [How to Run](#how-to-run)  
- [Conclusion](#conclusion)  
- [Author](#author)  
## Project Overview

A Random Forest Classifier is an ensemble learning method that combines multiple decision trees to improve accuracy and reduce overfitting. After training the model on a dataset, it provides feature importance scores, which indicate how much each feature contributes to making predictions. These importance values help in understanding which variables have the most influence on the target outcome. By ranking the features in descending order of importance, we can identify the most significant predictors and potentially drop less important ones for a simpler model. To make the results more interpretable, the feature importances can be visualized using a bar chart, where each bar represents a feature and its corresponding importance score. This visualization provides a clear and intuitive way to understand the relative impact of each feature in the model.


## 🏠 Housing Dataset 

**Dataset Source:** [Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

- id: Patient record identifier.

- diagnosis: Tumor diagnosis (M = Malignant, B = Benign).
- mean features: Average values of radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.
- se features: Standard error values for the same set of features.
- worst features: Maximum (worst-case) values of the same features.
- Unnamed: 32: Empty column (drop as irrelevant).

## Exploratory Data Analysis

1. **Data Overview**
  - Loaded the dataset and examined basic statistics and structure.
  - Checked for missing values and inconsistencies to ensure data quality.

2. **Feature Distribution Analysis**
  - Visualized the distribution of numerical features using histograms and density plots.
  - Identified skewness and potential outliers in key features.

3. **Correlation Analysis**
  - Computed the correlation matrix for numerical features.
  - Visualized correlations using a heatmap to detect strong relationships between variables.

4. **Categorical Feature Analysis**
  - Created count plots for categorical variables to examine class distributions.
  - Observed imbalances and unique patterns in categorical features.

5. **Boxplots for Feature Comparison**
  - Compared numerical feature distributions against categorical variables.
  - Detected variations in feature values that may influence model predictions.

6. **Feature Importance Visualization**
  - Encoded categorical variables for model compatibility.
  - Applied a Random Forest Classifier to compute and rank feature importances.
  - Visualized importance scores using a bar chart with error bars for clarity.

## Tools & Libraries
- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive coding environment

 

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Shrilaxmi-16/Breast_Cancer_Analysis.git


## Conclusion

This project demonstrates how a Logestic Regression and Random Forest Classifier can be effectively used to perform feature importance analysis. Through exploratory data analysis, strong patterns and correlations between features were identified, and categorical variables were encoded for modeling. The Random Forest model ranked features based on their influence on predictions, providing valuable insights for feature selection and dimensionality reduction. Such analysis not only improves model performance but also enhances interpretability, enabling data-driven decision-making. This approach can be applied to a wide range of datasets to uncover the most impactful features and streamline predictive modeling workflows.

## Author
Shrilaxmi Gidd

Email: shrilaxmigidd16@gmail.com

Date: 26-09-2025
  
