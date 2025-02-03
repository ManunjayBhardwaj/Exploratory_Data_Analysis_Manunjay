# EDA and Feature Engineering for Machine Learning

This repository contains notebooks and resources dedicated to learning **Exploratory Data Analysis (EDA)** and **Feature Engineering** techniques. These techniques are essential for building robust machine learning models by preparing and transforming data effectively.

## Contents

### Feature Engineering Techniques Covered:
- **Handling Missing Values**
- **Handling Imbalanced Dataset**
- **Handling Imbalanced Dataset Using SMOTE**
- **Handling Outliers Using Python**
- **Data Encoding (Nominal and One-Hot Encoding)**
- **Label and Ordinal Encoding**
- **Target Guided Ordinal Encoding**

---

## Feature Engineering:

### 1. **Handling Missing Values** (Feature **125**)
Missing data is common in real-world datasets. Handling missing values effectively is essential for ensuring that machine learning algorithms can work with clean and complete data.

- Imputation techniques (mean, median, mode).
- Using models to predict missing values (e.g., k-NN, regression).
- Dropping missing values where appropriate.

---

### 2. **Handling Imbalanced Dataset** (Feature **126**)
In real-world datasets, you may encounter an imbalanced class distribution. This can lead to biased predictions, where the model predicts the majority class more often.

- Techniques for handling imbalance:
  - **Resampling methods** (Oversampling the minority class or undersampling the majority class).
  - **Class weight adjustments** in models.
  - **Synthetic data generation** to balance the dataset.

---

### 3. **Handling Imbalanced Dataset Using SMOTE** (Feature **127**)
**SMOTE (Synthetic Minority Over-sampling Technique)** is an advanced technique used to balance the class distribution by generating synthetic samples for the minority class.

- Generating synthetic data points in the feature space.
- Using libraries like `imbalanced-learn` in Python for implementation.

---

### 4. **Handling Outliers Using Python** (Feature **128**)
Outliers can skew the results of statistical analysis and machine learning models. It is essential to detect and handle outliers effectively.

- **Visualization**: Using box plots, histograms, and scatter plots to detect outliers.
- **Statistical Methods**: Using Z-scores, IQR (Interquartile Range) to identify and handle outliers.
- **Techniques**: Removing, capping, or transforming outliers to mitigate their effect.

---

### 5. **Data Encoding - Nominal or One-Hot Encoding** (Feature **129**)
Machine learning algorithms require numerical input, but many real-world datasets contain categorical data. **One-Hot Encoding (OHE)** is a widely used technique to convert categorical data into a numerical format.

- **Nominal Encoding**: Encoding categories as separate binary columns (0 or 1).
- **One-Hot Encoding (OHE)**: Encoding categorical variables into multiple binary columns, one for each category.

---

### 6. **Label and Ordinal Encoding** (Feature **130**)
When working with categorical data, it is important to convert labels into numerical format.

- **Label Encoding**: Assigning a unique integer to each category.
- **Ordinal Encoding**: Encoding data with an ordinal relationship (e.g., Low, Medium, High) using integers that represent order.

---

### 7. **Target Guided Ordinal Encoding** (Feature **131**)
**Target Guided Ordinal Encoding** encodes categorical variables based on their relationship with the target variable.

- Calculate the mean target value for each category.
- Sort categories based on their mean target value and assign an ordinal value.
- Useful for ordinal categories with an inherent order but also related to the target.
