# EDA and Feature Engineering for Data Science

## Introduction

Exploratory Data Analysis (EDA) and Feature Engineering are fundamental steps in data science. They help uncover patterns, clean data, and create new features that improve model performance. This repository provides a structured approach to understanding EDA, data cleaning, feature engineering, and hypothesis testing sensitivity, ensuring data is optimized for machine learning and statistical analysis. This is the result of the knowledge covered in previous repositories ([Mathematics](https://github.com/H0wl3r2001/DataScientist_Mathematics), [Probability](https://github.com/H0wl3r2001/DataScientist_Probability), and [Statistics](https://github.com/H0wl3r2001/DataScientist_Statistics)).

## Table of Contents

1. [Introduction to EDA](#introduction-to-eda)
2. [EDA for Different Data Types](#eda-for-different-data-types)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Feature Engineering and Selection](#feature-engineering-and-selection)
5. [Hypothesis Testing Sensitivity](#hypothesis-testing-sensitivity)
6. [Real-World Case Studies](#real-world-case-studies)
7. [Extra Resources](#extra-resources)

---

## Introduction to EDA

Exploratory Data Analysis (EDA) helps to understand the structure, relationships, and patterns in data. Key techniques include:

### Summary Statistics
- **Mean, Median, Mode**: Measures of central tendency.
- **Variance & Standard Deviation**: Spread of the data.
- **Skewness & Kurtosis**: Distribution shape.

### Data Visualization
- **Histograms & Boxplots**: Understanding distributions.
- **Scatterplots & Correlation Matrices**: Identifying relationships.
- **Time Series Plots**: Observing trends over time.

---

## EDA for Different Data Types

### Numerical Data
- Distribution analysis
- Transformation techniques (log, square root, etc.)

### Categorical Data
- Frequency counts and bar charts
- Encoding strategies (One-Hot, Label Encoding)

### Time Series Data
- Trend, seasonality, and autocorrelation analysis

### Text Data
- Tokenization, TF-IDF, and sentiment analysis

### Image Data
- Histogram of pixel values and PCA on embeddings

---

## Data Cleaning and Preprocessing

### Handling Missing Data
- Imputation techniques (mean, median, mode)
- Dropping missing values

### Outlier Detection
- Z-score and IQR-based methods

### Scaling & Normalization
- StandardScaler, MinMaxScaler, RobustScaler

---

## Feature Engineering and Selection

### Creating New Features
- Polynomial features, interactions, binning

### Multicollinearity Detection
- Variance Inflation Factor (VIF), correlation matrices

### Feature Selection Techniques
- Filter: Variance Threshold, Mutual Information
- Wrapper: Recursive Feature Elimination (RFE)
- Embedded: LASSO, Decision Tree Importance

### Dimensionality Reduction
- PCA, t-SNE, UMAP

---

## Hypothesis Testing Sensitivity

### Minimum Detectable Effect (MDE)
- Smallest change detectable with statistical power

### Variance Reduction Techniques
- CUPED (Controlled-experiment Using Pre-Experiment Data)
- CUPAC (Controlled-experiment Using Pre-Assignment Covariates)

### Handling Ratio Metrics
- Revenue per user, conversion rates, delta method

---

## Real-World Case Studies

- **Customer Churn Analysis**
- **Healthcare Analytics (Survival Analysis)**
- **Stock Market Trends (Finance)**
- **Sentiment Analysis (NLP)**
- **Fraud Detection (Feature Engineering)**

---