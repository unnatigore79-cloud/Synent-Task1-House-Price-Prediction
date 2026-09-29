# 🏠 Task 1: House Price Prediction ML Model

**Company:** Synent Technologies  
**Domain:** Data Science / Machine Learning  
**Student Name:** Unnati Gore  

---

## 📌 Project Overview
This project predicts housing prices using Machine Learning techniques based on key socio-economic and geographical features. The project implements and compares two fundamental regression algorithms: **Linear Regression** and **Decision Tree Regressor**.

---

## 📊 Workflow & Methodology
1. **Data Acquisition:** Loaded the standard California Housing dataset via `scikit-learn`.
2. **Data Preprocessing & Splitting:** Divided data into 80% Training set and 20% Testing set (`train_test_split`).
3. **Model Training:** Built and trained Linear Regression and Decision Tree Regressor models.
4. **Performance Evaluation:** Evaluated using **Root Mean Squared Error (RMSE)** and **R² Accuracy Score**.
5. **Data Visualization:** Generated interactive comparison bar plots and actual-vs-predicted scatter charts using `Seaborn` & `Matplotlib`.

---

## 📈 Model Performance Comparison

| Model Name | RMSE Score (Lower is Better) | R² Accuracy Score |
| :--- | :---: | :---: |
| **Linear Regression** | ~0.745 | 57.58% |
| **Decision Tree Regressor** | **~0.703** | **62.21%** |

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Visualization:** Seaborn, Matplotlib
