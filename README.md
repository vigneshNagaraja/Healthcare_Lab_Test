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

##  Reflection on the Problem-Solving Process

The main challenge in this project was the absence of a direct 'exercise level' variable. To address this, we created a synthetic `Exercise_Level` feature by mapping BMI categories to approximate physical activity levels. This step required thoughtful consideration and domain logic.

Next, we handled missing values, which caused an error during model training. We resolved this by imputing the mode for the `Exercise_Level` column, which preserved the dataset's structure while avoiding bias.

Training the linear regression model was straightforward. The evaluation using MSE showed that while the model has some predictive power, real-world weight prediction likely needs additional variables (e.g., sleep, diet, genetics) to be more accurate. 

Overall, this process deepened our understanding of data preprocessing, feature engineering, and model evaluation using a healthcare dataset.
a.

##  Files
- `Lab_Test.ipynb`: Jupyter Notebook with full analysis
- `bmi.csv`: Dataset used
- `README.md`: This file


