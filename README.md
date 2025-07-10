# 📊 Bank Subscription Prediction

This project is part of the **Data Science Virtual Internship** by **SkillCraft Technology**. The task involved performing **Exploratory Data Analysis (EDA)** on a banking dataset to uncover insights and patterns related to customer subscription behavior.

---

## 🔍 Objective

The dataset contains information collected during direct marketing campaigns of a Portuguese banking institution. The goal was to understand which features influence whether a customer subscribes to a term deposit (`y` column).

---

## 🧠 Technologies Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Scikit-learn**

---

## 📁 Dataset Description

The dataset includes the following types of variables:

- **Demographic Data**: age, job, marital status, education
- **Economic Indicators**: balance
- **Campaign Features**: contact type, duration, number of contacts, etc.
- **Outcome Features**: poutcome, y (subscription)

---

## 🔎 Exploratory Data Analysis (EDA)

The EDA focused on:

- Missing value inspection
- Distribution of the target variable (`y`)
- Categorical feature distributions with respect to subscription
- Numerical feature histograms and correlation matrix
- Feature engineering (e.g., converting `pdays` into "contacted before")
- Label encoding of categorical variables

---

## 🌳 Model Training

A **Decision Tree Classifier** was trained using the preprocessed dataset with the following steps:

- Data split into training and test sets
- Model training on selected features
- Performance evaluation with classification report and confusion matrix
- Visualization of the decision tree structure

---

## 📈 Results

- Accuracy score and confusion matrix to measure model effectiveness
- Important patterns identified from categorical and numeric features
- Decision tree helps visualize branching decisions for predictions

---

## 📌 Folder Structure

bank-subscription-prediction/  
├── bank.csv  
├── models/  
│ ├── model.pkl  
│ └── encounters.pkl  
├── notebook/  
│ └── bank_analysis.ipynb  
├── README.md  

# # 🛠️ Future Development
The next goal is to build a Web Application that allows users to input customer data and get real-time predictions on whether they will subscribe to a term deposit — powered by the trained Decision Tree model.

Stay tuned!  

