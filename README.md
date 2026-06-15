# House_Prediction_ML
End-to-end Machine Learning application for predicting house prices using Random Forest Regression and Streamlit.
# 🏠 House Price Prediction

## Overview

This project predicts house prices using Machine Learning.

The model was trained using housing features such as:

- Lot Area
- Overall Condition
- Year Built
- Basement Area
- MS Zoning

Users can enter house details through an interactive interface and receive an estimated house price.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Random Forest Regressor
- GridSearchCV

---

## Model Performance

| Metric | Score |
|----------|----------|
| R² Score | 0.811 |
| MAE | $23,475 |
| RMSE | $38,061 |

---

## Features

- Interactive UI
- Real-time price prediction
- Hyperparameter tuning
- Prediction range estimation
- Model evaluation metrics

---

## Screenshots

### Home Page

![Home](screenshots/home_page.png)

### Prediction Output

![Prediction](screenshots/prediction_output.png)

---

## Run Locally

```bash
git clone <repo-link>
cd house-price-prediction-ml

pip install -r requirements.txt

streamlit run app.py
```
