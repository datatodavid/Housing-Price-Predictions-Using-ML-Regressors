# Machine Learning & Detecting Fraudulent Healthcare Providers

## [Blog Write-up WIP]() | [Kaggle]() | [David Gottlieb](https://www.linkedin.com/in/david-gottlieb-a351bb3b/) 

-------------------------------

### Project Goals

The goal of this project is to determine the best approaches for the following:
1) Creating an accurate regressor in which to predict housing prices for potential real estate builders sellers, realtors, and buyers in Ames, Iowa
2) To find more resource-efficient means of optimizing and tuning Machine Learning models
3) To see if ensmebling can help us determine the most important features in predicting the value of a house
4) To see what can be learned from this dataset that is applicable to other housing markets beyond Ames, Iowa
--------------------------------

### What's in this Repo?

Here you will find 3 notebooks of particular note: 
- I. Data Visualization and Statistical Analysis
- II. Pre-Processing Ames Housing Data
- III. Ames ML Models Final Code with Comments

Considering the length of the project, I found it was clearer to parse the three approaches into separate notebooks for easier viewing.

## Pre-Processing Ames Housing Data
Contents
I. Barebones Processing (Control Dataset)
II. Feature Engineering
 - Generating New Features
 - Consolidating Redundant Features
 - Quantitative Data Imputation
III. Filtering Noisy Classes Within Features
 - Creating a Frequency Filter for Dummification
 - Dummification of Remaining Nominal Features
IV. Ordinal Data Processing
 - Ordinal Feature Dummification
 - Ordinal Encoding through SciKitLearn's Ordinal Encoder
V. Filtering Observations using Cook's Distance Outliers
 - Cook's Distance filtering process for Ordinal Dummification Dataset
 - Cook's Distance filtering process for Ordinal Encoding Dataset
VI. Six ML-Ready Datasets

## Ames ML Models Final Code with Comments
I. METHOD: Using HyperTransformation Tuning and ML Model Ensembling
 - HyperTransformation Tuning - A New Machine Learning Optimization Approach
 - Machine Learning Model Ensembling
II. Dataset Preparation for Machine Learning
 - Load Data from Preprocessing and Create 80/20 Training/Test Splits for all 6 Datasets¶
 - Barebones Run
III. HyperTransformation Tuning 2: Scaled and Log Transformations
IV. HyperTransformation Pruning #1
V. HyperTransformation Tuning 3: PCA Transformations
 - Best PCA Models
 - Best Dataset Transformations For All 10 Models So Far
VI. HyperTransformation Tuning 4: Dimension Reduction
 - Lasso Lambda Coefficient Filter
 - Random Forest Feature Importance Filter
 - XGBoost Feature Importance Filter
 - Ridge Permutation Importance Filter
 - Creating an Average Importance Rank Filter
 - Best Dimension Reduction Models
VII. Does HyperParameter Tuning Still Have Value?
 - HyperParameter Tuning vs. HyperTransformation Tuning Conclusions
VIII. Statistical Analysis

--------------------------------

### For More

For further discussion of the project, its process, and the full analysis, please consult the blog post.