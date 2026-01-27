# California Housing Price Prediction
End-to-End Machine Learning Regression Project
# 📌 Project Overview

This project predicts median house prices in California using advanced regression techniques.
Beyond prediction, it provides data-driven insights into the key economic, geographical, and housing factors that influence real estate prices.

The project demonstrates a complete, production-ready machine learning workflow, from data exploration to model tuning and explainability.

# Business Objectives

Predict house prices accurately across California regions

Identify the most influential pricing drivers

Support real estate investment and urban planning decisions

Build an interpretable and robust regression pipeline

# Dataset

Source: Scikit-learn California Housing Dataset

Rows: 20,640

Target Variable: MedHouseVal (Median House Value)

Features include:

Median Income (MedInc)

House Age (HouseAge)

Rooms, Bedrooms, Population, Occupancy

Latitude & Longitude (geographical context)

# Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

# Project Structure

CALIFORNIA-HOUSING-PREDICTION/

├── data/

│   └── california_housing_processed.csv

├── California_Housing_Price_Intelligence.ipynb

├── California_Housing_Model_Training.ipynb

├── California_Housing_Explainability.ipynb

├── README.md


# Exploratory Data Analysis (EDA)

Key analyses performed:

Target variable distribution analysis

Feature correlation heatmap

Income vs house price relationships

Geographical price distribution

Skewness and density patterns

# 📌 Key Insight

Median income and coastal proximity strongly influence house prices.

# 🧩 Feature Engineering

Business-driven features were created to capture housing dynamics:

RoomsPerHousehold → Comfort & luxury indicator

BedroomsRatio → Space efficiency

PopulationPerHousehold → Congestion measure

IncomeCategory → Market segmentation (Low → Very High)

One-hot encoding for categorical variables

# Model Training & Evaluation
Models Trained:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Cross-Validation:

5-fold cross-validation used to ensure model stability

Hyperparameter Tuning:

GridSearchCV applied to Random Forest for optimal performance

# 📈 Model Comparison

| Model             | R² Score  | RMSE      |
| ----------------- | --------- | --------- |
| Linear Regression | 0.655     | 0.673     |
| Random Forest     | **0.806** | **0.504** |
| Gradient Boosting | 0.779     | 0.538     |

Final Model: Random Forest Regressor

Chosen for its:

Strong predictive performance

Ability to capture non-linear patterns

Robustness across cross-validation folds

#  Model Explainability

Feature importance analysis

Prediction error distribution

Geographical visualization of predicted prices

# Key Drivers of House Prices

Median income

Coastal location (Latitude & Longitude)

Housing density & room distribution

# Business Recommendations

Investors should prioritize high-income coastal regions

Urban planners can monitor congestion using density metrics

Developers can design housing based on room efficiency insights

# Conclusion

This project demonstrates:

A complete regression ML lifecycle

Strong alignment between data science and business insights

Real-world applicability in real estate and investment domains

👩‍💻 Author

Aqsa Abbasi
Machine Learning | AI
Actively transitioning into applied  AI roles