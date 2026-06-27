# 🏠 House Price Prediction using Machine Learning

A complete Machine Learning project that predicts California house prices using multiple regression algorithms and compares their performance.

---

## 📌 Overview

This project demonstrates an end-to-end Machine Learning regression workflow using the California Housing dataset.

The notebook includes:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training
- Model Evaluation
- Model Comparison
- Feature Importance Visualization

---

## 📂 Dataset

California Housing Dataset

Loaded directly from Scikit-learn

```python
from sklearn.datasets import fetch_california_housing
```

Target Variable

- Median House Value

Features

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## 🤖 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🏆 Model Comparison

| Model | RMSE | R² Score |
|--------|------|----------|
| Linear Regression | xx | xx |
| Decision Tree | xx | xx |
| Random Forest | xx | xx |

Best Performing Model

✅ Random Forest Regressor

---

## 📈 Feature Importance

Random Forest identifies the most important features affecting house prices.

Top Features include:

- Median Income
- Average Occupancy
- Latitude
- Longitude

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/house-price-prediction-ml.git

cd house-price-prediction-ml

pip install -r requirements.txt
```

---

## ▶ Run

```bash
jupyter notebook day19.ipynb
```

---

## 📁 Repository Structure

```
house-price-prediction-ml/
│
├── README.md
├── requirements.txt
├── day19.ipynb
├── images/
└── model/
```

---

## 💡 Future Improvements

- Hyperparameter Tuning
- XGBoost
- Gradient Boosting
- SHAP Explainability
- Streamlit Dashboard
- Flask API
- Docker Deployment

---

## 👩‍💻 Author

**Maheen Akther**

AI & Data Science Student
