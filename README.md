# 🚗 Toyota Corolla Price Prediction using Multiple Linear Regression

## 📌 Project Overview
This project predicts the selling price of Toyota Corolla cars using Multiple Linear Regression (MLR). The analysis includes data preprocessing, exploratory data analysis (EDA), feature selection, model building, performance evaluation, and regularization techniques such as Lasso and Ridge Regression.

The objective is to understand how different vehicle features influence the selling price and identify the most accurate regression model for prediction.

---

## 📂 Dataset
- **Dataset Name:** ToyotaCorolla - MLR.csv
- **Target Variable:** Price

### Features Used
- Age_08_04
- KM
- HP
- Automatic
- CC
- Doors
- Quarterly_Tax
- Weight
- Fuel_Type
- And other vehicle-related attributes

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Libraries
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 📊 Project Workflow

### 1. Import Libraries
Imported all required libraries for data manipulation, visualization, machine learning, and model evaluation.

### 2. Load Dataset
- Read the dataset
- Display dataset shape
- Check data types
- Identify missing values
- Check duplicate records
- Generate descriptive statistics

### 3. Data Preprocessing
- Encoded the categorical feature (**Fuel_Type**) using Label Encoding.
- Split the dataset into features (X) and target variable (y).
- Performed an 80:20 Train-Test Split.

### 4. Exploratory Data Analysis (EDA)
Created several visualizations:
- Correlation Heatmap
- Histograms
- Pairplots
- Boxplots for Outlier Detection

### 5. Model Building

#### Model 1
- Used all available features
- Trained using Multiple Linear Regression

#### Model 2
Selected important numerical features:
- Age_08_04
- KM
- HP
- Weight

#### Model 3
Optimized feature set:
- Age_08_04
- KM
- HP
- Automatic
- Weight
- Fuel_Type

---

## 📈 Model Evaluation

Each model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The results were compared to determine the best-performing regression model.

---

## 🔒 Regularization Techniques

To improve model stability and reduce overfitting, the following algorithms were implemented:

- Lasso Regression
- Ridge Regression

Both models were evaluated using:

- RMSE
- R² Score

---

## 📊 Results

The project compares:

- Model 1 (All Features)
- Model 2 (Selected Features)
- Model 3 (Optimized Features)
- Lasso Regression
- Ridge Regression

Performance comparison helps identify the model with the highest prediction accuracy and best generalization capability.

---

## 📁 Project Structure

```
Toyota-Corolla-MLR/
│
├── ToyotaCorolla - MLR.csv
├── mlr.py
└── README.md
```

---

## 🎯 Conclusion

This project successfully demonstrates the application of Multiple Linear Regression for predicting Toyota Corolla prices. The dataset was preprocessed, explored through visualizations, and used to build multiple regression models. Performance evaluation showed that the optimized feature model achieved a good balance between prediction accuracy and model simplicity. Additionally, Lasso and Ridge Regression improved model robustness by reducing overfitting. Overall, the project highlights how regression techniques can effectively estimate vehicle prices based on multiple influencing factors.

---

