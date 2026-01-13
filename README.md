# House Price Prediction — Machine Learning Project

## Project Overview
This project aims to predict house prices using regression techniques.  
We used the **California Housing Dataset** and applied both **Linear Regression** and **Random Forest Regression** to model the data.

---

## Dataset
- Source: [California Housing Dataset (scikit-learn)](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)
- Rows: 20640
- Columns: 9 features + 1 target (`MedHouseVal`)
- Features: 
  - MedInc: median income
  - HouseAge: median house age
  - AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
- Target: Median House Value (`MedHouseVal`)

---

## Exploratory Data Analysis (EDA)
- Checked first few rows with `df.head()`
- Dataset info and statistics with `df.info()` and `df.describe()`
- Checked target distribution (histogram)
- Checked missing values (none)
- Correlation analysis (heatmap) to understand feature relationships

---

## Feature Engineering
- No missing values in this dataset
- Input features (`X`) separated from target (`y`)
- Train-test split: 80% training, 20% testing

---

## Models Used

### 1. Linear Regression
- Simple linear model
- Fit on training data
- Predictions on test data
- Evaluation:
  - MSE = XXX
  - R² = XXX

### 2. Random Forest Regression
- Ensemble method
- Handles non-linear relationships
- Predictions on test data
- Evaluation:
  - MSE = XXX
  - R² = XXX

---

## Evaluation
| Model              | MSE     | R² Score |
|------------------|---------|---------|
| Linear Regression | XXX     | 0.5    |
| Random Forest     | XXX     | 0.8    |

> Random Forest performed better than Linear Regression as it captured non-linear patterns and achieved higher R².

---

## Conclusion
- Random Forest is more effective for predicting house prices in this dataset
- Model can be used for further experimentation, hyperparameter tuning, or feature selection
- Good first regression project for ML portfolio

---

