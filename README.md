# 🏠 House Price Prediction using Regression Models

This project is part of the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).  
We aim to predict the final price of residential homes using machine learning models.

---

## 📁 Project Structure

| Notebook | Branch | Description |
|----------|--------|-------------|
| `data_loading.ipynb` | `data-loading` | Load and explore the training & test datasets |
| `data_cleaning.ipynb` | `data-cleaning` | Handle missing values, clean inconsistent data |
| `feature_engineering.ipynb` | `feature-engineering` | Create meaningful new features & encode categories |
| `model_random_forest.ipynb` | `model-random-forest` | Use Random Forest model for better performance |
| `submission_rf.csv` | `model-random-forest` | Final predictions submitted to Kaggle |

---

## 📊 Dataset Description

Files used from Kaggle:
- `train.csv`: Training dataset with house prices
- `test.csv`: Test dataset without prices
- `data_description.txt`: Explanation of each feature
- `sample_submission.csv`: Format reference for submission

---

## 🔁 Workflow Summary

1. **Load** data from `train.csv` and `test.csv`
2. **Clean** the dataset (handle missing values, drop irrelevant features)
3. **Engineer** features to enhance model accuracy
4. **Train Models**:
   - Random Forest 
5. **Predict** house prices for test set
6. **Submit** results to Kaggle (`submission_rf.csv`)

---

## 📌 Models Used

| Model | Description |
|-------|-------------|
| Linear Regression | Simple baseline model |
| Random Forest Regressor | Tree-based ensemble model for improved performance |

---

## 🧠 What You Learn

- Real-world regression problem solving
- Data cleaning and feature engineering
- Model training and evaluation
- Kaggle submission workflow

---

## 🚀 How to Run This Project

1. Clone this repo:
   ```bash
   git clone https://github.com/Ritik-19-12/House-Price-Prediction.git
   cd House-Price-Prediction
