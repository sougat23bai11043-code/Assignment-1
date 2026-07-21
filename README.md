# Assignment-1
## Medical Insurance Cost Prediction using Multiple Linear Regression

##  Project Overview

This project develops a **Multiple Linear Regression** model to predict **medical insurance charges** based on customer demographic and health-related information. The model helps estimate insurance costs using machine learning techniques.

---

## Objective

The objective of this project is to:

- Predict medical insurance charges using Multiple Linear Regression.
- Perform data preprocessing and feature encoding.
- Evaluate the model using standard regression metrics.
- Visualize the relationship between actual and predicted insurance charges.

---

##  Dataset

**Dataset:** Medical Cost Personal Insurance Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## 🛠️Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Features Used

| Feature | Description |
|----------|-------------|
| Age | Age of the customer |
| Sex | Gender |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoker | Smoking status |
| Region | Residential region |

**Target Variable**

- Charges (Medical Insurance Cost)

---

##  Project Workflow

### 1. Data Understanding
- Loaded the dataset using Pandas.
- Displayed the first five records.
- Identified numerical and categorical features.
- Selected the target variable.

### 2. Data Preprocessing
- Checked for missing values.
- Encoded categorical variables using LabelEncoder.
- Split the dataset into 80% training and 20% testing data.

### 3. Model Development
- Built a Multiple Linear Regression model.
- Trained the model using the training dataset.
- Predicted insurance charges for the testing dataset.

### 4. Model Evaluation
The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

An **Actual vs Predicted** scatter plot was generated to visualize model performance.

---

##  Results

The model successfully predicts medical insurance charges with reasonable accuracy.

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The scatter plot demonstrates a positive relationship between actual and predicted values.

---

##  Conclusion

This project demonstrates the application of Multiple Linear Regression for predicting medical insurance charges. The analysis indicates that **smoking status**, **age**, and **BMI** are among the most influential factors affecting insurance costs.

Although Linear Regression provides a simple and interpretable model, it assumes a linear relationship between features and the target variable. More advanced machine learning algorithms such as Random Forest or XGBoost may improve prediction accuracy.

---

## Repository Structure

```
Assignment-1/
│
├── Assignment-1.ipynb
├── insurance.csv
└── README.md
```

---

##  Author

**Name:** Sougat Das

**Course:** AI & Machine Learning

**Assignment:** Assignment–1

**Topic:** Medical Insurance Cost Prediction using Multiple Linear Regression
