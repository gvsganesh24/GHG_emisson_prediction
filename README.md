# GHG Emission Prediction using Machine Learning

## 📌 Project Overview

This project predicts **Greenhouse Gas (GHG) emission factors** for different industries and commodities using machine learning models.
The goal is to analyze supply chain emission data and build predictive models that estimate emission factors based on multiple attributes.

The project performs **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling** to achieve accurate predictions.

---

## 📊 Dataset

The dataset used in this project contains **Supply Chain Emission Factors for US Industries and Commodities**.

It includes information such as:

* Commodity / Industry code
* Substance type (CO₂, methane, nitrous oxide, other GHGs)
* Emission factors with and without margins
* Data quality scores
* Source type (Commodity or Industry)
* Year

The dataset was processed and combined across multiple years to create a unified dataset. 

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib
* Joblib

---

## 🔎 Project Workflow

1. Data Loading from Excel sheets
2. Data Cleaning and Preprocessing
3. Feature Encoding and Scaling
4. Exploratory Data Analysis (EDA)
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. Model Saving

---

## 🤖 Machine Learning Models

The following models were used:

* Linear Regression
* Random Forest Regressor
* Tuned Random Forest using GridSearchCV

---

## 📈 Model Performance

| Model               | RMSE    | R² Score |
| ------------------- | ------- | -------- |
| Random Forest       | 0.0061  | 0.9993   |
| Linear Regression   | 0.00028 | 0.9999   |
| Tuned Random Forest | 0.0059  | 0.99937  |

Linear Regression achieved the best performance on the dataset.

---

## 📂 Project Structure

```
GHG_emisson_prediction
│
├── green_house_gas_emission.ipynb
├── models
│   ├── LR_model.pkl
│   └── scaler.pkl
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/gvsganesh24/GHG_emisson_prediction.git
```

2. Install dependencies

```
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

3. Run the notebook

```
green_house_gas_emission.ipynb
```

---

## 📌 Future Improvements

* Deploy the model using **Streamlit**
* Add **interactive dashboards**
* Extend prediction to **real-time emission analysis**

---

## 👨‍💻 Author

Ganesh
Machine Learning & Data Science Enthusiast
