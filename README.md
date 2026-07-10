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
## Advance Task 1: News Topic Classifier Using BERT

**Dataset:** AG News Dataset (fancyzhx/ag_news — Hugging Face)

**Model Used:** bert-base-uncased (Fine-tuned)

**Methods Applied:** Tokenization, Transfer Learning,
Fine-tuning, Text Classification

**Categories:** World, Sports, Business, Science/Technology

**Key Findings:**
- BERT successfully classified news headlines into 4 categories
- Fine-tuning on 2000 samples gave strong accuracy and F1 score
- Model correctly identified Science, Sports, Business and World news
- Gradio interface allows live headline classification in the browser

**Deployment:** Gradio Web Interface

---

## Advance Task 2: End-to-End ML Pipeline with Scikit-learn

**Dataset:** Telco Customer Churn Dataset (IBM)

**Models Applied:**
- Logistic Regression Pipeline
- Random Forest Pipeline
- Random Forest + GridSearchCV (Tuned)

**Methods Applied:** Scikit-learn Pipeline API, 
Label Encoding, Feature Scaling, GridSearchCV, 
Joblib Export

**Key Findings:**
- GridSearchCV improved Random Forest performance
- Logistic Regression provided strong baseline accuracy
- Complete pipeline exported and reloaded successfully with joblib
- Scikit-learn Pipeline ensured clean, production-ready workflow

**Pipeline saved as:** churn_pipeline.pkl

---

## Advance Task 3: Multimodal ML – Housing Price Prediction Using Images + Tabular Data

**Dataset:** SoCal House Prices and Images Dataset (Kaggle)

**Models Applied:**
- MobileNetV2 (CNN) for Image Feature Extraction
- Deep Neural Network (DNN) for House Price Prediction

**Methods Applied:** CNN Feature Extraction, Multimodal Learning (Image + Tabular Data), Feature Fusion, StandardScaler, Train-Test Split, Regression Modeling, TensorFlow/Keras

**Key Findings:**
- MobileNetV2 successfully extracted high-level image features from house images.
- Combining image features with tabular features improved the house price prediction process.
- The Deep Neural Network learned from both visual and structured data simultaneously.
- Model performance was evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- The trained model was successfully saved for future predictions.

**Model saved as:** house_price_model.h5

---
