# 🏡 Airbnb Price Prediction (NYC)

This project predicts the **nightly price** of Airbnb listings in New York City using machine learning.  
It includes full **data preprocessing**, **exploratory data analysis (EDA)**, and a **final regression model** optimized for prediction.

---

## 📁 Project Contents

All files are included in a single directory — no subfolders:

| File Name                           | Description                                              |
|-------------------------------------|----------------------------------------------------------|
| `1-PreProcessing_AirBNB.ipynb`      | Data cleaning, transformation & feature engineering      |
| `2-Visualization_Analysis_AirBnb.ipynb` | EDA & visual analysis of key features vs. price       |
| `Machine_Learning_Modeling_Airbnb.ipynb` | Regression model training, evaluation & export       |
| `predict_with_model.ipynb`          | Load the trained model and make predictions              |
| `raw_airbnb_data.csv`               | Original dataset from NYC Airbnb listings                |
| `clean_airbnb_data.csv`             | Final cleaned & transformed dataset used for modeling    |
| `final_model.pkl`                   | Trained regression model (Polynomial Regression Degree=2) |

---

## 🧠 Project Summary

This is a **real-world regression project** aimed at:

- Predicting Airbnb nightly prices using listing features  
- Applying feature transformations (log, encoding, etc.)  
- Visualizing data distributions and correlations  
- Evaluating multiple models and selecting the best one  
- Saving the final model for real-time usage

---

## 📊 Final Model Overview

| Metric        | Value    |
|---------------|----------|
| **Model**     | Polynomial Regression (Degree = 2) |
| **RMSE**      | `0.3917` |
| **R² Score**  | `0.6184` |

✅ This model outperformed baseline and linear models, especially on non-linear patterns.

---

How to Use the Model for Prediction:
To make predictions on new Airbnb listings using the trained model:

 Option 1: Use predict_with_model.ipynb (Recommended)
📁 Simply open and run the notebook predict_with_model.ipynb step-by-step.
It includes all necessary code blocks to:

Load the trained model

Prepare and input sample data

Make predictions

Interpret the result

📌 Note: If you're using your own sample listing, replace the input values in the sample_input dictionary accordingly.

