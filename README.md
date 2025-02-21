# **Delhi House Price Prediction** 
This is my **Machine Learning project** for predicting house prices in **Delhi**, trained on real estate data from **Magic Bricks (Kaggle)**. I explored multiple regression models to find the best one for price prediction, with **XGBoost achieving the highest accuracy**.  

## **🔹 Features**  
- **Dataset**: Delhi housing data from Kaggle (Magic Bricks).  
- **Models Implemented**:  
  - Linear Regression  
  - Ridge Regression  
  - Lasso Regression  
  - Gradient Boosting  
  - XGBoost (**Best performing model**)  
- **Evaluation Metrics**: MAE, MSE, R² Score  
- **Visualization**: Actual vs. Predicted Prices scatter plots  

## **🔹 Results**  
| Model                 | MAE  | MSE   | R² Score  |  
|----------------------|------|------|----------|  
| **Linear Regression**  | 0.0975  | 0.0170  | 0.954  |  
| **Lasso Regression**   | 0.2485  | 0.1014  | 0.726  |  
| **Ridge Regression**   | 0.0975  | 0.0170  | 0.954  |  
| **Gradient Boosting**  | 0.0242  | 0.0011  | 0.997  |  
| **XGBoost (Best)**  | **0.0127**  | **0.0007**  | **0.998**  |  

## **🔹 Future Plans :** 
I will to deploy this project as a web application so users can input property details and get price predictions instantly. The deployment will likely be done using Flask or FastAPI for the backend and a simple React.js frontend.
