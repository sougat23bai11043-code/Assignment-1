# Assignment-1
# Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective
To build a Multiple Linear Regression model that predicts medical insurance charges using customer and health-related information.

## Dataset
Medical Cost Personal Insurance Dataset

Kaggle Dataset:
https://www.kaggle.com/datasets/mirichoi0218/insurance

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Methodology
1. Load the dataset.
2. Display the first five records.
3. Identify numerical and categorical features.
4. Check for missing values.
5. Encode categorical variables.
6. Split the data into training and testing sets (80:20).
7. Train a Multiple Linear Regression model.
8. Predict insurance charges.
9. Evaluate the model using MAE, MSE, and R² Score.
10. Plot Actual vs Predicted values.

## Results
The model predicts insurance charges with reasonable accuracy. Performance is evaluated using MAE, MSE, and R² Score.

## Conclusion
Smoking status has the greatest impact on insurance charges. Age and BMI also influence insurance costs. Linear Regression provides a simple baseline model but may not capture complex non-linear relationships.
