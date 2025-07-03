# Healthcare_Lab_Test

#  Weight Prediction Using Linear Regression

This project aims to predict an individual's weight based on age, height, and exercise level using a linear regression model.

## Dataset
- Source: [Kaggle - Age, Height, Weight, BMI Dataset](https://www.kaggle.com/datasets/rukenmissonnier/age-weight-height-bmi-analysis)
- Used fields: Age, Height, BMI Class → Exercise_Level
- Target: Weight

##  ML Approach
- Linear Regression (Supervised Learning)
- Features: Age, Height, Exercise_Level (ordinal from BMI category)
- Target: Weight (kg)

##  Preprocessing
- BMI Class mapped to Exercise Level (Low = 1, Medium = 2, High = 3)
- Missing values filled using mode
- Dataset split 80/20 for training/testing

##  Evaluation
- Metric: Mean Squared Error (MSE)
- Result: **MSE ≈ 190.75**

##  Reflection
This project demonstrates how lifestyle and demographic indicators can be used to predict health metrics like weight. The results highlight that while linear regression provides a simple and interpretable model, accuracy could improve with more features like diet, sleep, or activity tracker data.

##  Files
- `Lab_Test.ipynb`: Jupyter Notebook with full analysis
- `bmi.csv`: Dataset used
- `README.md`: This file


