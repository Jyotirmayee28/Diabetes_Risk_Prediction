# 🩺 Diabetes Risk Prediction

🚀 Machine Learning System for Diabetes Risk Prediction

---

## 📜 Project Overview

The **Diabetes Risk Prediction System** is a Machine Learning-based solution designed to predict whether a person is likely to have diabetes based on various health-related parameters. The system analyzes medical attributes such as **Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Age, and other relevant features** to generate a diabetes prediction.

The project uses **Exploratory Data Analysis (EDA)** to understand relationships between health indicators and diabetes outcomes. Data preprocessing is performed by identifying invalid zero values and replacing them with appropriate mean values before training the Machine Learning model.

A **Logistic Regression** classification model is trained and evaluated using a stratified train-test split. The system also uses a confusion matrix and accuracy score to assess prediction performance and demonstrates predictions on sample patient data.

---

## 🎯 Key Features

✅ Diabetes risk prediction using Machine Learning 🧠  
✅ Exploratory Data Analysis of health-related attributes 📊  
✅ Correlation analysis using heatmaps 🔥  
✅ Pairwise feature analysis using visualizations 📈  
✅ Handling of invalid zero values and missing data 🧹  
✅ Logistic Regression-based classification 🤖  
✅ Confusion matrix for model evaluation 📋  
✅ Prediction on new patient health data 🩺  

---

## 🛠️ Tech Stack

- **Programming Language**: Python 🐍
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Algorithm**: Logistic Regression
- **Data Processing**: Missing Value Handling, Feature Analysis
- **Model Evaluation**: Accuracy Score, Confusion Matrix
- **Dataset**: Diabetes Dataset (diabetes.csv)

---

## 🖥️ How It Works

1️⃣ **Load Dataset:** Import the diabetes dataset using Pandas and examine its structure, dimensions, statistics, and data types.

2️⃣ **Data Analysis:** Perform EDA using count plots, pair plots, and correlation heatmaps to understand the relationship between different health parameters and diabetes outcomes.

3️⃣ **Data Preprocessing:** Identify invalid zero values in features such as Glucose, Blood Pressure, Skin Thickness, Insulin, and BMI and replace them with NaN values.

4️⃣ **Handle Missing Values:** Replace the identified missing values with the corresponding feature mean to prepare the dataset for model training.

5️⃣ **Train Model:** Separate the input features and target variable (`Outcome`) and train a Logistic Regression classifier using an 80/20 stratified train-test split.

6️⃣ **Evaluate Model:** Generate predictions on the test dataset and evaluate the model using a confusion matrix and accuracy score.

7️⃣ **Predict New Cases:** Provide health-related input values for a new individual and use the trained model to predict whether the person is **Diabetic** or **Non-Diabetic**.
