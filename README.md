# 🩺 Diabetes Prediction Using Logistic Regression

This project implements a machine learning model using **Logistic Regression** to predict whether a patient has diabetes. The model is trained on the PIMA Indian Diabetes dataset and includes steps like data cleaning, training, evaluation using confusion matrix, classification report — all within a Jupyter Notebook / Google Colab environment.

---

## 🚀 Features

- 🔍 Data Preprocessing & Cleaning
- 📈 Logistic Regression Model Implementation
- 📊 Evaluation using:
  - Confusion Matrix
  - Classification Report
- 📉 Train/Test Split (75/25)
- 🧼 Handles non-numeric values safely

---

## 🧠 Dataset

- **Dataset Used**: PIMA Indian Diabetes Dataset
- **Source**: Often available from `diabetes.csv` in ML repositories
- **Features**:
  - `glucose`: Plasma glucose concentration
  - `bp`: Blood pressure (mm Hg)
  - `skin`: Triceps skinfold thickness (mm)
  - `insulin`: 2-Hour serum insulin (mu U/ml)
  - `bmi`: Body mass index
  - `pedigree`: Diabetes pedigree function
  - `age`: Age (years)
  - `outcome`: 0 or 1 (Non-diabetic or Diabetic)

---

## 🛠️ Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy`
  - `scikit-learn` for ML
  - `matplotlib`, `seaborn` for visualization

---

## 📈 Evaluation Metrics

- **Confusion Matrix** (with heatmap)
- **Classification Report**
  - Precision, Recall, F1-score

These metrics help in understanding model performance and reliability.

---

## 📂 How to Run

> This notebook is intended to be run on **Google Colab** or Jupyter Notebook.

1. Clone the repository:
   ```bash
   git clone https://github.com/AmbreenGulfraz09/diabetes-logistic-regression.git
   cd diabetes-logistic-regression
