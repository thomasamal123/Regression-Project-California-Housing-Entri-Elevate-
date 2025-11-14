# Regression Project – California Housing (ENtri Elevate)

## Project Overview
This project is part of the Entri Elevate program. The goal is to build and compare regression models to predict house prices using the California Housing dataset. The notebook includes all preprocessing steps, model training, evaluation, and a final comparison of model performance.

## Steps Included in the Project
1. Load the California Housing dataset  
2. Explore the dataset and understand each feature  
3. Check for missing values  
4. Check for skewness and apply log transformation to skewed features  
5. Split the dataset into training and testing sets  
6. Scale only the training data using StandardScaler and apply the same scaler to test data  
7. Train multiple regression models  
8. Evaluate models using MAE, MSE, RMSE, and R² score  
9. Check for overfitting using Train R² vs Test R²  
10. Compare all models and select the best one  

## Models Used
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  

## Evaluation Metrics
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

These metrics were used to measure how accurate each model was.

## Best Performing Model
The Random Forest Regressor gave the best performance.  
It had the highest Test R² score and the lowest error values.  
The model showed good generalization and did not overfit heavily.

## Project Files
- Jupyter Notebook (.ipynb)  
- README.md (this file)  
