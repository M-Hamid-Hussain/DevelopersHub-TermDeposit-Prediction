# Term Deposit Subscription Prediction

## Project Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on data collected from marketing campaigns. The objective is to build and evaluate machine learning models that can assist financial institutions in identifying potential customers who are more likely to subscribe.

The dataset used in this project contains information about customer demographics, financial status, and details of previous marketing interactions.

---

## Dataset

The dataset used is the **Bank Marketing Dataset**, which contains information related to direct marketing campaigns conducted by a banking institution.

Key characteristics of the dataset:

- Customer demographic information
- Financial indicators
- Details of previous marketing contacts
- Campaign outcomes

Target variable:


---

## Project Workflow

The project follows a structured data science workflow:

### 1. Data Loading
The dataset is loaded and inspected to understand its structure and features.

### 2. Data Preprocessing
Data preprocessing steps include:

- Handling categorical variables
- Encoding categorical features
- Feature scaling
- Preparing the dataset for model training

### 3. Exploratory Data Analysis (EDA)
Exploratory analysis was performed to understand relationships between features and the target variable. Visualizations were created to observe patterns and trends in the data.

### 4. Model Development

Two machine learning models were implemented:

- Logistic Regression
- Random Forest Classifier

These models were trained to predict the probability of a customer subscribing to a term deposit.

### 5. Model Evaluation

The models were evaluated using several performance metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve

Since the dataset is imbalanced, special attention was given to **Recall and F1-score** for the positive class.

### 6. Model Explainability

To interpret the model's predictions, **SHAP (SHapley Additive exPlanations)** was used.

Explainability techniques included:

- SHAP Summary Plot to identify globally important features
- SHAP Waterfall Plots to explain individual predictions

This helps understand how different features influence the model’s decisions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SHAP
- Jupyter Notebook

---

## Key Insights

- Random Forest performed better than Logistic Regression in identifying customers likely to subscribe.
- Features such as **call duration, previous campaign outcomes, and contact information** significantly influence prediction results.
- Explainable AI techniques helped interpret model predictions and provided transparency into decision-making.

---

## Project Structure


---

## Conclusion

This project demonstrates how machine learning can be used to support marketing strategies in the banking sector. By identifying customers with a higher likelihood of subscribing to a term deposit, banks can improve the efficiency of their marketing campaigns and optimize customer engagement strategies.

---

## Author

Muhammad Hamid Hussain
Mathematics Graduate | Aspiring Data Analyst / Data Scientist
