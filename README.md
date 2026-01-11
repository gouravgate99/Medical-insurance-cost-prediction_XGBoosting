# Medical-insurance-cost-prediction_XGBoosting


This project predicts **medical insurance costs** using machine learning regression models.
The objective is to estimate insurance charges based on customer attributes such as age,
BMI, smoking status, and other encoded features.

---

##  Project Overview

Medical insurance pricing depends on multiple demographic and lifestyle factors.
This project applies **ensemble regression models** to learn complex non-linear
relationships and accurately predict insurance costs.

---

##  Models Used

- **Random Forest Regressor**
- **XGBoost Regressor**

These models were chosen due to their robustness, ability to handle nonlinearity,
and strong performance on tabular datasets.

---

##  Dataset Description

The dataset consists of numerical and encoded categorical features such as:

- Age
- BMI
- Smoking indicator
- Gender (encoded)
- Region (encoded)
- Other normalized numerical attributes

**Target Variable:**
- `charges` → Medical insurance cost (USD)

---

##  Technologies & Libraries

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn (for visualization)

---

##  Workflow

1. Data loading and exploration
2. Data preprocessing & feature encoding
3. Train-test split
4. Model training
5. Model evaluation
6. Insurance cost prediction for new input data

---

##  Model Training Example

```python
model.fit(X_train, y_train)
prediction = model.predict(input_data)
