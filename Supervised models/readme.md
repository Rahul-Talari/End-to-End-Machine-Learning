# Supervised ML Models

This repository contains a collection of machine learning models, algorithms, and techniques implemented in Python. The models cover a wide range of topics, including regression, classification, and ensemble methods, among others. This is a comprehensive guide to the most widely-used machine learning algorithms, including both traditional and modern methods.

## Models Overview

The models in this repository are categorized as follows:

### 1. **Naive Bayes Theorem**
   - **Gaussian Naive Bayes**
   - **Multinomial Naive Bayes**
   - **Bernoulli Naive Bayes**

### 2. **Linear Models**
   - **Linear Regression**  
     - Ordinary Least Squares (OLS)
     - Least Mean Squares (LMS)
     - Batch Gradient Descent Optimization (GDO)
     - Stochastic Gradient Descent (SGD)
     - Mini-batch Stochastic Gradient Descent
     - Regularization:
       - L1 Regularization (Lasso Regression)
       - L2 Regularization (Ridge Regression)
       - L1+L2 Regularization (Elastic Net)
   - **Multiple Linear Regression**
   - **Polynomial Linear Regression**
   - **Robust Regression**  
     - Huber Regression
     - Quantile Regression
   - **Generalized Linear Models (GLMs)**  
     - Continuous Outcome: Linear Regression
     - Binary Outcome: Logistic Regression
     - Categorical Outcome:
       - Ordinal Data:
         - Proportional Odds: Basic Ordinal Logistic Regression
         - Non-Proportional Odds: Generalized Ordinal Logistic Regression
       - Nominal Data: Multinomial Logistic Regression
     - Count Outcome:
       - Equi-dispersed Data: Poisson Regression
       - Non-Equi-dispersed Data: Negative Binomial Regression

### 3. **Support Vector Machines (SVM)**
   - **Hard Margin Classifier (for linearly separable data)**
   - **Soft Margin Classifier (for linearly non-separable data)**
     - Kernel-Induced Feature Space
     - Non-Linear Classifier
   - **Decomposing Multi-class Classification**  
     - One-vs-All
     - One-vs-One
   - **Support Vector Regression (SVR)**  
     - Linear Regression
     - Non-Linear Regression

### 4. **K-Nearest Neighbour (KNN)**

### 5. **Decision Trees**
   - **ID3** (Classification)
   - **C4.5** (Classification)
   - **CART** (Classification & Regression)

### 6. **Ensemble Methods**
   - **Homogeneous Ensemble Models:**
     - Bagging:
       - Random Forest
       - Extremely Randomized Trees (ExtraTrees)
     - Boosting:
       - Adaptive Boosting (AdaBoost)
       - Gradient Boosting Machine (GBM)
       - Stochastic Gradient Boosting Machine (Stochastic GBM)
       - Extreme Gradient Boosting Machine (Extreme GBM)
       - LightGBM
       - Categorical Gradient Boosting Machine (CatBoost)
   - **Heterogeneous Ensemble Models:**
     - Stacking
     - Blending

### 7. **AutoML**
