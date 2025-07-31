
# Ecommerce Spending Prediction

This project aims to predict yearly spending of e-commerce customers using data features related to their behavior on the website and mobile app. The workflow includes Exploratory Data Analysis (EDA), visualization, feature selection, linear regression modeling, and performance evaluation.
---
## Project Overview

**Goal:**  
To predict the annual amount spent by an e-commerce customer based on user activity and performance across platforms (mobile app & website).

---

## Project Workflow

### Task 1: Problem Framing & Overview
- Defined the scope of the problem and laid out the steps to be followed.
- Objective: Predict customer yearly spending.

### Task 2: Data Import & Inspection
- Loaded dataset using **Pandas**.
- Explored data using `info()`, `describe()`, and `head()` functions.
- Found no missing data.

### Task 3: Exploratory Data Analysis & Visualization
- Utilized **Seaborn** and **Matplotlib** for:
  - Pair plots of all features.
  - Regression plots for relationships with yearly spending.
  - Heatmap to observe correlations.

### Task 4: Feature Selection & Model Building
- Chose the most impactful features based on correlation analysis.
- Split the data into training and test sets (80/20 split).
- Trained a **Linear Regression** model using Scikit-learn.

### Task 5: Model Evaluation
- Calculated:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
- Assessed model fit using prediction vs. actual plots.

### Task 6: Residual Analysis
- Plotted residual distribution using Seaborn.
- Checked for normality using Q-Q plots and SciPy.

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---
# Kaggle Link: https://www.kaggle.com/code/elkholyjr/ecommerce-spending-prediction
---
## 📌 Insights & Notes
- Mobile app usage had stronger correlation with spending than website usage.
- Linear Regression provided reasonable error metrics and residuals distribution aligned with assumptions.
- Potential future improvements: try different regression models (Ridge, Lasso), feature engineering.
