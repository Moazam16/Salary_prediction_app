# 💼 Salary Prediction using Traditional Machine Learning

This project predicts a person's salary based on their **experience**, using traditional regression techniques.

## 📌 Project Overview

The goal of this project is to:

- Explore and preprocess a real-world dataset.
- Build multiple regression models.
- Evaluate and compare their performance.
- Deploy the best model in a **Streamlit web application**.
- Make the app accessible publicly via **Streamli**.

This project helped me gain hands-on experience with the **ML lifecycle** — from raw data to a deployed prediction app.

---

## Dataset

We used the **Salary Data Year of Experience** dataset from Kaggle:  
[View Dataset](https://www.kaggle.com/datasets/korpionn/salary-prediction-dataset)

**Features:**

- **Experience** (in years)
- **Salary** (target variable)

---

## Steps

### Data Exploration & Preprocessing

- Loaded the dataset and checked for missing values.
- Encoded categorical features (Education, Job Title).
- Scaled numerical features for better model performance.

### Model Building

Tested multiple models:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

### Model Evaluation

Used regression metrics:

- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score**

Example:
| Model | MAE | RMSE | R² Score |
|--------------------|-------|-------|----------|
| Linear Regression | 3000 | 4000 | 0.85 |
| XGBoost | 2000 | 2700 | 0.93 |

### Streamlit Deployment

- Built a user-friendly app where users can input:
  - Years of Experience
- Predicts salary instantly.

### 6️⃣ Hosting on Streamlit

- Hosted the Streamlit app for public access.
- Linked it in the GitHub repo.
