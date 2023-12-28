# Feature Importance in Breast Cancer Classification
## Overview:
This machine learning code utilizes a Random Forest classifier to determine the most crucial features in the Breast Cancer dataset. The process includes data preprocessing, heatmap visualization using seaborn, and feature importance analysis.

### Steps:
Data Loading:

The Breast Cancer dataset is loaded using scikit-learn.
### Data Splitting:

The dataset is split into training and testing sets with a stratified approach.
### Exploratory Data Analysis (EDA):

A DataFrame is created for EDA, and a correlation heatmap is generated using seaborn to visualize feature relationships.
### Correlation Analysis:

The correlation of each feature with the target variable (benign/malignant) is analyzed.
### Random Forest Classification:

A Random Forest classifier is trained on the dataset.
### Feature Importance:

The most important features are identified using the trained classifier.
### Usage:

Analyze feature importance and correlations in Breast Cancer dataset.
### Libraries Used:
pandas
seaborn
scikit-learn
