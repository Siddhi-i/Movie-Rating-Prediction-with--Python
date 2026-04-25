![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# 🎬 Movie Rating Prediction

## 📌 About the Project
I worked on this project to understand how machine learning can be used to predict movie ratings based on different features like genre, director, and actors.

The goal was to build a model that can estimate the rating of a movie using historical data.

---

## 📊 Dataset
The dataset contains information about movies such as:
- Genre  
- Director  
- Actors  
- Rating (target variable)  

Some rows in the dataset were inconsistent or missing values, so preprocessing was required.

---

## ⚠️ Challenges Faced
- The dataset contained **missing values and noisy rows**  
- Some rows had incorrect formatting  
- Categorical data needed to be converted into numerical form  

---

## 🔄 What I Did

### 🧹 Data Cleaning
- Removed unnecessary columns  
- Dropped rows with missing values  
- Converted rating column to numeric format  
- Skipped invalid rows while loading the dataset  

---

### 🔤 Feature Encoding
- Converted categorical features (Genre, Director, Actor) into numbers using **Label Encoding**

---

### 🤖 Model Building
I trained two models:
- **Linear Regression**  
- **Random Forest Regressor**

---

## 📈 Model Evaluation
The models were evaluated using:

- **Mean Squared Error (MSE)** → Measures prediction error  
- (Optional) **R² Score** → Shows how well the model fits the data  

Random Forest performed better as it captured more complex patterns.

---

## 📊 Visualization
A scatter plot was created to compare:

### Actual vs Predicted Ratings
![Actual vs Predicted](actual_vs_predicted.png)

This helped visualize how close the predictions were to real values.

---

## 🧠 Key Learnings
- Real-world datasets are often messy and require cleaning  
- Categorical data must be encoded before training  
- Regression models are used for predicting continuous values  
- Random Forest can perform better than simple linear models  

---

## 🛠️ Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 🚀 Final Thoughts
This project helped me understand the complete workflow of a regression-based machine learning problem, from data cleaning to model evaluation.

---

## 📂 Dataset
The dataset is not included in this repository due to size.

👉 https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies  

After downloading:
- Place the CSV file in the project folder  
- Run the notebook  

---

## 👤 Author
Siddhi 

Open to feedback and suggestions 🙂
