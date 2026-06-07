# House Price Prediction using Machine Learning

This project predicts house prices using Machine Learning algorithms by analyzing various housing features. The project compares the performance of multiple regression models including **Linear Regression**, **Decision Tree Regressor**, and **Random Forest Regressor** to identify the best-performing model.

---

## Project Overview

The goal of this project is to build a machine learning model that can predict house prices based on various house-related features such as size, number of rooms, condition, and other property characteristics.

Different regression algorithms were trained and evaluated to determine which model performs best on unseen data.

---

## Features

- Data preprocessing and feature selection
- Train-test split for model evaluation
- Feature scaling using `StandardScaler`
- Implementation of multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Performance evaluation using:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score

---

## Dataset

The dataset contains house-related information used to predict house prices.

### Selected Features
Some unnecessary columns were removed for better model performance:

- Price (Target Variable)
- House-related property features
- Removed columns:
  - Latitude
  - Longitude
  - Postal Code
  - Renovation Year
  - Date
  - ID

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models Used

### 1. Linear Regression
A baseline regression model used to establish a simple relationship between house features and prices.

**Result:**  
Performed reasonably well but struggled to capture complex relationships in the data.

---

### 2. Decision Tree Regressor
A tree-based model that learns non-linear patterns.

**Result:**  
Overfitted the training data and generalized poorly on test data.

---

### 3. Random Forest Regressor
An ensemble learning method that combines multiple decision trees.

**Result:**  
Performed best among all models by capturing complex relationships while reducing overfitting.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- **Mean Squared Error (MSE)** → Measures prediction error magnitude
- **Mean Absolute Error (MAE)** → Average absolute prediction error
- **R² Score** → Measures how well the model explains variance in house prices

---

## Best Performing Model

**Random Forest Regressor** achieved the best performance compared to Linear Regression and Decision Tree Regression due to better generalization and reduced overfitting.

---
## Installation

Clone the repository:

```bash
git clone https://github.com/machanikki2006-cpu/house-price-prediction.git
```
