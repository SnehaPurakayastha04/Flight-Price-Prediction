# Flight Price Prediction using Machine Learning

## Project Overview

This project predicts airline ticket prices using supervised machine learning techniques. Various flight-related attributes such as airline, source, destination, class, duration, number of stops, and days left before departure are used to estimate ticket prices.

The project includes data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## Features

- Data preprocessing and cleaning
- Missing value handling
- Exploratory Data Analysis (EDA)
- Outlier analysis
- Feature scaling and One-Hot Encoding
- Comparison of seven regression models
- Hyperparameter tuning using RandomizedSearchCV
- Kaggle submission file generation

---

## Dataset

Dataset Source:
Kaggle – Flight Price Prediction Dataset

Target Variable:
- Price

Features:
- Airline
- Source
- Destination
- Class
- Departure Time
- Arrival Time
- Duration
- Stops
- Days Left

---

## Machine Learning Models

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor

Hyperparameter tuning was performed on:

- Random Forest
- Extra Trees
- Gradient Boosting

---

## Best Model

Random Forest Regressor (Tuned)

Performance:

- R² Score: **0.9767**
- RMSE: **3466.19**
- MAE: **1704.84**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Kaggle

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning
9. Final Prediction
10. Kaggle Submission

---

## Repository Structure

```
Flight_Price_Prediction.ipynb
README.md
images/
```

---

## Future Improvements

- XGBoost implementation
- LightGBM implementation
- CatBoost implementation
- Feature importance visualization
- Model deployment using Flask/FastAPI

---

## Author

Sneha Purakayastha
