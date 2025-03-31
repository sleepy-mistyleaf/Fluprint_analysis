# Fluprint_analysis

## 1. FluPRINT Analysis for Understanding Vaccine Response.

## 2. Description
This project aims to analyze the FluPRINT dataset to better understand immune responses to influenza vaccines. This analysis's significance lies in its potential to identify novel biological factors influencing vaccine efficacy, which is crucial for improving public health outcomes. Understanding vaccination responses can help address current challenges in vaccine effectiveness and immune response variability.

## 3. Motivation
### The Problem
Current vaccination strategies face challenges due to variability in individual immune responses, which can lead to reduced vaccine effectiveness across different age groups and influenza seasons. Previously identified correlates of protection often fail to account for the majority of individual responses, highlighting the need for more comprehensive analyses.

 ### Main Goals:
Our primary goal is identifying key immune cell populations and molecular markers correlating with strong vaccine responses. By leveraging machine learning techniques, we aim to uncover novel predictors of vaccine efficacy and contribute to the development of more personalized vaccination strategies.

## 4. Dataset Information

   ### Source of the Data
The FluPRINT dataset is a multidimensional analysis of the influenza vaccine's impact on the immune system. It is publicly available and sourced from multiple clinical studies conducted between 2007 and 2015.

        The official Fluprint paper can be accessed via Tomic, A., Tomic, I., Dekker, C.L. et al. The FluPRINT dataset, a multidimensional analysis of the influenza vaccine imprint on the immune system. Sci Data 6, 214 (2019). https://doi.org/10.1038/s41597-019-0213-4
        
        Data was downloaded from Zenodo: https://zenodo.org/records/3222451#.XOb7MaR7lPY
        
        Data is also available at https://fluprint.com.

   ### Preprocessing Steps
Preprocessing involved cleaning data, handling missing values, and transforming features (e.g., one-hot encoding for categorical variables). We also applied techniques like SMOTE to address class imbalance.

## 6. Methodology Overview
### Data Cleaning Techniques:
 - Data Inspection: Initial exploration to identify missing values and outliers.
 - Data Transformation: Pivoting and column renaming to organize immune cell data.
 - Feature Retention: Applying a threshold to exclude features with high sparsity.

### Machine Learning Models
1. Logistic Regression: Used for initial classification tasks.
2. Polynomial Regression: Explored to capture non-linear relationships.
3. Random Forest: Employed for handling high-dimensional data and complex interactions.
4. Gradient Boosting Classifier: Utilized to mitigate overfitting issues.
5. K-Means Clustering: Applied for unsupervised learning to identify immune profiles.

### Evaluation Metrics
- Accuracy: Primary metric for classification models.
- F1-Score: Used to assess the balance between precision and recall.
- ROC AUC: Evaluated for class separation and model robustness.
- Cross-Validation: Employed to ensure model generalizability.


