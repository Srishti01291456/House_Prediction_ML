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

<img width="802" height="562" alt="image" src="https://github.com/user-attachments/assets/da87694d-073e-40e4-b9b3-35bc0bce0f3c" />


### Prediction Output

<img width="802" height="525" alt="image" src="https://github.com/user-attachments/assets/4034ba46-ed05-42d3-b28a-9c6065f13d6d" />


---

## Run Locally

```bash
git clone <repo-link>
cd house-price-prediction-ml

pip install -r requirements.txt

streamlit run app.py
```
