# Titanic Fare Prediction Lab

This project focuses on using regression models to predict Titanic passenger fares based on various input features. The lab involves training, evaluating, and comparing different regression techniques.

## Objectives

- Build and evaluate regression models using Titanic data  
- Test different combinations of input features  
- Explore the effect of model complexity and regularization  
- Visualize polynomial fits and compare performance

## Tools & Libraries

- Python  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib

## Models Used

- Linear Regression  
- Ridge Regression  
- ElasticNet  
- Polynomial Regression (Degree 3 and Degree 6)

## Key Takeaways

- **Passenger class** (`pclass`) was the most useful feature for predicting fare  
- **ElasticNet** and **Polynomial Regression** had the best performance overall  
- Higher-degree polynomials added complexity without much benefit  
- Prediction was more accurate for well-distributed features and less extreme values

## Reflections

This lab reinforced how feature choice, model type, and outliers impact performance. Polynomial regression captured non-linear trends, and regularization helped manage complexity.
