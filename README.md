# 🌟 Interest Based Content Recommendation System (Regression Approach)

This project builds a **machine learning model** to predict a recommendation/engagement score for social media posts based on their features. The pipeline covers **EDA, feature engineering, outlier detection, encoding, model building, and evaluation**.  

The final model, a **Random Forest Regressor**, achieved an **R² score of 99.57%** on the test data.

---

## 📋 Project Overview

The workflow involves:
1. **Data Loading & Cleaning**: Handled missing values, categorical features, and outliers.
2. **Exploratory Data Analysis (EDA)**: Statistical summaries, feature distributions, and visualizations.
3. **Correlation Analysis**: Checked feature relationships with correlation heatmaps.
4. **Feature Engineering**: Encoded categorical variables, handled numerical transformations.
5. **Model Training**: Built a **Random Forest Regressor**.
6. **Evaluation**: Assessed model performance using **R² score**.

---

## 💾 Dataset Overview

The dataset consists of post, engagement and user-level features, including both categorical and numerical variables. These were preprocessed and encoded for training. 

---

## 🛠️ Methodology

### Exploratory Data Analysis
- Visualized feature distributions with histogram, boxplot, pie chart and scatterplot.
- Detected outliers and checked null values.
- Checked feature relationships with correlation heatmaps.

### Data Preprocessing
- Encoded categorical variables using suitable encoding strategies.
- Split dataset into **train (80%)** and **test (20%)** sets.

### Model Building
- Used **Random Forest Regressor** for prediction.
- Achieved an **R² score of 99.57%** on test data.

---

## 📈 Results

| Metric   | Score   |
|----------|---------|
| **R²**   | 99.57%  |

The Random Forest model shows an excellent fit on the dataset, explaining almost all variance in the target variable.

---

## 🔮 Possible Extensions
- Try **other regression models** like Gradient Boosting (XGBoost, LightGBM) and compare results.  
- Perform **hyperparameter tuning** using GridSearchCV/RandomizedSearchCV.  
- Test **feature importance** to understand which variables drive predictions.  
- Deploy the model with **Flask/Streamlit** for real-time recommendations.  

---
