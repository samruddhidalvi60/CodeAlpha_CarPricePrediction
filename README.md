# CodeAlpha_CarPricePrediction
This project aims to predict vehicle selling prices using Machine Learning regression algorithms
# Vehicle Price Prediction Using Machine Learning

## Project Overview
This project aims to predict vehicle selling prices using Machine Learning regression algorithms. It uses vehicle-related features such as present price, manufacturing year, kilometers driven, fuel type, transmission, and ownership details.

## Dataset
- Total Records: 299
- Total Columns: 9 (before feature engineering)
- Missing Values: 0
- Duplicate Records: 0

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Categorical Data Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Actual vs Predicted Visualization
10. Feature Importance Analysis
11. Model Saving and Testing

## Machine Learning Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.473 | 2.525 | 0.753 |
| Decision Tree | 1.149 | 2.132 | **0.824** |
| Random Forest | 1.523 | 3.716 | 0.464 |

**Best Model:** Decision Tree Regressor

**R² Score:** 0.824

## Key Findings
- Decision Tree Regressor achieved the best performance among the three evaluated models.
- Present Price was an important feature in predicting selling prices.
- Vehicle age and kilometers driven were also considered during prediction.
- The model was saved and successfully loaded using Joblib.

## Project Files
- `CodeAlpha_Car_Price_Prediction.ipynb` – Complete project implementation.
- `car_price_prediction_model.pkl` – Trained Decision Tree model.

## Conclusion
This project demonstrates how Machine Learning regression algorithms can be used to estimate vehicle selling prices. It provided practical experience in data preprocessing, exploratory data analysis, feature engineering, model evaluation, and prediction.

## Internship
CodeAlpha Data Science Internship – Task 3
