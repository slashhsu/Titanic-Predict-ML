# Titanic Survival Prediction using Machine Learning

## Overview
The **Titanic dataset** provides a comprehensive set of information about passengers, including **age, gender, ticket class, cabin, and embarkation point**. The dataset also includes a **binary survival indicator** (1 for survived, 0 for not survived), making it an ideal case study for predictive modeling.

This project employs two powerful ensemble learning methods: **Random Forest (RF)** and **Decision Tree (DT)** models. 
- **Random Forest (RF)** combines multiple Decision Trees to improve accuracy and robustness using ensemble learning.
- **Decision Tree (DT)** constructs tree-based models based on hierarchical decision rules for easy interpretation.

Both models provide valuable insights into the factors influencing **survival outcomes**, helping us identify key attributes that played a role in passenger survival.

![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/5a94e054-e004-4f70-b250-f5770b07f555)

---

## Objectives
✅ **Preprocess and explore the Titanic dataset**  
✅ **Train Decision Tree and Random Forest models for survival prediction**  
✅ **Analyze key features impacting survival rates**  
✅ **Visualize survival probabilities and feature importance**  
✅ **Evaluate model performance using classification metrics**  

---

## Dataset
The dataset consists of the following key attributes:
- **PassengerID** – Unique identifier for each passenger.
- **Pclass** – Ticket class (1st, 2nd, or 3rd class).
- **Sex** – Gender of the passenger.
- **Age** – Age of the passenger.
- **SibSp** – Number of siblings/spouses aboard.
- **Parch** – Number of parents/children aboard.
- **Ticket** – Ticket number.
- **Fare** – Price paid for the ticket.
- **Cabin** – Cabin number (if available).
- **Embarked** – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **Survived** – Survival status (1 = Survived, 0 = Did not survive).

---

## Implementation
### **Technologies Used**
- **Python** – Data preprocessing, model training, and evaluation.
- **Pandas & NumPy** – Data manipulation and transformation.
- **Matplotlib & Seaborn** – Data visualization and feature analysis.
- **Scikit-Learn** – Machine learning model implementation.

### **Code Workflow**
#### **1. Data Preprocessing**
- Handle missing values using median imputation for Age.
- Convert categorical variables (Sex, Embarked) into numerical format.
- Normalize numerical features (Fare, Age) for improved model performance.

#### **2. Model Training & Evaluation**
- Train **Decision Tree and Random Forest models**.
- Split data into training and testing sets (**80/20 split**).
- Evaluate model performance using **accuracy, precision, recall, and F1-score**.
- Analyze **feature importance** to determine survival predictors.

#### **3. Data Visualization**
- Generate **heatmaps** to analyze correlations.
- Plot **survival rates based on ticket class, age, and gender**.
- Visualize **feature importance rankings**.

---

## Visualizations
![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/50e226ba-e64b-4eca-b7e3-57a14c42718e)
![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/1a598f57-255d-4c1d-96c0-03eff4164f07)
![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/3cc241f2-7311-42e7-b528-c04e170e7ac2)
![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/788c5439-039c-483c-8c3d-0216eca141fd)
![image](https://github.com/slashhsu/Titanic-Predict-ML/assets/137000188/08e529c6-b02e-490d-bba6-9cb12ed59963)

---

## Results & Insights
📌 **Random Forest outperforms Decision Tree in accuracy due to its ability to reduce overfitting.**  
📌 **Gender (Sex), Ticket Class (Pclass), and Fare are key predictors of survival.**  
📌 **First-class passengers had a higher survival rate, while third-class passengers had the lowest.**  
📌 **Women and children had a significantly higher chance of survival.**  



