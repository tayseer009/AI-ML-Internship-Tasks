# AI/ML Internship Tasks — DevelopersHub

## Task 1: Iris Dataset Exploration
**Dataset:** Iris Dataset (loaded via seaborn)

**Models/Methods Applied:** Descriptive statistics, scatter plots, histograms, box plots

**Key Findings:**
- Setosa is linearly separable from other species
- Petal length is the strongest distinguishing feature
- No missing values in the dataset

---

## Task 2: Predict Future Stock Prices (Short-Term)

**Dataset:** Apple (AAPL) stock data from Yahoo Finance via yfinance library (2020–2024)

**Models Applied:**
- Linear Regression
- Random Forest Regressor

**Key Findings:**
- Used Open, High, Low, and Volume to predict next day's Close price
- Both models achieved R² score of ~0.99
- Random Forest handles non-linear patterns better than Linear Regression
- Short-term stock prediction is highly accurate due to price continuity

---

## Task 3: Heart Disease Prediction

**Dataset:** Heart Disease UCI Dataset (heart.csv) from Kaggle — 303 patients, 13 features

**Models Applied:**
- Logistic Regression
- Decision Tree Classifier

**Key Findings:**
- No missing values found in the dataset
- Logistic Regression accuracy: ~85%, Decision Tree: ~80%
- Logistic Regression had higher ROC-AUC score — better overall model
- Top features predicting heart disease: chest pain type (cp), max heart rate (thalach), ST depression (oldpeak)

---

## Task 4:House Price Prediction

**Dataset:** House Price Prediction Dataset (Kaggle — Housing.csv)

**Models Applied:**
- Linear Regression
- Gradient Boosting Regressor

**Key Findings:**
- Gradient Boosting outperformed Linear Regression with lower MAE and RMSE
- Area and number of bathrooms were the strongest predictors of house price
- Categorical features like air conditioning and preferred area also significantly impacted price
- Feature scaling improved model performance for Linear Regression

---
