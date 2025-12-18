# Loan Default Risk — Machine Learning Project

This project builds a transparent, interpretable Machine Learning model using logistic regression to estimate the probability that a small business loan will default. The goal is to support data-driven lending decisions by analyzing borrower characteristics, loan attributes, and financial indicators.

This project focuses on both **model performance** and **business interpretation**, allowing stakeholders to understand *why* the model makes certain predictions.

---

## 🔍 Project Objective

Banks and lenders face financial risks when issuing small business loans.  
This project aims to:

- Predict the likelihood that a loan will default  
- Identify the most important predictors of default  
- Provide actionable insights to improve lending strategy  
- Demonstrate interpretable modeling through logistic regression  

---

## 📊 Dataset Description

The dataset includes historical SBA (Small Business Administration) loan records, with fields such as:

- **Loan Amount**
- **Term Length**
- **Interest Rate**
- **Business Category**
- **State**
- **Urban/Rural Indicator**
- **Bank Guarantee Percentage**
- **Default Status (Target Variable)**

The data was cleaned, encoded, and prepared for modeling inside the Jupyter Notebook.

---

## 📈 Machine Learning Approach

### **1. Data Cleaning & Preparation**
- Removed nulls and inconsistent records  
- Encoded categorical variables  
- Handled skewness and outliers where appropriate  
- Train-test split for fair evaluation  

### **2. Class Imbalance Handling**
Since default cases are rare, imbalance techniques were applied:
- Class weights  
- Threshold tuning  
- Careful metric evaluation  

### **3. Logistic Regression Model**
Model chosen because it is:
- Highly interpretable  
- Fast and stable  
- Business friendly 

### **4. Model Evaluation**
The model was evaluated using:

- **Precision / Recall**  
- **Confusion Matrix**  
- **Classification Report**  
- **Probability Threshold Analysis**  

### **5. Interpretation**
- Coefficients were converted into **odds ratios**  
- Feature importance tied back to lending decisions  
- Thresholds were tested to find the ideal approval cut off  

---

## 💼 Business Value

This ML model helps lenders understand:

- Which loans are too risky  
- Which borrower/business characteristics matter most  
- How approval thresholds affect revenue vs. risk  
- How to design smarter lending policies  

It also demonstrates your ability to combine **analytics**, **business reasoning**, and **machine learning**.

---

## 📁 Files Included in This Repository

- Full machine learning analysis  
- Dataset used in the project 
 
---

## 🛠 Tools & Technologies

- **Python** (pandas, NumPy, Scikit-learn)  
- **Matplotlib / Seaborn** for visualization  
- **Logistic Regression** for modeling  
- **ROC & evaluation metrics**  
- **Jupyter Notebook**  

---

## 🧠 What I Learned

- How to build interpretable ML models  
- How to analyze imbalanced classification problems  
- How to evaluate models beyond accuracy  
- How to translate model output into **business recommendations**  
- How threshold adjustments impact real-world decisions  

---

## 🔗 Connect With Me

- **Portfolio:** https://hashimgilani.github.io  
- **LinkedIn:** https://linkedin.com/in/syedhashimgilani  
- **Email:** hashimgilani331@gmail.com  

⭐ *Thanks for reviewing this machine learning project!*
