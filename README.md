# 🏥 Medical Insurance Cost Prediction

Predicting healthcare costs is a crucial component for insurance companies, hospitals, and government agencies. This project leverages machine learning techniques to **accurately estimate medical insurance charges** based on demographic and health-related attributes.

> 📌 **Goal:** Build a predictive model that estimates insurance charges using regression techniques and evaluate the performance of different algorithms.

---

## 🧠 Why This Project Matters

With rising healthcare expenses, insurance providers need reliable models to forecast medical costs and reduce financial risk. This project simulates a real-world problem where data scientists help insurers make **data-driven pricing decisions**.

---

## 🚀 Project Highlights

- 🔍 Performed **in-depth EDA** and **feature engineering**
- 🔄 Built a **scalable preprocessing pipeline** using `ColumnTransformer` & `Pipeline`
- 🧠 Trained **5 regression models**, including:
  - Polynomial Regression
  - Decision Tree
  - K-Nearest Neighbors
  - Random Forest
- 📈 Compared models using **R², MAE, MSE**
- 🏆 Identified **Random Forest** & **Polynomial Regression (degree 2)** as top performers

---

## 🧰 Tech Stack / Tools Used

| Category         | Tools & Libraries        |
|------------------|--------------------------|
| Language         | Python                   |
| Data Handling    | pandas, numpy            |
| Visualization    | seaborn, matplotlib      |
| Modeling         | scikit-learn             |
| Preprocessing    | Pipeline, ColumnTransformer, OneHotEncoder |
| Evaluation       | r2_score, MAE, MSE       |

---

## 📁 Dataset

The dataset used is `insurance.csv`, which includes the following features:
- `age`: Age of primary beneficiary
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of dependents covered by insurance
- `smoker`: Smoking status
- `region`: Residential area in the US
- `charges`: Medical insurance cost (target variable)

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for null values
- Visualized distributions of categorical and numerical features
- Calculated average values for key numeric features

---

## 🛠️ Data Preprocessing

- Handled missing values using `SimpleImputer`
- Scaled numeric features using `StandardScaler`
- Encoded categorical features using `OneHotEncoder`
- Combined transformations with `ColumnTransformer`

---

## 🔍 Models Used

| Model                            | Description                               |
|----------------------------------|-------------------------------------------|
| Linear Regression                | Baseline model                            |
| Polynomial Regression (Degree 1–4) | Captures non-linear relationships       |
| Decision Tree Regression         | Explored various max depths               |
| K-Nearest Neighbors (KNN)        | Used with `k=5`                           |
| Random Forest Regression         | Used with 100 trees                       |

---

## 📈 Performance Snapshot

| Model                          | R² Score | MAE     | MSE        |
|-------------------------------|----------|---------|------------|
| Polynomial Regression (deg 2) | **0.87** | 2753.25 | 20.6M      |
| Random Forest Regression      | **0.86** | 2562.44 | 21.3M      |
| Decision Tree (MaxDepth=4)    | 0.86     | 2698.97 | 21.0M      |
| K-Nearest Neighbors           | 0.77     | 3630.80 | 35.9M      |

---

## ✅ Key Skills Demonstrated

- Data preprocessing & cleaning  
- Feature scaling & encoding  
- Regression modeling & tuning  
- Evaluation metrics interpretation  
- Visual storytelling with data  
- Building end-to-end ML pipelines  

---

## 📊 Visualizations

- Feature distributions using seaborn  
- Bar chart comparing model accuracies  

---

## 📂 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/vall9133/medical-insurance-prediction.git
cd medical-insurance-prediction

2.Open the notebook:
jupyter notebook Project_ML.ipynb
3.Run the notebook cells
You will see:
Data preprocessing steps
Visualizations for feature distributions
Training and evaluation of multiple regression models
Final comparison of model performances
