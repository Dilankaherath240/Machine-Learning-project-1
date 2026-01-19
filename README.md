# 📊 Machine Learning Project – Power Plant Energy Prediction

## 🌟 Project Overview

This project implements and compares multiple machine learning models to predict the net hourly electrical energy output of a combined-cycle power plant. The dataset contains 9,568 samples collected over 6 years.

## 🚀 Features

- Multiple Algorithms: Linear Regression, Decision Trees, Random Forest, SVR  
- Cross-Validation: K-Fold validation for robust performance evaluation  
- Comparative Analysis: Direct comparison of different ML approaches  
- Full Implementation: Ready-to-run Jupyter notebooks  

## 🔧 Technologies Used

- Python 3.9  
- Scikit-learn – Machine learning algorithms  
- Pandas & NumPy – Data manipulation  
- Matplotlib & Seaborn – Data visualization  
- Jupyter Notebook – Interactive development  

## 📊 Dataset Features

The Combined Cycle Power Plant dataset contains 5 key features:

- AT – Ambient Temperature (°C)  
- V – Exhaust Vacuum (cm Hg)  
- AP – Ambient Pressure (millibar)  
- RH – Relative Humidity (%)  
- PE – Net Hourly Electrical Energy Output (MW) **(Target Variable)**  

## 🎯 Models Implemented

- Linear Regression – Baseline model  
- Decision Tree Regressor – Non-linear relationships  
- Support Vector Regressor (SVR) – High-dimensional spaces  
- Random Forest Regressor – Ensemble method  
- K-Fold Cross Validation – Model evaluation technique  

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher  
- Jupyter Notebook  
- Git  

## 📈 Model Performance

### Evaluation Metrics

- R² Score (Coefficient of Determination)  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

### Expected Results

- Random Forest typically achieves the highest accuracy  
- Linear Regression provides a strong baseline  
- SVR performs well with proper hyperparameter tuning  
- Decision Trees offer good interpretability  

## 🔍 Key Findings

- Feature Importance: Ambient Temperature (AT) is the most significant predictor  
- Model Performance: Random Forest consistently outperforms other models  
- Data Quality: High-quality dataset with minimal missing values  
- Practical Application: Models can help optimize power plant efficiency  

## 👤 Author

Dilanka Herath

## 📚 Credits

- Dataset: UCI Machine Learning Repository  
- Libraries: Scikit-learn, Pandas, NumPy  
